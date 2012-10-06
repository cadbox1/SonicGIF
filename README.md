SonicGIF is a way to produce a near identical GIF from a sonic canvas animation for the 
purpose of backwards compatibility with older browsers.

It combines two projects Sonic, obviously, and jsgif which converts canvas graphics to gifs

Sonic by Padolsey: https://github.com/padolsey/Sonic

jsgif by Antimatter15: https://github.com/antimatter15/jsgif

To use SonicGIF you must:

-Include all the scripts from the Encoder folder on your page

-Start Sonic the way you usually would

-Add two extra properties to your sonic settings; convert:TRUE and background:"#fff"
    These tell SonicGIF that you want a gif and also the background colour of the GIF
    as GIF files do not support transparency.
    
-Finally as you would append Sonic to an element also append sonic.img

You can see all this happening in Example.html

The only limitation is the fps on gifs which by my count is about 10 but thats not too bad
Enjoy!