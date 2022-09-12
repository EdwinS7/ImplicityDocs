# ⚙ Render

### Line :

```lua
render.line(int xStart, int yStart, int xEnd, int yEnd, float r, float g, float b, float a, float flThickness)
```

### Rectangle :

```lua
render.rectangle(int xStart, int yStart, int iWidth, int iHeight, float r, float g, float b, float a)
```

### Rectangle Filled :

```lua
render.rectangle_filled(int xStart, int yStart, int iWidth, int iHeight, float r, float g, float b, float a)
```

### Rectangle Gradient :

```lua
render.rectangle_gradient(int xStart, int yStart, int iWidth, int iHeight,float r1,float g1,float b1,float a1, float r2, float g2, float b2, float a2)
```

### Text :

```lua
render.text(string szText, int xStart, int yStart, float r, float g, float b, float a, int iFontIndex, int uFlags, int rOutline, int gOutline, int bOutline, int aOutline)

--Custom text
render.custom_text(HFont uFont, std::string szText, int xStart, int yStart, float r, float g, float b, float a)
```

### World To Screen :

```lua
render.world_to_screen(float xPos,float yPos,float zPos)
```

### Create Font :

```lua
render.create_custom_font(std::string szFontName, int iSize, int iWidth, int uFlags)
```

### Get Text Size :

```lua
render.custom_font_get_text_size(HFont uFont, std::string szText)
```

#### Flags :

```
Font Flags :
0 = shadow
1 = outline
```

#### Font Indexes :

```
Render Font Index :
0 = verdana
1 = smallest pixel
2 = smallest pixel small
3 = player name esp
4 = verdana big
5 = console clean shadow
23 = thin and medium font
30 = big and bold
31 = medium bold with shadow
```
