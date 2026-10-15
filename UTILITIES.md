## UTILITIES • УТИЛИТЫ

Game archive packager: A BASH script that compiles Lua scripts into LuaC format and packages game archives using a custom utility called `AssetCompressor`; these functions will eventually be integrated into the game world editor.

Упаковщик игровых архивов: BASH-скрипт, компилирующий Lua-скрипты в формат LuaC и упаковывающий игровые архивы самописной утилитой `AssetCompressor`, в будущем эти функции войдут в состав редактора игрового мира.

![AssetCompressor Screenshot](images/AssetCompressor.png)

The `luac` utility is used for compiling Lua scripts, while the `glslang` utility is used for compiling GLSL shaders into the SPIR-V format.

Для компиляции Lua-скриптов используется утилита `luac`, а для компиляции GLSL-шейдеров в формат SPIR-V используется утилита `glslang`.

---

### © 2017-2026 Daniil Petrov • Даниил Петров