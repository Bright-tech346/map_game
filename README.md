# 點亮地圖 · Map Light-Up Games

Two browser geography games. Type a place name and it lights up on the map.

| Game | Regions | Modes |
|---|---|---|
| [點亮中國](china/) | 34 provincial-level divisions | Free play · A → B route · A → B → C route with a waypoint |
| [點亮日本](japan/) | 47 prefectures | Free play · A → B route · Guess-the-prefecture from its neighbours · 🔍 hint lens |

Each game is a single self-contained `index.html` with no build step and no network requests. Open it in any browser, or serve the folder with GitHub Pages.

## Input

- **China:** simplified or traditional Chinese, pinyin, or one-character abbreviations (e.g. 湖北 / 鄂 / hubei)
- **Japan:** Japanese kanji, simplified or traditional Chinese, hiragana/katakana, or romaji (e.g. 大阪 / おおさか / osaka)

## Play online with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.
4. After a minute the games are live at `https://<your-username>.github.io/<repo-name>/`.

## Map data

- China boundaries come from the map data bundled with [Apache ECharts](https://github.com/apache/echarts) 4.9 (Apache-2.0).
- Japan boundaries come from [jpn-atlas](https://github.com/biskwikman/jpn-atlas) (BSD-3-Clause), based on the Geospatial Information Authority of Japan's *Global Map Japan*.
