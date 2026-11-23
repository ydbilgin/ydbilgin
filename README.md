## Yasin Derya Bilgin

Computer Engineering graduate (KTO Karatay University). I build Windows desktop
software and browser extensions — mostly small tools that fix something that
annoyed me on my own machine, then get maintained until they actually work.

### Projects

**[KickFlow](https://github.com/ydbilgin/kickflow)** — Chrome MV3 extension
(TypeScript) that preserves local chat context on Kick.com when messages
disappear from the page after moderation events. The page doesn't expose a
stable message id, so the extension reconstructs one and reconciles it against
the site's live event stream as rows are virtualised in and out of the DOM.
Message storage is bounded on two axes so a fast chat cannot evict the messages
the extension exists to preserve. No backend, no account automation, and no
`innerHTML` anywhere in the source. 730 passing tests across 63 files.

**Windows Care Kit** (0.2.0-beta)
— early C#/WPF toolkit for Windows reinstall and maintenance: settings backup,
migration to a fresh install, cleanup, uninstall. Direct calls to the file,
directory and registry deletion APIs I banned fail the build, so destructive
operations have to go through the safety gate rather than around it. Its package
manifest was merged into
[microsoft/winget-pkgs](https://github.com/microsoft/winget-pkgs/pull/399259).

**[MouseFence](https://github.com/ydbilgin/MouseFence)** — Rust tray app for
multi-monitor Windows setups: each screen edge lets the pointer cross freely, only
with a firm push, or never, so the cursor stops drifting onto the wrong screen.
A low-level mouse hook with a Win32-free decision core, tested against the
earlier C# version's behaviour row by row.

**[snip](https://github.com/ydbilgin/snip)** — Rust screenshot tool for Windows 11:
Win+Shift+S snips that freeze every monitor, an annotation editor, all-screens
capture, short MP4/GIF recordings and OCR text copy (it replaced my earlier
WinTextCapture). One small exe with no network code.

### Elsewhere

C#, .NET, WPF, TypeScript, Rust. Java and Spring Boot from coursework and
internships — those repos are still here.

[LinkedIn](https://www.linkedin.com/in/ydbilgin)
