# Unity - UI
![Unity - UI](https://docs.unity3d.com/Packages/com.unity.ugui@1.0/manual/images/GUI_Canvas_Screenspace_Overlay.png)

This repository is used for a project at Holberton School to learn about how UI works in Unity.

## Learning Objectives
- What is the Canvas
- What is screen space vs world space
- How to use the Rect Tool
- What are anchors and how to use them
- How to display and update information in the UI
- What is a coroutine
- How to create a menu
- How to use Unity’s UI Interaction Components
- What the alpha value of a color is
- How to set and change material colors with scripts
- What are common accessibility concepts to consider

## Tasks
### 0. Scoreboard
We’ll be building off the last project to add UI elements.

Clone your `holbertonschool-0x02-unity-scripting` repo into a new repo called `holbertonschool-0x03-unity-ui`. Like the previous project, this project should be inside its own repo, not within a subdirectory.

Create a new Canvas GameObject:
- Render Mode: `Screen Space - Overlay`
- Pixel Perfect: Yes
- UI Scale Mode: `Scale With Screen Size`

Inside the Canvas, create a new UI Image GameObject and name it `ScoreBG`. Anchor it to the top right of the game window using Anchor Presets.
- Pos X: `-80`
- Pos Y: `-40`
- Width: `100`
- Height: `30`
- Image color: `#000000`
- Alpha: `200`

Create a new Text GameObject named `ScoreText`. Make `ScoreText` a child of `ScoreBG`. Anchor `ScoreText` to the middle of `ScoreBG` using Anchor Presets.
- Width: `100`
- Height: `30`
- Text: Score: `0`
- Font size: `18`
- Alignment: `Center + Middle`
- Horizontal Overflow: `Overflow`
- Font color: `#FFFFFF`

![Score](https://s3.eu-west-3.amazonaws.com/hbtn.intranet.project.files/holbertonschool-cs-unity/422/0.png)
