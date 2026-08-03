<p align="center">
    <img src="/assets/icon-grid.png" width="500" height="437" alt="Icon grid" />
</p>
<h1 align="center">
    Custom Lucide Icons
</h1>

### About

Recently, I have been working on my personal network documentation and professional portfolio website, and I have been modernizing the aesthetics by replacing the aging Material Design Icons with [Lucide](https://lucide.dev) icons. In several circumstances I ran into situations where Lucide did not have the icon I wanted, so I decided to make my own versions trying to stick to the [Lucide design guidelines](https://lucide.dev/contribute/icon-design-guide). These icons are the result. Some of them are still a work-in-progress while others are finalized.

### Work-in-Progress Icons

The icons in the '/icons/work-in-progress' directory are not in their final form. This directory contains the working files I use to create the final icon. The `work-in-progress` directory contains the following files:

| File Name         | Description                                                                                |
| :---------------- | :----------------------------------------------------------------------------------------- |
| `*-inkscape.svg`  | The original source of the icon, created in Inkscape.                                      |
| `*-optimized.svg` | The file saved by Inkscape as an "optimized" SVG with all extra Inkscape metadata striped. |
| `*-studio.svg`    | The icon from Lucide Studio with "tidied" XML code.                                        |

### Finalized Icons

The icons in the `/icons/final` directory are finalized and ready for use in a project. The icons in this directory are duplicates of the `*-studio.svg` files with the proper class definition added to the `<svg />` XML tag. For example, the icon `house-shield` has the class definition `class="lucide lucide-house-shield-icon lucide-house-shield"`. This ensures when you use the icon in your project along with other Lucide icons you can reference it in the same way.