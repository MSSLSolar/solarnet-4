---
layout: page
title: "Instructions"
description: "Get Ready!!!"
header-img: "img/Tsuru_wiki.svg"
---

# Installation of SolarSoftware (ssw)

Most of the software that will be used in the hands-on session will be using the
[solarsoft](http://www.lmsal.com/solarsoft/) library and [IDL](http://www.exelisvis.com/IntelliEarthSolutions/GeospatialProducts/IDL.aspx). Please, make sure you have them installed properly in 
your laptop. In case you don't have an IDL license, we will provide a network license
for the duration of the summer school and workshop.

To install solarsoft you should get an installation script from [this form](http://www.lmsal.com/solarsoft/ssw_install.html). Make sure
to select the following packages:

-   SDO/AIA and HMI
-   Hinode/EIS
-   Orbital Observatories/IRIS
-   Virtual Observatories/VSO

Once you download the form follow the "what do I do next?" link in the result page.

If you are using Linux or Mac OS you then could create a *ssw* file to run IDL
with solarsoft from the bash terminal. Follow the instructions in [this blogpost](http://dpshelio.github.io/blog/2015/10/08/GetBash.html)
and change the variables defined and the `SSW_INSTR` accordingly (using the list
of instruments above).
You can also
[download this two files](https://gist.github.com/dpshelio/0b01261c31a7a4de21ea2f8a6eb8c4f9)
which are the ones used by the backup virtual machine.

If you are a OS X user you will need to install [XQuartz](http://www.xquartz.org/).

# Installation of other software

## Paraview

Paraview is is an open-source, multi-platform data analysis and visualisation
application. This will be used to visualise 3D magnetic field extrapolations.
Follow the [download instructions](http://www.paraview.org/download/) to install it in your machine. If you are
using Linux you can also get it by using the package-manager of your distribution
(e.g., dnf, apt-get, ...).

## ...


# During the workshop

## IDL Licenses.

The instructions on how to access the IDL license will be provided in the
workshop.

## Data

We are going to work with a lot of data, you should downloaded it before the
workshop starts to avoid delays due to the network. The data needed is available
in [the material section](/material/).


# If everything fails...

[Don't Panic](https://en.wikipedia.org/wiki/Phrases_from_The_Hitchhiker's_Guide_to_the_Galaxy#Don.27t_Panic).
We have prepared a virtual machine with all the software used so you can follow all the programme.
First you will need to download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
Download [solarnet4 virtualmachine](http://www.mssl.ucl.ac.uk/missions/corpita/solarnet4/data/SOLARNET_fedora.ova) (10GiB). Once The VirtualBox is installed and the virtual machine
instance downloaded, open VirtualBox and select `Import appliance` from the `File` menu. 
Select the file downloaded previously `SOLARNET_fedora.ova` and click `next` and `import`.

If everything goes well you should have a new virtual machine in the menu which
provides you with a Linux Fedora 24 system. This includes: IDL 8.5, Paraview and
some of the data to be used during the school. After starting the virtual
machine, to run `solarsoft`, you will have just to open a terminal and write
`ssw`. It will prompt you asking for the password for the licence which will be
provided during the workshop.

<br><br><br>

*Image source: [Orizuru](https://upload.wikimedia.org/wikipedia/commons/2/2f/Tsuru_wiki.svg) - <img width="60" src="http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg">*
