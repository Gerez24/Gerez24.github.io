---
title: "The interface"
weight: 2
---
The Graphical User Interface, or GUI for short, is the main workspace for AnimeEffects and consists of the various parts that can be seen in the image bellow. <br>
Our interface is written using the Qt framework, which gives it a distinct look you may have seen in other applications.<br>
{{< picture "english/ae_gui_extended.png" "english/ae_gui_extended.png" "ae_menu_bar">}}<br>
Let's go through all the parts one by one.

### The Menu Bar
A classic, the menu bar is a very important part of many application because it contains various useful commands, let's give them a small summary! And don't worry, we'll touch on important options later.<br>

[//]: # (File menu)

{{< block "grid-2" >}}
{{< tip >}}
- File
    <details>
    <summary>New Project</summary>

    - Creates a new project based on the parameters given by the user.

    </details>
    <details>
    <summary>Open Project</summary>

    - Allows you to select an existing project file to open.

    </details>
    <details>
    <summary>Open Recent</summary>

    - Lets you to select from a dropdown menu a recently opened file.
    
    </details>
    <details>
    <summary>Save Project</summary>

    - Saves your current project (Ctrl - S).
    
    </details>
    <details>
    <summary>Save Project As</summary>

    - Allows you to name and select where to save your current project
    
    </details>
    <details>
    <summary>Export As</summary>

    - Lets you to export to various file formats through a dropdown menu.
    
    </details>
    <details>
    <summary>Close Project</summary>

    - Closes the current project.
    
    </details>
{{< /tip >}}
{{< picture "english/file_menu.png" "english/file_menu.png" "ae_file_menu">}}
{{< /block>}}

[//]: # (Edit menu)

{{< block "grid-2" >}}
{{< tip >}}

- Edit
    <details>
    <summary>Undo</summary>

    - Undoes the latest action performed (Ctrl - Z).

    </details>
    <details>
    <summary>Redo</summary>

    - Performs the latest undone action (Shift - Ctrl - Z)

    </details>

{{< /tip >}}
{{< picture "english/edit_menu.png" "english/edit_menu.png" "ae_edit_menu">}}
{{< /block >}}

[//]: # (Project menu)

{{< block "grid-2" >}}
{{< tip >}}

- Project
    <details>
    <summary>Set canvas size</summary>

    - Allows you to resize your canvas to an specified width and height measured in pixels.

    </details>
    <details>
    <summary>Set maximum frame count</summary>

    - Lets you change how many frames the animation should have.

    </details>
    <details>
    <summary>Set animation loop</summary>

    - Allows you to select wether the animation loops or not.

    </details>
    <details>
    <summary>Set frames per second</summary>

    - Lets you change the playback speed of your animation.

    </details>

{{< /tip >}}
{{< picture "english/project_menu.png" "english/project_menu.png" "ae_project_menu">}}
{{< /block >}}

[//]: # (Window menu)

{{< block "grid-2" >}}
{{< tip >}}

- Window
    <details>
    <summary>Resource Window</summary>

    - This will show you a very special window that we'll discuss later.

    </details>

{{< /tip >}}
{{< picture "english/window_menu.png" "english/window_menu.png" "ae_window_menu">}}
{{< /block >}}


[//]: # (Options menu)

{{< block "grid-2" >}}
{{< tip >}}

- Options
    <details>
    <summary>General Settings</summary>

    - This will open a menu that will allow you to customize your expirience with AnimeEffects, from
    the language, to your theme, autosaves, etc.

    </details>
    <details>
    <summary>Mouse Settings</summary>

    - This will allow you to change how the mouse interacts with the canvas and the timeline.

    </details>
    <details>
    <summary>Key bindings</summary>

    - This allow you to change your keybinds.

    </details>

{{< /tip >}}
{{< picture "english/options_menu.png" "english/options_menu.png" "ae_option_menu">}}
{{< /block >}}

[//]: # (Help menu)

{{< block "grid-2" >}}
{{< tip >}}

- Help
    <details>
    <summary>About AnimeEffects</summary>

    - This will give you a window with information about the current version of AnimeEffects, you can get more info by clicking the "Show details" button.

    </details>
    <details>
    <summary>Check for updates</summary>

    - This let's you check if you have the latest and greatest version of AnimeEffects, you can also download updates or visit the release site from here!

    </details>

{{< /tip >}}
{{< picture "english/help_menu.png" "english/help_menu.png" "ae_help_menu">}}
{{< /block >}}



### The Tool Dock
A dock filled with useful tools to bring your animations to life! <br>
{{<tip "warning">}}
We make reference to nodes in this part of the documentation, and while we will discuss them in detail later, for now you should know that this is how we refer to images and folders.<br>
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/showmesh.png) Shows the mesh from the currently selected node. <br>
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/cutimages.png) Don't draw images outside the canvas. <br>
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/rotateac.png) Rotate the canvas by 15° counterclockwise. <br>
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/resetrot.png) Reset the canvas rotation. <br>
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/rotatecw.png) Rotate the canvas by 15° clockwise. <br>
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/cursor.png) Panning tool, it lets you scroll through the canvas by using your mouse.
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/srt.png) Transforming tool, selecting it gives you the option to move and rotate images, it also gives you the option to:<br>
- ![:inline](../../../images/ui-elements/move.png) Select an animation key type to forcefully create through movement with this tool.
- ![:inline](../../../images/ui-elements/transcent.png) Move the center of the image.
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/bone.png) Bone tool, selecting it gives you access to various tools to create, destroy and manipulate bones, these tools are:<br>
- ![:inline](../../../images/ui-elements/plus.png) Allows you to add new bones to a node.
- ![:inline](../../../images/ui-elements/minus.png) Allows you to remove bones from a node.
- ![:inline](../../../images/ui-elements/move.png) Allows you to move bone joints.
- ![:inline](../../../images/ui-elements/bind.png) Allows you to bind a bone to a node.
- ![:inline](../../../images/ui-elements/influence.png) Allows you to adjust the influence a bone exerts on a node by dragging it.
- ![:inline](../../../images/ui-elements/pencil.png) Allows you to adjust the influence a bone exerts on a node by painting it.
- ![:inline](../../../images/ui-elements/eraser.png) Allows you to erase a previously defined influence.
{{</tip>}}

{{<tip>}}
![:inline](../../../images/ui-elements/pose.png) Posing tool, selecting this allows you to move the bones you have created, manipulating the mesh of the node according to the bone influence.
{{</tip>}}

#### Under construction 🏗️

### The Animation Dock

### The Property Dock

### The Main View

### The Console

