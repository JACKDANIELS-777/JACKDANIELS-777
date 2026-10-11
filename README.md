# Hi, I'm Jack 👋

Systems programmer from South Africa. I build **languages, compilers and interpreters**, mostly from scratch and
often in raw assembly, and I write **ASP.NET backends** for work and study.

I started with Python about 8 years ago. Most of what's below was written without frameworks, and some of it in Notepad.

---

## ⭐ Highlights

| Project | What it is | Size |
|---|---|---|
| **[Masm_Gui](https://github.com/JACKDANIELS-777/Masm_Gui)** | A Windows GUI framework in pure **x64 MASM**: self-drawn controls, a layout parser that builds UIs from one string, and **TrenchScript**, a scripting language with its own VM | ~10,600 lines of asm |
| **[Nasm_Interpreter](https://github.com/JACKDANIELS-777/Nasm_Interpreter)** | An expression interpreter in **x64 NASM**: lexer, recursive parser, a real AST in a hand-managed arena, tree-walking evaluator | ~1,400 lines of asm |
| **[Assembler_Diamant](https://github.com/JACKDANIELS-777/Assembler_Diamant)** | Compiles a small register-level language straight to **x86-64 machine code** (REX, ModR/M, call fix-ups), with no assembler involved | ~1,900 lines of Python |
| **[Diamant_OS](https://github.com/JACKDANIELS-777/Diamant_OS)** | A tiny OS in **x86 assembly**: boot sector, 32-bit protected mode, its own interrupts and keyboard driver, a hand-made bitmap font in VGA mode 13h | ~2,300 lines of asm |
| **[Excel_Interpreter](https://github.com/JACKDANIELS-777/Excel_Interpreter)** | A programming language that runs **inside Excel**: lexer and interpreter in VBA, with a bridge out to Python | ~1,800 lines of VBA |

## 💎 The Diamant projects

Diamant is my own language. Each repository is a separate project that explores a different part of building one:

* **[Diamant](https://github.com/JACKDANIELS-777/Diamant):** a tree-walking interpreter that can call **Python and C** from the same program.
* **[Diamant_Compiler](https://github.com/JACKDANIELS-777/Diamant_Compiler):** compiles Diamant to 32-bit NASM for **bare metal** (no OS needed).
* **[Assembler_Diamant](https://github.com/JACKDANIELS-777/Assembler_Diamant):** source → raw x86-64 bytes.
* **[Diamant_Assembler](https://github.com/JACKDANIELS-777/Diamant_Assembler):** an x86-64 instruction encoder, checked byte-for-byte against NASM.
* **[Diamant_OS](https://github.com/JACKDANIELS-777/Diamant_OS):** the bootable OS above.
* **[Diamant_Int](https://github.com/JACKDANIELS-777/Diamant_Int):** an early version's page: C DLLs and the Windows API from Diamant.

## 🧪 More experiments

* **[MASM-GemmaStrike](https://github.com/JACKDANIELS-777/MASM-GemmaStrike):** an x64 MASM front end for Google's Gemma model, with a small Python bridge.
* **[JSE_intreperter](https://github.com/JACKDANIELS-777/JSE_intreperter):** a language parser in legacy Microsoft JScript.
* **[AST-Csharp-Automarker](https://github.com/JACKDANIELS-777/AST-Csharp-Automarker):** grades C# code by walking its syntax tree.


---

## 🧰 Tech

* **Assembly:** x64 MASM, NASM, x86 bare metal, Win32 API
* **Languages:** Python, C#, C, VBA, JavaScript
* **Backend:** ASP.NET Core MVC, SignalR, EF Core, SQL Server, Identity, Azure
* **Concepts:** lexers and parsers, ASTs, code generation, machine-code encoding, OS boot and interrupts

## 📈 Right now

* Building **FoosNet**, a real-time multiplayer foosball game: ASP.NET Core + SignalR, with server-side physics,
  accounts, bans and match replays, hosted on Azure.
