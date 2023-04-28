# Entry 4
##### 04/13/23


#### Introduction
After weeks of learning our tool we are now starting our freedom project. In this blog entery I will talk about where I'm at in my project and how I'm adding my tool into my project.

#### Process
For my freedom project I want to make a platformer game. Before even being able to do this I have to make a map so that the character can have somewhere to move. I think creating the map was one of the hard things to do because it required using another app that I've never used before. When doing the melon js tutorial that teaches you how to make a game everything seemed a lot easier because well melon was giving you everything, the files, the code and etc. Therefore, when using the Tiled app (where the map is being created) it was a lot easier to understand.
I first had to find tilesets. I didn't want to copy the exact same format of the games that were being shown, therefore, I downloaded a variety of tilesets that were sort of similar and I was going to mix it up. I thougt it was going to take a lot longer to make but it did not. After I finished making my map I struggled to import it into my ide. In the tutorial one of the important things we had to do in order for the map to show up was:

{name: "Map1"               type:"tmx"        src: "img/Map1.tmx" }

Which is exactly what I did, however, the map was still not showing up. After a long time of looking for what was wrong the issue was that I also needed to insert the image for the tileset. I then added:

{name:"Terrain1"            type: "image"     src: "img/Terrain1.png"}
{name:"Terrain2"            type: "image"     src: "img/Terrain2.png"}

and my map had finally showed up on the ide!


### EDP/Skills
I am currently on the creating part of the engineering design process. As I finish making my map my next step is to make add a character for my game. A skill that I have learned while working on my project is collaboration. When I was struggle to add my map onto my ide. My classmate who sits next to me is also doing melonjs and she had already created her game. Therefore, when I asked if I could see what she did in order to add her map onto her ide she showed me and helped me do the same with mine. Although it did not work at first she helped me. 




[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)