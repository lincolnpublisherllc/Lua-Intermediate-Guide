README (not included in the ZIP)
What’s inside

Folders per chapter, e.g. Chapter 01 - Core Syntax and Concepts Refresher/

Code files extracted in reading order as code_01.lua, code_02.lua, etc.

When a block wasn’t clearly Lua (e.g., Makefile, Ninja, Dockerfile, or a .rockspec), I saved it with a matching extension:

.rockspec for LuaRocks specs

.Makefile for Make targets

.ninja for Ninja builds

.Dockerfile for Docker snippets

.sh for shell-like blocks without clear Lua end tokens

If a chapter didn’t contain extractable code, you’ll see _NO_CODE_FOUND.txt in that folder.

How I extracted it

Parsed the uploaded DOCX, detected fenced code blocks where present.

If fences weren’t present, I used a conservative Lua-aware heuristic to group consecutive “code-ish” lines (things starting with local, function, return, --, typical library calls like io.*, os.*, etc.).

This keeps prose out and captures runnable snippets as faithfully as the document allows. Source: the uploaded manuscript. 

Lua Intermediate Guide

Notes and limitations

Some examples in the book are shown across multiple small snippets. I saved each snippet separately to avoid merging unrelated examples.

If you prefer different filenames (e.g., report/core.lua, report/format.lua), tell me your desired structure and I’ll reorganize the ZIP accordingly.

If any snippet should be grouped as one file (for instance, a multi-part example spread across the chapter), flag it and I’ll merge those into a single file.

Quick start (example)

If you want to run the extracted grade-report refactor from Chapter 1, copy the related code_XX.lua files into a small project and require them as shown in the book’s examples (e.g., report/core.lua, report/format.lua, report/cli.lua, and a main.lua wrapper). The ZIP includes the raw snippets; file/folder naming in your project can follow the book’s suggested layout.

If you want me to:

rename files to match the exact module paths shown in the chapters,

split or merge specific blocks,

or add a root README.md inside the ZIP mapping each file to the page/section,

say the word and I’ll ship a fresh ZIP.
