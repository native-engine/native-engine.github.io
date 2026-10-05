## WORKING TOOLS USED • ИСПОЛЬЗУЕМЫЙ РАБОЧИЙ ИНСТРУМЕНТАРИЙ

I have never been a proponent of russian software — let alone russian internet services — and have always considered myself an independent developer rather than a russian one; when runet finally degraded to cater to the uncompetitive «Gazprom-media», I deleted my russian-language blog and no longer wish to promote myself in Russia.

Я никогда не был сторонником ни российского программного обеспечения, ни тем более российских интернет-сервисов, и всегда считал себя не российским, а именно независимым разработчиком, а когда рунет окончательно деградировал в угоду неконкурентоспособному «Газпром-медиа», я удалил свой русскоязычный блог и больше не желаю продвигаться в России.

![Native Engine Banner](images/Manjaro Linux.png)

## SOFTWARE • ПРОГРАММНОЕ ОБЕСПЕЧЕНИЕ

* Operating system • Операционная система: [Manjaro Linux](https://manjaro.org/) + [KDE Plasma](https://kde.org/plasma-desktop/)
* Web browser • Веб-браузер: [Chromium](https://www.chromium.org/Home/)
* Office suite • Офисный пакет: [OnlyOffice](https://www.onlyoffice.com/)
* File manager • Файловый менеджер: [Double Commander](https://doublecmd.sourceforge.io/)

---

* Raster editor • Растровый редактор: [GIMP](https://www.gimp.org/)
* Vector editor • Векторный редактор: [Inkscape](https://inkscape.org/)
* Publishing system • Издательская система: [Scribus](https://www.scribus.net/)
* Font editor • Редактор шрифтов: [FontForge](https://fontforge.org/en-US/)

---

* 3D graphics and motion design • 3D-графика и моушн-дизайн: [Blender](https://www.blender.org/)
* Video editor • Редактор видеомонтажа: [Kdenlive](https://kdenlive.org/)*
* Sound editor • Звуковой редактор: [Audacity](https://www.audacityteam.org/)
* Digital audio workstation • Цифровая звуковая рабочая станция: [Ardour](https://ardour.org/)

---

* Development environment and RAD editor • Среда разработки и RAD-редактор: [Qt](https://www.qt.io/)
* Compilers: [GCC](https://gcc.gnu.org/) and [Crosstool-NG](https://crosstool-ng.github.io/) for current and older versions of Linux, and [MinGW-w64](https://www.mingw-w64.org/) for Windows
* Компиляторы: [GCC](https://gcc.gnu.org/) и [Crosstool-NG](https://crosstool-ng.github.io/) для актуальной и старых версий ОС Linux и [MinGW-w64](https://www.mingw-w64.org/) для ОС Windows

![Native Engine Banner](images/Kdenlive.png)

> [Davinci Resolve video editor is quite difficult to download, does not support all video cards, and has very few supported codecs](https://wiki.archlinux.org/title/DaVinci_Resolve#MP4,_H.264,_H.265_and_AAC_Support)

> [видеоредактор Davinci Resolve довольно затруднительно скачать, поддерживает далеко не все видеокарты и слишком мало поддерживаемых кодеков](https://wiki.archlinux.org/title/DaVinci_Resolve#MP4,_H.264,_H.265_and_AAC_Support)


## AUXILIARY UTILITIES • ВСПОМОГАТЕЛЬНЫЕ УТИЛИТЫ

* Publishing • Издательство: [PDF Mix Tool](https://www.scarpetta.eu/pdfmixtool/) + [PDFsam Basic](https://pdfsam.org/)*
* Working with fonts • Работа со шрифтами: [Font Manager](https://github.com/FontManager/font-manager) + [Gucharmap](https://github.com/GNOME/gucharmap)
* Reference Organization • Организации референсов: [PureRef](https://www.pureref.com/)
* Music composition • Написание музыки: Windows plugins wrapper • обёртка Windows-плагинов [Yabridge](https://github.com/robbert-vdh/yabridge)
* Software containers: [AppImage](https://appimage.org/) for Linux and [Inno Setup](https://jrsoftware.org/isdl.php) for Windows
* Контейнеры для ПО: [AppImage](https://appimage.org/) для ОС Linux и [Inno Setup](https://jrsoftware.org/isdl.php) для ОС Windows

---

* Development: [Kate](https://kate-editor.org/) shader and script editor, [CMake](https://cmake.org/) build system, [Ccache](https://ccache.dev/) compilation cache, [AddressSanitizer](https://github.com/google/sanitizers/wiki/AddressSanitizer) memory error detector, [MangoHud](https://github.com/flightlessmango/MangoHud) graphics monitoring overlay, [Wine](https://www.winehq.org/) Windows runtime for Linux, [Okteta](https://apps.kde.org/okteta/) hex editor

* Разработка: редактор шейдеров и скриптов [Kate](https://kate-editor.org/), система сборки [CMake](https://cmake.org/), кэш компиляции [Ccache](https://ccache.dev/), отладчик использования памяти [AddressSanitizer](https://github.com/google/sanitizers/wiki/AddressSanitizer), оверлей для мониторинга графики [MangoHud](https://github.com/flightlessmango/MangoHud), Windows-рантайм для Линукса [Wine](https://www.winehq.org/), шестнадцатиричный редактор [Okteta](https://apps.kde.org/okteta/)

---

* Multimedia: [Open Broadcaster Software](https://obsproject.com/) screen recording program, [HandBrake](https://handbrake.fr/) hardware video converter, [MPV](https://mpv.io/) video player, and [Audacious](https://audacious-media-player.org/) audio player

* Мультимедиа: программа для записи экрана [Open Broadcaster Software](https://obsproject.com/), аппаратный видеоконвертер [HandBrake](https://handbrake.fr/), видеопроигрыватель [MPV](https://mpv.io/) и аудиоплеер [Audacious](https://audacious-media-player.org/)

![Native Engine Banner](images/OBS Studio.png)

> Scribus, a page layout editor, is unable to export PDFs that combine two-page portrait spreads into a single landscape page

> редактор вёрстки Scribus не способен экспортировать PDF-издания с объединением двухстраничных портретных разворотов в одну альбомную страницу


## LIBRARIES AND APIS • БИБЛИОТЕКИ И API

* Platform-specific code for Linux and Windows • Платформенный код для ОС Linux и Windows: [SDL](https://www.libsdl.org/)
* Graphics • Графика: [Vulkan](https://vulkan.lunarg.com/sdk/home) + [OpenGL Mathematics](https://github.com/g-truc/glm)
* Sound • Звук: [OpenAL Soft](https://github.com/kcat/openal-soft) + [Ogg Vorbis](https://xiph.org/downloads/)

---

* Physics • Физика: [Jolt Physics](https://github.com/jrouwe/JoltPhysics)
* Scripting language • Скриптовый язык: [Lua](https://www.lua.org/download.html)
* Compression of game archives • Компрессия игровых архивов: [LZ4](https://github.com/lz4/lz4)
* Loading and saving settings • Загрузка-сохранение настроек: [inifile-cpp](https://github.com/Rookfighter/inifile-cpp)

---

* Model import/export and optimization • Импорт-экспорт и оптимизация моделей: [cglTF](https://github.com/jkuhlmann/cgltf) + [Draco mesh](https://github.com/google/draco) + [Mesh optimizer](https://github.com/zeux/meshoptimizer)
* Image import/export • Импорт-экспорт изображений: [stb](https://github.com/nothings/stb) (JPEG, PNG, BMP, TGA, GIF, PSD, HDR, PIC и PNM)
* Block compression of texture maps • Блочная компрессия текстурных карт: NVIDIA [Texture Tools SDK](https://developer.nvidia.com/gpu-accelerated-texture-compression)

---

### © 2017-2026 Daniil Petrov • Даниил Петров

