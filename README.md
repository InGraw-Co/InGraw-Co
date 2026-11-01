# Hey, I'm Mateusz! 👋

I'm a 15-year-old electronics and software developer from Poland, and the founder of **InGraw Co.**

I design my own hardware, write software for it, and spend a lot of time figuring out how computers actually work — not just how to use them.

My projects range from custom PCBs and embedded Linux systems to handheld consoles, single-board computers, desktop applications, and games.

I enjoy working on things that involve both hardware and software. Designing a PCB is one thing. Getting it to boot Linux, initialize its memory, load drivers, and display a working desktop is something else entirely.

And that's exactly the kind of challenge I like.

## 🚀 What I'm working on

### 🖥️ InGraw Core 3 PRO — My own single-board computer

One of my biggest hardware projects so far.

Instead of building another development board around a microcontroller, I wanted to design a real Linux-capable computer from scratch.

**Hardware:**
- **SoC:** Allwinner H616 — Quad-core ARM Cortex-A53
- **GPU:** ARM Mali-G31
- **RAM:** 1 GB DDR4
- **Storage:** eMMC
- **PCB:** Custom 6-layer board, approximately 33.7 × 31 mm
- **Interfaces:** HDMI, USB-C power, microSD

I've worked on DDR4 initialization, bootloader configuration, eMMC booting, Linux bring-up, and hardware debugging.

After plenty of experiments, failed boots, and debugging sessions, I managed to boot my own Linux-based operating system directly from the onboard eMMC and reach a graphical desktop.

Seeing a computer I designed actually boot an operating system was one of my biggest milestones.

### 🐧 InGrawOS — My Linux-based operating system

I'm developing **InGrawOS**, a custom Linux-based system for my hardware projects.

It involves much more than changing the desktop wallpaper.

I've been working with:
- U-Boot and the Linux kernel
- Buildroot, Debian, and Armbian-based environments
- Device trees and hardware configuration
- Linux drivers and embedded peripherals
- Wayland, labwc, and Qt
- Custom graphical interfaces
- Boot optimization and system debugging

I'm especially interested in the entire boot process — from the SoC's BootROM and memory initialization to the kernel, userspace, and graphical interface.

### 🎮 InConsole — Custom handheld gaming consoles

I also design my own handheld gaming hardware.

One of my projects, **InConsole 2.0**, is a custom console built around the Allwinner T113-S3.

It features:
- Dual-core ARM Cortex-A7 processor
- 128 MB DDR3 memory
- 4.3-inch LCD
- Custom PCB
- Physical buttons and joystick
- Speaker and battery-powered operation
- Custom Buildroot-based Linux system

I've worked on the hardware design, Linux configuration, audio support, and software integration.

The goal is to build a complete handheld console, not simply put a Raspberry Pi inside a 3D-printed enclosure.

### 🌐 InGraw Platform

I'm also developing the software side of InGraw, including its website, applications, and tools.

One of the ideas behind the platform is **InConsole Custom**, a configurator for creating personalized console designs.

I enjoy building systems where hardware, software, user interfaces, and design all connect together.

### 👾 The Pilunia — Game development

Hardware isn't my only interest.

I'm also creating **The Pilunia**, a story-driven horror game developed in Unreal Engine 5.

The project involves worldbuilding, environmental storytelling, 3D environments, gameplay mechanics, puzzles, and a fictional world with its own history.

Game development gives me a chance to combine programming with creativity, visual design, and storytelling.

## 🛠️ Technologies & Skills

**Programming**
- C++ — my primary programming language
- Python
- GDScript
- HTML and web technologies
- Shell scripting and Linux development

**Hardware & Embedded Systems**
- PCB and schematic design
- Multilayer PCB development
- ARM-based SoCs and microcontrollers
- DDR memory and eMMC integration
- Embedded Linux bring-up
- U-Boot, Buildroot, and Linux kernel configuration
- SPI, I²C, UART, USB, and other interfaces
- Hardware debugging and troubleshooting
- Soldering, prototyping, and electronics repair

**Software & Creative Tools**
- Visual Studio Code / VSCodium
- EasyEDA
- Unreal Engine 5
- Godot and Unity
- Blender
- Affinity
- Arduino IDE
- Git and GitHub
- Linux development environments
- 3D printing and mechanical design

## 🧠 How I approach engineering

I'm interested in understanding computers at every level.

Not just writing an application, but understanding how the processor executes it.

Not just connecting RAM, but understanding how memory initialization works.

Not just installing Linux, but understanding how the bootloader, kernel, drivers, and userspace fit together.

I prefer building and experimenting over following tutorials without understanding what's happening.

And yes, sometimes that means spending days debugging something that turns out to be one tiny configuration mistake. 😭

I also believe that choosing reliable components and designing things properly is usually worth the extra cost. Saving a few dollars isn't much of a saving if it costs several days of debugging.

And when a component doesn't survive an experiment?

Well, it might end up in my personal **Museum of Disasters**. 💀

## 🎯 My goals

I want to keep developing InGraw into an ecosystem of hardware and software that I've designed and built myself.

I'm particularly interested in:
- Designing increasingly advanced single-board computers
- Developing custom Linux systems and embedded software
- Understanding SoC architecture and low-level hardware
- Creating original electronic devices
- Connecting hardware with intuitive software
- Improving my skills through ambitious, real-world projects

I'm still learning, and there's a lot I don't know yet. But that's what makes engineering interesting.

Every successful boot, working PCB, fixed bug, and completed project teaches me something new.

## 📫 Contact

- **Website:** [ingraw.com](https://ingraw.com)
- **InGraw Co.:** [ingrawco@outlook.com](mailto:ingrawco@outlook.com)
- **Personal:** [mateuszlademann8@gmail.com](mailto:mateuszlademann8@gmail.com)

---

### "A co, jeśli zadziała?"
*What if it works?*

That's the idea behind InGraw.

Sometimes a project seems too complicated, too ambitious, or just unlikely to work.

But I'd rather try to build it and learn something than never find out whether it was possible.

**Thanks for visiting my GitHub! 🚀**
