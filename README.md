# H-Bridge PCB
<!-- Badges -->
<!-- [![Build Status][build-shield]][build-url] -->
[![GitHub release][release-shield]][release-url]
[![GitHub commits][commits-shield]][commits-url]
[![MIT License][license-shield]][license-url]

[![Twitter][twitter-shield]][twitter-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Follow GitHub][github-shield]][github-url]
[![YouTube][youtube-shield]][youtube-url]


# H-bridge and drivers Eagle PCB design 

<sup> Please download the latest stable release from [here][download-latest]. Please report any bugs in [issues][report-bug].</sup>

This repository is the official PCB of my paper [Design and Hardware Implementation Considerations of Modified Multilevel Cascaded H-Bridge Inverter for Photovoltaic System](https://www.researchgate.net/publication/329921455_Design_and_Hardware_Implementation_Considerations_of_Modified_Multilevel_Cascaded_H-Bridge_Inverter_for_Photovoltaic_System) we published in 2019.

**Special features of the design are**
- Completely modular design. The H-bridge and driver circuits are completely modular. 
- I have included 2 types of driver circuit. The driver circuits are similar design so that these can be connected and disconected with the H-bridge in easy ways. 

## Schematic and PCB
Here is the schematic and PCB of H-bridge circuit
![H-Bridge Circit](./Resources/Full%20bridge%20schematic.png)
![H-Bridge PCB](./Resources/Full%20bridge%20pcb.png)

I have included few types of driver circuit with the project. The driver circuits are modular design on the top of the H-bridge. Here is the IR2111 driver circuit. This circuit is optically isolated. 
![IR2111 Circuit](./Resources/IR2111%20Opto%20Driver%20Schematic.png)
![IR2111 PCB](./Resources/IR2111%20Isolated%20Driver%20PCBboth%20.png)

# How to cite the paper
If you use the driver circuits and PCB design for your research, please cite publication as follow:

- S. Shuvo, E. Hossain, T. Islam, A. Akib, S. Padmanaban and M. Z. R. Khan, "Design and Hardware Implementation Considerations of Modified Multilevel Cascaded H-Bridge Inverter for Photovoltaic System," in IEEE Access, vol. 7, pp. 16504-16524, 2019, doi: 10.1109/ACCESS.2019.2894757.


# Credits
- [Shuvangkar Chandra Das](https://www.linkedin.com/in/shuvangkar/) - Lead Researcher
- Abir Ahsan Akib
- Tanveerul Islam 
- Ziaur Rahman Khan - Project Supervisor
- Eklas Hossain - Project Supervisor

 
# License
MIT


<!-- Social Links -->
[twitter-shield]: https://img.shields.io/twitter/follow/shuvangkar_das?style=social&logo=twitter
[twitter-url]: https://twitter.com/intent/follow?screen_name=shuvangkar_das

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/shuvangkar

[youtube-url]: https://www.youtube.com/channel/UCU6T54Uu5Mgd6NwYbnXaosA
[youtube-shield]: https://img.shields.io/youtube/channel/subscribers/UCU6T54Uu5Mgd6NwYbnXaosA?style=social

[github-shield]: https://img.shields.io/github/followers/shuvangkar?style=social
[github-url]: https://github.com/shuvangkar

[ResearchGate-url]:  https://www.researchgate.net/profile/Shuvangkar-Das
[Google Scholar-url]: https://scholar.google.com/citations?user=ebLUEXQAAAAJ

[build-url]: https://travis-ci.com/github/shuvangkar/SIM800L

[release-shield]: https://img.shields.io/github/release/shuvangkar/SIM800L.svg
[release-url]: https://github.com/shuvangkar/SIM800L

[commits-shield]: https://img.shields.io/github/commits-since/shuvangkar/SIM800L/v0.1.0
[commits-url]: https://img.shields.io/github/commits-since/shuvangkar/SIM800L/v0.1.0


[license-shield]: https://img.shields.io/github/license/shuvangkar/SIM800L
[license-url]: https://github.com/shuvangkar/SIM800L/blob/master/LICENSE.txt



<!-- Product Screenshot -->
[product-screenshot]: resources/screenshot1.png

<!-- Download links -->
[download-latest]:https://github.com/shuvangkar/SIM800L/releases/latest
[report-bug]: https://github.com/shuvangkar/SIM800L/issues/new