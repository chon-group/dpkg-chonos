# ChonOS - A Specific-Purpose GNU/Linux Distribution for Embedded BDI-based Multi-Agent Systems

|![](???)|
|:--:|
|The chonOS is a ready-to-go GNU/Linux distribution that integrates several existing solutions to abstract technological dependencies in embedding MAS in hardware platforms. In addition, it offers a framework for Embedded MAS programming to control hardware devices and support the development of mobile or IoT agents.|


## How to use?
1) Download the chonOS for your single-board computer, below are the available models:

||||
|:-:|:-:|:-:|
|[![](https://papers.chon.group/JAAMAS/chonOS/pictures/rpi1.png) Raspberry Pi 1 Model B](https://sourceforge.net/projects/chonos/files/rc1/chonos-rc1-RPI-1-Model-B-2012.zip/download)|[![](https://papers.chon.group/JAAMAS/chonOS/pictures/rpi3.png) Raspberry Pi 3 Model B ](https://sourceforge.net/projects/chonos/files/rc1/chonos-rc1-RPI-3-Model-B.img.zip/download)|[![](https://papers.chon.group/JAAMAS/chonOS/pictures/rpizeroW.png) Raspberry Pi Zero W](https://sourceforge.net/projects/chonos/files/rc1/chonos-rc1-RPI-1-Model-B-2012.zip/download)|
|[![](https://papers.chon.group/JAAMAS/chonOS/pictures/bpim2.png) Banana Pi M2 Zero ](https://sourceforge.net/projects/chonos/files/rc1/chonos-rc1-BPI-M2-Zero.img.zip/download)|||


2) Burn a SD Card

    [![](https://papers.chon.group/JAAMAS/chonOS/pictures/001-BurningSDCard.png)](https://youtu.be/sBbAgfHaPb0)

    Tutorial: https://youtu.be/sBbAgfHaPb0


Other Single-board Computer? Try to execute the follow commands:

```console
echo "deb [trusted=yes] http://packages.chon.group/ chonos main" | sudo tee /etc/apt/sources.list.d/chonos.list
sudo apt update
sudo apt install chonos
```


## How to use?

TODO




## COPYRIGHT
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />The [_Cognitive Hardware on Networks Operating
System (chonOS)_](http://os.chon.group/) and is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. The licensor cannot revoke these freedoms as long as you follow the license terms:

* __Attribution__ — You must give __appropriate credit__ like below:

LAZARIN, Nilson Mori; PANTOJA, Carlos Eduardo; VITERBO, José. Towards a Toolkit for Teaching AI Supported by Robotic-agents: Proposal and First Impressions. In: WORKSHOP SOBRE EDUCAÇÃO EM COMPUTAÇÃO (WEI), 31. , 2023, João Pessoa/PB. Anais [...]. Porto Alegre: Sociedade Brasileira de Computação, 2023 . p. 20-29. ISSN 2595-6175. DOI: https://doi.org/10.5753/wei.2023.229753.


<details>
<summary> Bibtex citation format</summary>

```
@inproceedings{chonOS,
 author = {Nilson Lazarin and Carlos Pantoja and José Viterbo},
 title = { Towards a Toolkit for Teaching AI Supported by Robotic-agents: Proposal and First Impressions},
 booktitle = {Anais do XXXI Workshop sobre Educação em Computação},
 location = {João Pessoa/PB},
 year = {2023},
 issn = {2595-6175},
 pages = {20--29},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/wei.2023.229753},
 url = {https://sol.sbc.org.br/index.php/wei/article/view/24887}
}

```
</details>
