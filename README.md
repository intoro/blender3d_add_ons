Add ons for Blender 3d

git add *;
git commit -m "another add on";
git push -u origin master;

_______________________________________________________________________________________________
AllBlue-Blender-Tools

  A set of Blender Add-ons that can be useful here and there...

File Browser Search

  File Browser Search is a BlenderAdd-on that allows you to search for files in Blender File Browser (i.e. when linking/appending resources, opening folders, adding images or movies, opening *.blend files, etc.).

Add-ons Tools

  Add-on Tools allows you to decided which add-ons should be enabled according to *.blend file and not only by User Preferences.

Group Particles Tools

  Group Particles Tools enables a "hidden" functionality of particles systems in Blender which allows better control over particles displayed as objects group.

Mesh Sorting Tools

  Mesh Sorting Tools allows you to sort meshes in a more advanced way. It is quite useful when combined with particles or build/explode modifiers.

Animate Render Layers

  Animate Render Layers allows you to animate render layers using keyframes. It can be used to speed up renders or replace objects in a scene with for example shattered objects from another layer.
_______________________________________________________________________________________________
Joeboy/blender-addons

This is a place to keep my blender add-ons, so I don't lose them. They're
mostly quick hacks for my own benefit, but other people might find them
useful too.

So far, these are all for working with the VSE:

Sync Audio: For syncing external audio with your crappy camera audio.

VSE export: Export your audio mix to an Ardour session for more powerful audio mixing.

Mute strip modifiers: Mute / unmute all VSE strip modifiers. Useful if modifiers are slowing down video previewing.

Open strip source: Open a VSE strip's source audio/video in an external editor.
_______________________________________________________________________________________________
Blender Add-ons: 3DM Morph

Morphing images

Download

v0.1.5	3dm_morph.py
Install

Click on button Install from File... in "User Preference"
Or Copy 3dm_morph.py in folder "~/.config/blender/2.78/scripts/addons"

_______________________________________________________________________________________________

3DM Snow

Create snow on selected objects.

Download

v0.1.0	3dm_snow.py
Install

Click on button Install from File... in "User Preference"
Or Copy 3dm_snow.py in folder "~/.config/blender/2.78/scripts/addons"

_______________________________________________________________________________________________
  Transform
You Can - Copy / Paste / Paste Mirror, Transform object, vertex, edge and faces.

Download

v0.2.6	3dm_transform.py
Install

Click on button Install from File... in "User Preference"
Or Copy 3dm_transform.py in folder "~/.config/blender/2.78/scripts/addons"

_______________________________________________________________________________________________
BAddons
  About
The BAddons repository contains addons (i.e. script snippets meant to extend functionality) for the 3D software Blender.
These addons are free and open-source (GPL-licensed, in version 2+), see LICENSE for more information.

    Structure of the repository
  The repository is organized as follows:
  Main folder:
