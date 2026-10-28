<img width="896" height="1195" alt="DevToolkit" src="https://github.com/user-attachments/assets/9baec82d-8075-47d4-9ec6-ea24b58469fa" />

### **Morphs DevToolkit — The Offline Developer Workstation**
*Air-Gapped Regex Workbench, Multi-Syntax Formatter, Cryptographic Hasher & JWT Security Inspector*

#### **Overview: Stop Pasting Sensitive Code into Cloud Websites**
Every day, developers paste proprietary source code, database queries, API payloads, and sensitive customer JSON Web Tokens into random "free" online formatters and regex testers. Most web-based utilities quietly log your input, store your clipboard data on external servers, or expose your enterprise infrastructure to data leakage.

**Morphs DevToolkit** is a lightweight, zero-dependency, 100% offline developer workstation built specifically for Windows. It provides all your daily core utility tools inside a single portable executable with **zero cloud connections, zero tracking, and absolute data privacy**. What you paste into Morphs DevToolkit stays in your machine’s RAM and never leaves your workstation.

#### **Key Features & Built-in Tooling**

##### 🔍 **1. Interactive RegEx Workbench**
* **Real-Time Evaluation:** Test regular expressions with live pattern evaluation and multiline colorized highlighting.
* **Smart Flag Matrix:** One-click toggles for Case-Insensitive `(i)`, Multiline `(m)`, and DotAll / Singleline `(s)`.
* **Built-in Developer Preset Codex:** Instant, pre-tested patterns for RFC 5322 Emails, IPv4, IPv6, Web URLs, UUIDv4 tokens, ISO 8601 Timestamps, Credit Card masks, and SemVer versioning strings.
* **Group Capture Inspector:** Tabular breakdown displaying match indexes, lengths, and isolated capture groups ($1, $2, etc.).
* **Substitution & Replacement Engine:** Live regex-based find-and-replace with real-time preview.

##### 📐 **2. Code & Data Formatter Studio**
* **Multi-Syntax Engine:** Instant formatting, beautification, and minification for **JSON**, **HTML5 / XML**, and **SQL queries**.
* **Lenient HTML5 Support:** Unlike rigid XML formatters that crash on modern web documents, DevToolkit seamlessly handles HTML5 void tags (`<meta>`, `<link>`, `<img>`, `<br>`, `<input>`) without errors.
* **Selection-Aware In-Place Case Conversion:** Highlight a variable, sentence, or word in either the input or output buffer to convert it immediately to `UPPERCASE`, `lowercase`, `Title Case`, `Sentence case`, or `iNVERT cASE` without losing your selection or altering surrounding code.
* **Live Syntax Highlighting:** Visual colorization for markup tags, attributes, and strings.

##### ⚡ **3. Converters & Hardware Hash Suite**
* **Instant Encoders & Decoders:** Bidirectional Base64 (UTF-8) and URL Percent-Encoding/Unescaping.
* **Unix Epoch Clock:** Real-time UTC and Local date/time conversion with live "Current Epoch" timestamp generation.
* **Batch UUIDv4 Generator:** Generate cryptographically random RFC 4122 GUID tokens in batches of 1, 5, 10, or 25 with uppercase/lowercase toggles.
* **Cryptographic Hasher:** Simultaneous single-click generation of **MD5**, **SHA-1**, **SHA-256**, and **SHA-512** hashes.
* **Hardware Checksum Match Verifier:** Paste a vendor's published SHA-256 hash to perform instant, bit-exact verification with a clear Green (Confirmed) or Red (Mismatch) integrity badge.

##### 🛡️ **4. Dedicated JWT Security Token Inspector**
* **Client-Side Decoding:** Decode JSON Web Tokens (JWT) into clean, readable JSON trees for Headers and Payloads with zero server roundtrips.
* **Live Expiration Sentry:** Automatically evaluates `exp`, `iat`, and `nbf` claims against system clocks, flagging expired tokens in high-contrast red and valid tokens in active green.
* **One-Click Notepad Dump:** Export complex token headers, claims, and signatures directly into Windows Notepad for side-by-side audit reviews.

##### 📝 **5. Universal Scratchpad Drawer & Workspace Ergonomics**
* **Collapsible Side Drawer:** Universal notes panel accessible from any tab for staging temporary snippets, API tokens, and scratch notes.
* **Multi-Tab File Autoloader:** Open any `.ps1`, `.html`, `.json`, `.sql`, or `.txt` file once, and DevToolkit automatically broadcasts it across all inspection tabs simultaneously.
* **External Editor Bridge:** Instant 1-click export of any buffer to Windows Notepad.
* **High-DPI & Multi-Theme UI:** WCAG AAA high-contrast themes including **Nordic Frost**, **Dark Stealth (OLED)**, and **Soft Slate Light**, with dynamic font scaling (Normal 9.5pt and Large 11.5pt).

#### **Privacy & Security Guarantee**
* **100% Offline Execution:** Contains zero telemetry endpoints, analytics trackers, or network sockets.
* **Portable & Self-Contained:** Runs immediately without installer packages, Node.js runtimes, Python environments, or administrative rights.
* **Local Folder Persistence:** Saves your preferences, window bounds, and themes right next to the executable in `settings.json`.

#### **System Requirements**
* **Operating System:** Windows 10 or Windows 11 (64-bit recommended)
* **Runtime:** Built-in Windows PowerShell 5.1+ (Native to Windows — no extra installations needed)
* **Architecture:** Standalone Portable `.exe` or Contiguous `.ps1` Script
