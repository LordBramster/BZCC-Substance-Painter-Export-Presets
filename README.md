<img width=60% src="assets/bzcc.png"> <img width=30% src="assets/substance-painter.png">

<br>

# PBR SpecGloss Export Setting Presets for BZCC
You won't have to make these two presets from scratch! Just use the templates provided below to setup PBR SpecGloss properties for Battlezone Combat Commander.

<br>

## Getting Started

Download the necessary preset files. 
You can also browse or download the specific presets as you wish in the [Releases](https://github.com/LordBramster/BZCC-Substance-Painter-Export-Presets/releases) tab.

Or, you can download them from here:
- [Height-Normals Preset](BZCC-Height-Normals-Export.spexp)
- [SpecGloss Maps Preset](BZCC-PBR-SpecGloss-Export.spexp)


_These files were made by me, however the information to make and save these presets were given by various BZCC Community Members. Those had prior knowledge with Substance Painter, so all credit is due to them. Thank you to those for sharing the knowledge that has gotten us all this far._

<br>

## Installation and Setup

### Steam Version
- Navigate to the following directory: ```C:\Users\...\Documents\Adobe\Adobe Substance 3D Painter\assets\export-presets```
- Paste **BOTH** `.spexp` files here.
- That's it! They are ready for use.

### Non-Steam Version
- Navigate to the following directory: ```C:\Users\...\Documents\Allegorithmic\Substance Painter\shelf\export-presets```
- Paste **BOTH** `.spexp` files here.
- That's it! They are ready for use.


<br>

## Demonstration
_(This was demonstrated using the Steam Version)_

There are two major instances when you'd export from Substance Painter (in this context):
- Generating a usable Normal Map from the Height Map data. This can be used to bake.
- Generating final texture maps, with BZCC PBR SpecGloss properties configured.

### Getting There
We need to find where to export textures. Conveniently it is called "Export Textures" on the top Toolbar.
- **Select** Export Textures _(ctrl+shift+e)_
<img width=40% src="assets/demo1.JPG">

### Bake Normal Map(s)
Once you have created your Height map, you will want to convert it to a Normal Map:
<img width=40% src="assets/demo2b.JPG">
- **Select** the field called "Output Template".
- **Choose** `BZCC-Height-Normals-Export`
- When you're ready, **select** "Export".
<img width=50% src="assets/demo2.JPG">

### Bake General Texture Maps (Diffuse, Normal, SpecGloss, Emissive)
After you are done texturing, and want to export these textures for Battlezone Combat Commander:
- **Select** the field called "Output Template".
- **Choose** `BZCC-PBR-SpecGloss-Export`
- When you're ready, **select** "Export".
<img width=50% src="assets/demo3.JPG">