-general repository files (.gitignore, README's, LICENSE).
-a Pickle file, ADDONS_LIST.pkl, which contains a serialized representation of the repo's structure; it is used by the next file:
-a Python addon, matpi_addons_collection.py, which is intended to facilitate handling of others (dowloading, updating, deletion, etc.). See below.
-various folders, containing each a Python addon. See below for more information about each addon.

  Matpi's Addons Collection (Configurator)
The Addons Collection addon, sometimes refered to as addon master, has been written with the goal of providing to users a simplified way to manage addons of this repository within their own Blender configuration, f.ex. to keep them updated against latest released version.

Thus, a user taking advantage of this script only needs to download and install that one per hand, which will once enabled in Blender displays options to download and install others very easily and quickly.

Usage of this addon master is strongly recommended for a ultimate experience with BAddons items. Of course, downloading each addon separately is also possible.

Description of the addons

Name	Description	Current version
3DView_BorderLines_BMeshEdition -	Provides a way to highlight border lines (edges connected to exactly one face) of Blender meshes to help checking topology.	1.9
3DView_MeshStatistics -	Computes some information about current Blender mesh, i.e. volume, area, position of the center of mass.	1.0
3DView_SynchronizeViews -	Provides an option to lock viewpoint in a Blender 3D view region to the one of another view region. This addon is currently under heavy rewriting.	1.0
GameEngine_DecompileRuntime -	Re-extracts the original .blend file out of a runtime executable BlenderPlayer file; this i.e. proves that the "save as Game Engine Runtime" option is reversible.	1.0
GameEngine_LegacyStart - 	Re-enables the 2.73-deleted option of starting the BGE from any rendering mode by pressing the P-Key in the 3D view.	1.1
Node_LocationPanel -	Displays the exact position of a node in its 2D space; this is more of a demo addon, probably useless to most of the users.	1.1

_______________________________________________________________________________________________
Blender_add-ons

[English version]

Add-ons and python scripts made in my free time for the 3D software Blender.
Currently there are avaible under GPL v3: so there are completly free to use them as you want (and i'm very interested about what you can do with it . Returns will be highly appreciated).
If you enjoy them, please make a donation by buying my Lapineige's Tools, a compilation of them: http://cgcookiemarkets.com/blender/all-products/lapineiges-tool-add-ons-compilation/



[French version]

Add-ons et script python pour le logiciel 3D Blender, réalisés durant mon temps libre.
Actuellement ils sont tous disponibles sous licence GPL v3: vous êtes libre de les réutiliser comme vous le souhaitez (et je suis très intéressé par ce que vous pourrez faire avec . Les retours serons très appréciés).
Si vous appréciez ces outils, faites un don en achetant la compilation de ces outils, les Lapineige's Tools: http://cgcookiemarkets.com/blender/all-products/lapineiges-tool-add-ons-compilation/
_______________________________________________________________________________________________
Fire VR
Fire: JanusVR Importer and Exporter for Blender 3D

Fire is a Blender addon that exports the current scene to the JanusVR FireBoxHTML-format. It generates the XML description of the room automatically, exports the objects and materials and launches into JanusVR with just one click. It can also import scenes directly from your PC or websites, just give it a URL.

It optionally also supports instant publication over the IPFS network (no server needed!).

Requirements

JanusVR
Optional:

IPFS (only required for IPFS publication)
To use IPFS, it must be present in the PATH. When not using the IPFS gateway, you need to run the IPFS daemon locally ("ipfs daemon").
Documentation

https://firevr.readthedocs.io/en/latest/

Installation

Download this repository as .zip file: https://github.com/void4/FireVR/archive/master.zip
Blender -> User Preferences -> Addons -> Install from File -> Select the .zip, enable the addon
More detailed installation instructions can be found here: https://firevr.readthedocs.io/en/latest/installation.html

Usage

Create your scene
Blender -> 3D View -> Tool Shelf -> Misc -> Set your room and object attributes using the panel options
Blender -> 3D View -> Tool Shelf -> Misc -> Set the JanusVR and Export target directories
Click on Start JanusVR to export and launch your room in JanusVR
This addon was tested under Ubuntu/Linux and Windows. Your feedback is welcome!
_______________________________________________________________________________________________
Magic-UV

Features

"Magic UV" have features as follows.

Copy/Paste UV Coordinates
Copy/Paste UV Coordinates (by selection sequence)
Copy/Paste UV Coordinates (Among same objects)
Flip/Rotate UVs
Transfer UV
Manipulate UV with Bouding Box in UV Editor
Move UV from 3D View
Texture Projection
Pack UV (with same UV island packing)
Texture Lock
Mirror UV
World Scale UV
Unwrap Constraint
Preserve UV Aspect

_______________________________________________________________________________________________

ManuelbastioniLAB
The aim of ManuelbastioniLAB is to bring you a set of advanced tools to turn your Blender in a powerful laboratory for realistic humanoid characters creation.

This software is based on the 15 years experience gained during the realization of various 3d graphics projects and CG humans and collects new algorithms, prototypes and unpublished python scripts developed by Manuel Bastioni.

_______________________________________________________________________________________________
    Video Sequence Editor Add Ons
Video Sequence Editor Add Ons

This is my collection of Plugins for Blender3D's Video Sequence Editor. They aim to add feature which are common in other video editors to make blender the best open source video editor out there.

Transform (transform.py)

This script by kgeogeo & DoubleZ allows grabbing, scaling and rotating strips in the preview window.

Composite (composite.py)

Assists in the creation of video compositions with presets for keying, pixelizing and 3D animations.

Text (text.py)

Creates a scene with a text and allows simple editing in the sequencer.

Scene tools (sceentools.py)

Will in the future be availlable for handling and prerendering scene strips.

Record (record.py)

Will in the future be availlable to record audio in blender.
