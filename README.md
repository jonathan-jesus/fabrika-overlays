# 🎬 fabrika-overlays-releases-draft

This is a derivative of a tool I designed and developed entirely on my own a couple of years ago. I initially built it to solve my own workflow challenges, and later shared it with colleagues. It was a personal initiative that proved useful in that work context. This tool addresses a very specific need, but for those who do face this challenge, it can be a real time-saver.

This app allows you to combine videos, variable information for each video, and artwork, then output either a video editing project (Final Cut XML Exchange format, which can be imported into most modern editing tools) or image overlays (PNGs) for each video.

📦 Download links (latest version)

[Fabrika Overlays 0.1.0.1 - portable](https://github.com/jonathan-jesus/fabrika-overlays-releases-draft/releases/download/0.1.0.1/Fabrika-Overlays-0.1.0.1-win-portable.zip)

[Fabrika Overlays 0.1.0.1 - win x64](https://github.com/jonathan-jesus/fabrika-overlays-releases-draft/releases/download/0.1.0.1/Fabrika-Overlays-0.1.0.1-win-x64.zip)

[Fabrika Overlays 0.1.0.1 - win x86](https://github.com/jonathan-jesus/fabrika-overlays-releases-draft/releases/download/0.1.0.1/Fabrika-Overlays-0.1.0.1-win-x86.zip)


# ⚙️ Philosophy Behind the Tool

Instead of manually editing each video, you define a single visual layout and feed it with a spreadsheet of data. The tool takes care of the rest: generating ready-to-use overlays that match your data and media.
It’s interoperable with existing editing workflows, thanks to outputs like PNGs and Final Cut XML (importable into most modern editing software).

![Basic diagram of the tool](images/diagram.jpg?raw=true)

# 🛠️ Requirements

Windows 10+

1280px X 720px + screen

.NET 8 Runtime (only for portable version, the other releases are self contained)

# 📚 How to use
[![Tutorial 1](images/example1-video-thumbnail.png?raw=true)](https://www.youtube.com/watch?v=AHgMzBAnnP0)

Text guide: [Tutorial 1: Apply a Fixed Overlay to Multiple Videos](examples/example1)

[![Tutorial 2](images/example2-video-thumbnail.png?raw=true)](https://www.youtube.com/watch?v=0Q6QUYnllk0)

Text guide: [Tutorial 2: Personalized Overlays with Spreadsheet Data](examples/example2)

**Interface**

Basic interface description
![Basic UI description](images/ui-01.jpg?raw=true)

1. Left Panel
Project settings, layers of selected group/layer
2. Properties panel
Properties of selected object.
Text (Text objects only): text value settings
3. Right panel
Sources: Data set, Media set, Action history
4. Preview panel
5. Timeline (not interactive yet)/Group layers
Visually inspector of video tracks and grouplayer tracks. In/out transitions and animations are planned for version 0.2 (expected Nov 2025).

Detailed interface description
![Detailed UI description](images/ui-02.jpg?raw=true)

# 🚀 Going Forward

There are several opportunities to improve this tool. I’d like to continue developing it, but future work depends on reaching a sufficiently large audience. Consider this section a declaration of intent: if the tool gains adoption, I’ll keep updating and expanding it.

Planned improvements include:

* In-place creation/editing of datasets

* A more responsive video preview player

* Export of encoded videos (currently exports editing projects in Final Cut XML format)

* In/out layer group animations

* Interactive timeline

* Cross-platform support (Windows/Linux/Mac)


# ❗ License

Unrestricted Binary Software License (Public Domain Style)

This software is released to the public without any restrictions.

You are free to (but not limited to):
* Use the software for any purpose, commercial or non-commercial

* Copy, distribute, and share it

* Install the software on as many devices as you like

You should NOT: 
* Include or redistribute the software in your own projects, products, or services

* Claim authorship of the project

This software is provided "as is", without warranty of any kind. The author assumes no liability for any damages or losses resulting from its use.

# 🔹 Third-Party Content Used in This Project

This project uses the following:

ExcelDataReader.3.6.0

MediaToolkit.1.1.0.1

Ookii.Dialogs.Wpf.5.0.1

PixiEditor.ColorPicker.3.4.1

MediaInfo
