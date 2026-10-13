# AI Applications Mind Map

An interactive 3D mind map of an eight-unit course on artificial intelligence applications. Units rise in a spiral, one per week. Each unit branches into its key ideas. A gold thread traces the semester capstone project, and dashed lines show ideas that return in later units.

## Use it

- Drag to rotate. Scroll or pinch to zoom.
- Click any sphere, label, or unit chip to fly to it.
- The side panel shows each unit's summary, key ideas with definitions and examples, and connections to other units.

## Host it on GitHub Pages

1. Put `index.html` in the root of a repository.
2. In the repository, open **Settings > Pages**.
3. Under **Source**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. The page appears at `https://cynthialmcginnis.github.io/arin-320-mindmap/` within a few minutes.

## Edit the content

All course content lives in the `UNITS`, `CAPSTONE`, `LINKS`, and `COURSE` objects near the top of the script in `index.html`. Change the text there and the map and panel update automatically.

## Built with

- [three.js](https://threejs.org/) r128 for the 3D scene
- Google Fonts: Bricolage Grotesque, Atkinson Hyperlegible, JetBrains Mono
