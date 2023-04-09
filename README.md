
# Canvas-zoom extension showcase

This repository is a demonstration of all the [canvas-zoom](https://github.com/richrobber2/canvas-zoom) extension capabilities for [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

1. [Context menu](#context-menu) 
2. [Moving canvas](#moving-canvas) 
   - [Move via shift](#move-via-shift) 
   - [Move via hotkey](#move-via-hotkey) 
3. [Zooming canvas](#zooming-canvas) 
   - [Zoom via keys](#zoom-via-keys) 
   - [Fit to screen](#fit-to-screen) 
4. [Controls](#controls)
   - [Reset zoom](#reset-zoom) 
   - [Toggle overlap elements](#toggle-overlap-elements)
   - [Undo last action](#undo-last-action)  
   - [Adjust brush size](#adjust-brush-size) 
   - [Fast open color panel](#fast-open-color-panel) 
   - [Open color panel under mouse](#open-color-panel-under-mouse) 
5. [Mask transparency](#mask-transparency)
   - [Canvas transparency](#canvas-transparency) 
   - [Brush transparency](#brush-transparency) 

## For Beginners
Use the context menu to customize the keys or to switch the [movement mode](#move-via-hotkey) .

Important functions you should know: **[Moving canvas](#moving-canvas)** , **[Zooming canvas](#zooming-canvas)**, **[Undo](#undo-last-action)**, **[Reset zoom](#reset-zoom)**, **[Overlap elements](#toggle-overlap-elements)**  and **[Fit to screen](#fit-to-screen)**


## Default hotkeys:

**Shift + click or wheel (hold)** - Move canvas

**Shift + "+" or Shift + "-"** - Scale canvas ( numpad keys also work )

**Shift + wheel** - Scale canvas

**Ctr + wheel** - Change brush size

**F (hold)** - Move canvas (Need to switch move mode)

**S** - Zoom in on the canvas so that it fits into the screen

**R** - Reset Zoom.

**Q** - Open/Close color panel

**T** - Open color panel right above the mouse. The mouse should be in the image area

**O** - Overlap all elements and back

**Ctr-Z** - Undo last action

**C** - Toggle mask transparency mode ( Works only in Inpaint )

**V** - Toggle brush transparency mode  ( Works only in Inpaint )

## Context menu <a name="context-menu"></a>

This application has a context menu that is called by **Right mouse button** , you must click in the image field in **Inpaint, Sketch, Inpaint Sketch**

In the context menu you can:
1) Change the hotkeys as you like
2) Change the movement mode
3) Adjust the degree of transparency

https://user-images.githubusercontent.com/22278673/230694818-6cb0e66f-b30d-4923-82f1-f434193d67f4.mp4


## Moving canvas <a name="moving-canvas"></a>


### Move via shift <a name="move-via-shift"></a>
You can move canvas with **shift + wheel (hold)** 


https://user-images.githubusercontent.com/22278673/230692150-f6e6b1b1-a8fc-4def-b0fe-570b8dd4f5d5.mp4

<br />

### Move via hotkey <a name="move-via-hotkey"></a>
If you are annoyed by the traces when you move on shift+wheel, 
then 

Toggle the move mode and move with the **F** key

https://user-images.githubusercontent.com/22278673/230693840-2796973a-68eb-425e-8b1f-741d67046604.mp4

<br />

## Zooming canvas <a name="zooming-canvas"></a>

You can zoom canvas with **shift + wheel** 

https://user-images.githubusercontent.com/22278673/230693887-1019b30d-a8a4-4aee-8d38-92327007d59f.mp4

<br />

### Zoom via keys <a name="zoom-via-keys"></a> 

If you don't have a mouse or don't want to zoom with the wheel, you can also use **Shift + "+"** and **Shift + "-"** (Numpad also works) to zoom in and out

https://user-images.githubusercontent.com/22278673/230693976-18680edb-332a-45dd-8119-0804494f6937.mp4

<br />

### Fit to screen <a name="fit-to-screen"></a>
You can immediately zoom in on the image so that it fits into your screen on **S**.

https://user-images.githubusercontent.com/22278673/230694112-d4633df7-88ab-45c7-a950-d300b6071388.mp4


## Controls <a name="controls"></a> 

Keys that allow you to control the state of canvas

### Reset zoom <a name="reset-zoom"></a> 

You can quickly reset the zoom on the **R** key

https://user-images.githubusercontent.com/22278673/230694270-55ef6aa9-cd82-4e1a-a553-7f01cfb2c439.mp4

### Toggle overlap elements <a name="toggle-overlap-elements"></a> 

You can enable overlapping of elements, on the key **O** so that nothing disturbs you

https://user-images.githubusercontent.com/22278673/230694310-6f856cc5-5fdc-4a68-8edb-c6f78c9840ba.mp4

### Undo last action <a name="undo-last-action"></a>

You can quickly undo the last action on **Ctr+Z**

https://user-images.githubusercontent.com/22278673/230695848-f77e790f-3169-4ff2-8403-8ce2a1d00685.mp4

### Adjust brush size <a name="adjust-brush-size"></a> 

You can quickly adjust the brush size with **Ctr+wheel**

https://user-images.githubusercontent.com/22278673/230694713-8990ffe4-c650-4542-bffb-8b5bc269f434.mp4

### Fast open color panel <a name="fast-open-color-panel"></a> 

You can quickly on **Q** open the color bar and select a color or dropper

https://user-images.githubusercontent.com/22278673/230694370-776ea55e-02ab-43f4-9d2a-d6047724bdeb.mp4

### Open color panel under mouse <a name="open-color-panel-under-mouse"></a> 

If you get too close to the image or if you don't want to reach the default location of the color box you can open it right next to the mouse. Press the **T** key 

https://user-images.githubusercontent.com/22278673/230694442-4048601b-b2b7-4a29-ae41-f34c1dc09772.mp4


## Mask transparency <a name="mask-transparency"></a> 

Transparency mode only works in **Inpaint** , transparency mode is not made 100% can be a problem. 

You can adjust the mask and brush transparency in the **context menu**.

### Canvas transparency <a name="canvas-transparency"></a> 

On the **C** hotkey you can turn on the transparency mode of the mask.

https://user-images.githubusercontent.com/22278673/230694599-9b4f2585-1c8c-4162-a9da-8a1a9ccd0475.mp4

### Brush transparency <a name="brush-transparency"></a> 

On the **V** hotkey you can turn on the transparency mode of the brush.

https://user-images.githubusercontent.com/22278673/230694636-8acb8104-8f64-4860-b394-0fad0006cb12.mp4



