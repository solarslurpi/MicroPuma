# What the Heck?
I am exploring how good of a microscope can be made using mostly 3D parts.  Heck, it works for my Prusa Printer....Oh and, of course learning for the sheer exhilaration of it all.
# Welcome
Who needs Virtual Reality when there is a whole world of tiny creatures dashing around a soil sample.  I wanted a microscope that I could evolve over time to self adjust focus, detect movement and track the little critters as they dash about,..., all digitally captured.  I ran across [the PUMA project](https://www.optarc.co.uk/products/puma-products/) by Dr. Paul J. Tadross and decided to try putting together the PUMA DIY microscope.  A person with expertese in microscopy has the passion to open source a DIY microscope and also make a small business out of it. On to answer the burning questions -  _how hard can it be to make a Puma microscope?_  I guess _as hard as I make it_. So off I go!
# Resources
- [Unboxing the PUMA Foundation Scope YouTube video](https://www.youtube.com/watch?v=EfecD0UGLDQ)
- [Intro to the PUMA microscope YouTube video](https://www.youtube.com/watch?v=7UbkrZyNgpo)
- [Assembling the PUMA Foundation Scope YouTube video](https://www.youtube.com/watch?v=C-2vRsHi46c)
- [Puma Github site](https://github.com/TadPath/PUMA).  
    - [The CAD files](https://github.com/TadPath/PUMA/tree/main/FreeCAD) are in FreeCAD's file format. 
    - [Bill of Materials](https://github.com/TadPath/PUMA/tree/main/Bill_of_Materials)  
    - [Puma 3D printing guide](https://github.com/TadPath/PUMA/blob/943e9fdd85a75a0f66877ff655aecd6222ea8cb0/3D_Printing/PUMA_3D_Printing_Guide.pdf).  The guide walks through how to use FreeCAD to generate the STL files.  The information helped to get into FreeCAD's "mesh design workspace", however, I was having a challenge saving to STL. I found [export method 1 from the FreeCAD wiki](https://wiki.freecadweb.org/Export_to_STL_or_OBJ) gave me the info I needed.  The guide lists all the STL files.  
# First Build
This build consists of:
- building the stand.
- building the Foundational scope.

As I dove in, I immediately started drowning in the trees without a way of seeing the forest.  
- Pages upon pages of CAD parts.  
- A CAD software package I'd never heard of (my bad I guess).  
- Component sources are places I don't normally shop (Alibaba for example).  M6, M4, M3, M2 threaded bolts, nuts, washers with specific tops...um, my hardware store might have had one of the bolts....
# Building the Stand
I started by extracting the STL files from FreeCAD.  I then pulled the STLs into Fusion 360.  Let's stop here for a second so I can explain why I introduce Fusion 360 when I can just shove the STL files on my Prusa mk3s printer.  I did it because I was completely confused and clueless how to put the stand together.  My cluelessness is slightly better, so I am hoping someone will take pity on this effort and guide me where I made mistakes.  What does Fusion 360 bring in?  A way to break out the building and BoM in the most efficient way.  By that I mean animated exploded views and Drawings with a Parts list.

With Fusion 360 in mind, besides the challenge of knowing what STL files to use out of the ocean of available files, STLs are difficult to model with.  The least of it being STL files are unitless.  The hardest challenge is converting an STL into a Fusion 360 body.
![The Puma stand](images/PUMAstandDrawing.jpg)

[PDF file](https://github.com/solarslurpi/PumaBuddy/blob/f52439c8b1b514a02d744e74469203ae59990232/stand/Puma%20Stand%20Drawing%20v1.pdf)

I couldn't find any manual or video that walks through putting the stage together.  Here is my attempt.  I broke building the stand into three parts.
## 1-Base
### Exploded View
<iframe width="560" height="315" src="https://www.youtube.com/embed/iJgOUpIeiLo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Build the Stand
The challenges with building the stand 