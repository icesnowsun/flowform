# FlowForm

**Beautiful flowcharts from a simple form — no code, no dragging.**
Write each step, pick a shape, choose what it connects to. FlowForm lays it out automatically and exports crisp PNG / SVG.

**填表即可生成漂亮的流程图。** 界面支持中文 / English 一键切换。

🔗 **Try it:** https://icesnowsun.github.io/flowform/

## Features

- **Form-based editing** – one card per step: text, shape, and “Connect to…”
- **Bulk add** – one step per line, auto-connected; lines ending with `?` become decisions
- **Auto layout** – layered layout with crossing reduction; decision branches split left/right; links back to earlier steps become side loops
- **6 shapes** – Start, End, Process, Decision, Input/Output, Subprocess
- **8 themes** – Fresh, Midnight, Morandi, Mono, Sunset (gradient), Ocean, Blueprint, Candy
- **Vertical / horizontal** direction, **curved / elbow** edges
- **Export** 3× PNG or vector SVG (drop straight into slides, Figma, docs)
- **Share link** – the whole chart is encoded in the URL
- **中文 / English** UI toggle
- Autosaves in your browser · works offline · nothing is uploaded

## How to use

1. Click **+ Process / + Decision …** to add steps
2. Type the text, then **+ Connect to…** to pick the next step. Label decision branches “Yes / No”
3. Switch theme, direction and edge style — the preview updates live
4. **Export PNG** or **SVG**

Or pick an example from **Start from a template…** (Scientific method, Journal peer review, Systematic review / PRISMA).

## Run locally / deploy

Just open `index.html` in a browser.

To host your own copy: fork this repo → **Settings → Pages** → Source **Deploy from a branch**, branch `main`, folder `/ (root)`.

## Customize

Everything lives in `index.html`. To add a theme, copy an entry in the `THEMES` object and change the colors; add its name to `I18N.en` / `I18N.zh` as `th_<key>`.

---

## 中文说明

- 左侧每张卡片是一个步骤：填文字、选形状、点“+ 连接到…”指定下一步
- 判断节点添加两条连线并标注“是 / 否”；连回前面的步骤会自动画成回环
- “批量添加”：每行一个步骤，以 `?` / `？` 结尾识别为判断
- 8 套主题、纵向 / 横向、曲线 / 直角，导出 3× PNG 或 SVG
- 右上角“中 / EN”切换界面语言

## License

[MIT](LICENSE)
