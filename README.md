# Argument-diagrammer
A lightweight, browser-based tool for creating argument diagrams. 
Arrange numbered statements, draw arrows to show inferential support, and group linked premises with brackets. Export finished diagrams as PNG or SVG for use in lecture slides, discussion handouts, other teaching materials, and student homework.

<img width="219" height="249" alt="diagram-12345" src="https://github.com/user-attachments/assets/4cfc4935-4cf8-4197-ab5c-a99ec9932d8f" />

## Getting Started

1. **Add statements.** The editor opens with a sample diagram, so click Clear all first for a blank canvas. Then enter statement numbers or letters (for example, 1-4; or A, B, C) and click **Add**. 
2. **Arrange statements.** Drag the numbered circles into position, typically placing premises above the conclusions they support.
3. **Connect statements.** Drag the connector dot beneath a circle onto the statement it supports to create an arrow.
4. **Bracket linked premises.** Select multiple statements using Shift+click or box selection, then click **Bracket**. Drag the bracket's connector onto the conclusion. If the conclusion is included in your selection, the connecting arrow is added automatically. 
5. **Export your diagram.** Click **Download PNG** or **Download SVG**. You can also use **Copy PNG** to paste a diagram directly into a slide or document.

## Features

### Diagram editing

- **Direct manipulation:** Drag statements, arrows, and brackets to build and rearrange arguments.
- **Linked premises:** Group statements that jointly support a conclusion using brackets.
- **Custom labels:** Double-click any statement circle to change its number or replace it with another label.
- **Arrow editing:** Use **Flip arrow** to reverse a connection or **Unarrow** to remove it.
- **Bracket editing:** Use **Unbracket** to separate linked premises into individual support arrows.
- **Multi-selection:** Select elements with Shift+click or drag a selection box.

### Layout and formatting

- **Auto-align:** Automatically arrange statements into evenly spaced rows, placing conclusions at the bottom. Select specific circles to align only those.
- **Align row:** Arrange selected statements along a common horizontal line.
- **Custom styling:** Change the color of statements, arrows, and brackets, and apply bold or dashed styles. Press Shift to select multiple elements. 
- **Fine positioning:** Use the arrow keys to nudge selected statements into place.

### Export and file management

- **PNG export:** Download diagrams as images or copy them directly to the clipboard.
- **SVG export:** Export resolution-independent vector diagrams for presentations and print materials.
- **Transparent backgrounds:** Remove the white background when exporting.
- **Automatic cropping:** Exports are trimmed to the diagram's contents.
- **Editable project files:** Save diagrams as `.json` files and reopen them for further editing.
- **Undo:** Reverse changes using Ctrl+Z (⌘Z on macOS).

The complete list of keyboard shortcuts is available under **Keys** in the sidebar.

## Saving Your Work

The editor does not automatically save diagrams between sessions. Closing or reloading the page will discard any unsaved changes.

To preserve an editable diagram:

1. Click **Save file** to download a `.json` project file.
2. Keep the file somewhere accessible.
3. Use **Open file** to restore the diagram and continue editing.

PNG and SVG exports are intended for presentation and distribution. Save a JSON project file if you plan to make further changes.

## Running Locally

Argument Diagrammer is a standalone HTML application with no installation or build process.

1. Download `index.html` from this repository.
2. Open the file in a modern web browser.
3. Start diagramming.

The application works offline.

## Privacy

All diagram editing and rendering take place entirely within your browser. Diagrams are not uploaded to a server, and no account is required.

Your work stays on your device unless you choose to export or share it.

## License

See [LICENSE](./LICENSE) for licensing information.

---

Created by **Dylan Teng**.
