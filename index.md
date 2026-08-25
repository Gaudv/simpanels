---
layout: default
---

Hello!

I'm designing and building physical **aircraft control panels** and **cockpit systems** for Flight Simulators, primarily **Microsoft Flight Simulator 2024 (MSFS24)**. 

On this website, you'll find all the 3D models, documentation, parts lists, and firmware for my projects.

---

## Design & Build Philosophy

- **3D Modeling**: [Fusion 360](https://www.autodesk.com/products/fusion-360/personal) for all panel designs
- **Manufacturing**: Bambu Lab A1 3D printer with AMS for multi-color and multi-material parts
- **Electronics**: Standard components from Amazon, AliExpress, and specialty suppliers
- **Control Systems**: Arduino-based microcontrollers for panel integration
- **Software Integration**: [MobiFlight](https://docs.mobiflight.com/) for flight simulator connectivity and microcontrollers firmware

---

## Featured Projects

{% for project in site.projects %}
- **[{{ project.title }}]({{ project.url | relative_url }})** - {{ project.description }}
{% endfor %}

---

## Contributing & Support

Found an issue? Have a suggestion? Feel free to open an issue on [GitHub](https://github.com/Gaudv/simpanels/issues/new).

---

## Licensing

![Documentation & Files License](https://img.shields.io/badge/licence-CC_Attribution-green)
![Code License](https://img.shields.io/github/license/Gaudv/simpanels)

- **Documentation, 3D Models & Files**: Licensed under [Creative Commons Attribution 3.0 Unported](https://creativecommons.org/licenses/by/3.0/)
- **Source Code & Firmware**: Licensed under [MIT License](https://github.com/Gaudv/simpanels/blob/main/LICENSE)

---