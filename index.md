Hello! 

I'm trying to create simple (physical) Aircraft Panels and Control Panels for Flight Simulators (Primarely MSFS24). you will find on this website all the files, docs, parts for my crations.

## Conception
- Panels models (3D models) are creating using [Fusion 360](https://www.autodesk.com/products/fusion-360/personal)
- Part are 3D Printed, using a bambulab A1, with AMS for multi color / material parts
- Electronic parts (wire, switches, etc), are comming from different stores, but overall it can always be found on Amazon, Aliexpress, etc..
- Controler/Interface are (for now) Arduino based
- Frimware and software are provided by [MobiFlight](https://docs.mobiflight.com/)

## Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url | relative_url }}) - {{ project.description }}
{% endfor %}


## License

![Documentation & File License](https://img.shields.io/badge/licence-CC_Attribution-green)
![GitHub License](https://img.shields.io/github/license/Gaudv/simpanels)

The content of this site itself, documentation, files, is licensed under the [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/). The sources, code files, configurations,  and the underlying source code of this site and of all listed projects is licensed under the [MIT license](https://github.com/Gaudv/simpanels/blob/main/LICENSE).