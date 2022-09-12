# ⚙ Surface

### Set Color :

```lua
surface.draw_set_color(float r, float g, float b, float a)
```

### Filled Rectangle :

```lua
surface.draw_filled_rectangle(int x0, int y0, int x1, int y1)
```

### Filled Rectangle Fade :

```lua
surface.draw_filled_rectangle_fade(int x0, int y0, int x1, int y1, uint32_t uAlpha0, uint32_t uAlpha1, bool bHorizontal)
```

### Outlined Rectangle :

```lua
surface.draw_outlined_rectange(int x0, int y0, int x1, int y1)
```

### Line :

```lua
surface.draw_line(int x0, int y0, int x1, int y1)
```

### Poly Line :

```lua
surface.draw_polyline(int* x, int* y, int nPoints)
```

### Set Text Font :

```lua
surface.draw_set_text_font(unsigned long hFont)
```

### Set Text Color :

```lua
surface.draw_set_text_color(float r, float g, float b, float a)
```

### Set Text Position :

```lua
surface.draw_set_text_position(int x, int y)
```

### Text :

```lua
surface.draw_render_text(const wchar_t* wszText, int nTextLength, int drawType)
```

### Set Text RGBA :

```lua
surface.draw_set_text_rgba(int nIndex, const unsigned char* rgba, int iWide, int iTall)
```

### Set Texture :

```lua
surface.draw_set_texture(int nIndex)
```

### Create New Texture Id :

```lua
surface.draw_create_new_texture_id(bool bProcedural)
```

### Create Font :

```lua
surface.draw_create_font()
```

### Set Font Glyph :

```lua
surface.draw_set_font_glyph_set(HFont hFont, const char* szWindowsFontName, int iTall, int iWeight, int iBlur, int nScanLines, int iFlags, int nRangeMin, int nRangeMax)
```

### Get Text Size :

```lua
surface.draw_get_text_size(HFont hFont, const wchar_t* wszText)
```

### Play Sound :

```lua
surface.play_sound(const char* szFileName)
```

### Outlined Circle :

```lua
surface.draw_outlined_circle(int x, int y, int iRadius, int nSegments)
```

### Textured Polygon :

```lua
surface.draw_textured_polygon(int n, Vertex_t* pVertice, bool bClipVertices)
```
