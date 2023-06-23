# コンピューターグラフィックス

## Github Pages
- [TOP](https://ryomanden.github.io/CG_class/)
- [第1回　レポート](https://ryomanden.github.io/CG_class/report1.html)
- [第2回　レポート](https://ryomanden.github.io/CG_class/report2.html)

## Library
### Three.js
- OrbitControls
  - [ICS Media](https://ics.media/tutorial-three/camera_orbitcontrols/)
  - [Documentation](https://threejs.org/docs/#examples/en/controls/OrbitControls)
- lil-gui
  - [Documentation](https://lil-gui.georgealways.com/)
### Other
- tailwindcss
  - [Documentation](https://tailwindcss.com/docs/installation)
- daisyUI
  - [Documentation](https://daisyui.com/)

## How to develop
### tailwind and daisyUI
1. tailwindのインストール\
```bash
npm install
```
2. スタイルを書き始める前に以下を実行。
```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
3. tailwindのクラスをまとめる時は`/src/input.css`に記述していく。
```css
.index-wrap {
    @apply h-screen w-screen flex justify-center flex-col
}
```