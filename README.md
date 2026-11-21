# Hi, I’m Wamphyre

I’m a Unix sysadmin and software developer with **10 years of experience**. I build open-source tools for FreeBSD, Linux, and macOS, develop audio software in C++, and make pixel-art games as **Wamphyre Studio**. I’m also a black metal musician.

![Animated ASCII terminal banner reading Wamphyre and cycling through Unix systems, C++ audio and DSP, retro game development, and AI coding agents](./wamphyre-ascii.gif)

## Retro games

[**Wamphyre Studio on itch.io**](https://wamphyre.itch.io/) is my solo studio for pixel-art games inspired by 16-bit consoles, dark fantasy, and horror.

- [**El Huésped**](https://wamphyre.itch.io/el-huesped) is a horror adventure for the Sega Mega Drive set in an abandoned clinic.
- [**Monster Chess**](https://wamphyre.itch.io/monster-chess) is a supernatural chess game with branching endings.

### YmirPS5

[**YmirPS5**](https://github.com/Wamphyre/YmirPS5) is my PlayStation 5 port of the [Ymir Sega Saturn emulator](https://github.com/ymir-emu/Ymir). It brings Saturn emulation to PS5 with a DualSense interface, Vulkan rendering, and support for original Saturn CDs via USB optical drives.

## Building software with AI agents

I use AI coding agents to prototype and build applications, software tools, and games. I’m good at turning a rough idea into clear direction for an agent, using examples and focused feedback to refine each iteration. I bring my own creative judgment to the result, from how the code is structured to how the interface looks and feels.

```text
+--------------------------------------------------------+
|  wamphyre@studio:~/ai                       [ RELEASE ]|
|                                                        |
|              /\                        /\              |
|          ___/  \__      /\  /\      __/  \___          |
|          \        \____/  \/  \____/        /          |
|           \__/\__     .        .     __/\__/           |
|                  \____/\/\__/\/\____/                  |
|                                                        |
|                 LIQUIDVAMP R4 / 1.7B                   |
|                                                        |
|  > AGENTS    context / tools / iterative review        |
|  > HARNESS   task execution / output evaluation        |
|  > MODEL     LoRA post-training / BF16 GGUF            |
|  > RUNTIME   llama.cpp / Vulkan / Linux                |
+--------------------------------------------------------+
```

### Agents, harnesses, and local LLMs

I work with coding agents and their harnesses to build software. I shape the context agents receive, decide which tools they can use, and evaluate their output as I iterate. I also build and tune local inference setups on Linux using `llama.cpp` and Vulkan.

I published **LiquidVamp-R4-1.7B**, an experimental LFM3-based model that I adapted with supervised LoRA post-training. The release includes a merged Safetensors checkpoint and a BF16 GGUF build. I tested local inference on Ubuntu with a Radeon RX 6600 using `llama.cpp` and Vulkan. [Model on Hugging Face](https://huggingface.co/WamphyreAI/LiquidVamp-R4-1.7B) · [Technical specification](https://huggingface.co/WamphyreAI/LiquidVamp-R4-1.7B/blob/main/TECHNICAL_SPEC.md)

## Audio, systems, and desktop software

| Project | What it does |
| --- | --- |
| [**oXygen**](https://github.com/Wamphyre/oXygen) | C++ and JUCE mastering suite with an automatic mastering assistant, reference matching, and DSP regression tests. |
| [**BeastNgine**](https://github.com/Wamphyre/BeastNgine) | FreeBSD web-stack automation for Nginx, Varnish, PHP-FPM, and Valkey. |
| [**DrumCraker**](https://github.com/Wamphyre/DrumCraker) | Drum sampler with DrumGizmo kit support, multichannel routing, and MIDI humanization. |
| [**miloOS**](https://github.com/Wamphyre/miloOS-core) | Turns Debian 13 with XFCE into a **low-latency audio workstation**, with PipeWire, WirePlumber, and JACK compatibility preconfigured. |
| [**SuperSnippet**](https://github.com/Wamphyre/SuperSnippet) | Portable C++ utility for Windows with code snippets, clipboard history, global hotkeys, and local SQLite storage. |
