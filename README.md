PPM reader/writer
===================
OpenGL should be activated.
```
int texWidth, texHeight;
vector<PackedPixel> pixData;
ppmRead("smile.ppm", texWidth, texHeight, pixData);
```
----------
and to write
```
writePpmScreenshot(g_width, g_height, "out.ppm");
```