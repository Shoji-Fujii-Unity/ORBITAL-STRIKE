# ORBITAL STRIKE - Star Domain Assault

A single-file Three.js 3D space flight shooter.
Three.js 製の単一ファイル 3D 宇宙シューティングゲームです。

## Supported Languages / 対応言語 / 支援语言

- Japanese: 日本語
- English: English
- Chinese: 中文 / 简体中文

This README contains instructions in Japanese, English, and Simplified Chinese.

---

## File Structure / ファイル構成 / 文件结构

- index.html

The game is contained entirely inside one HTML file.

---

## How to Run / 起動方法 / 运行方法

### Japanese

1. index.html をブラウザで開きます。
2. モバイルの場合は端末を横画面にしてください。
3. タイトル画面で言語を選択できます。
4. START からステージ選択へ進めます。
5. Sound On / Off でサウンドを切り替えられます。

推奨ブラウザ:
- Google Chrome
- Microsoft Edge
- Safari
- Firefox

PC の場合はキーボード操作、モバイルの場合はタッチ操作でプレイできます。

### English

1. Open index.html in a web browser.
2. On mobile devices, rotate your device to landscape mode.
3. Select your language on the title screen.
4. Press START to open the stage selection menu.
5. Use Sound On / Off to enable or disable audio.

Recommended browsers:
- Google Chrome
- Microsoft Edge
- Safari
- Firefox

PC players can use keyboard controls. Mobile players can use touch controls.

### 简体中文

1. 在浏览器中打开 index.html。
2. 手机设备请将设备横屏。
3. 在标题画面可以选择语言。
4. 按下 START 进入关卡选择。
5. Sound On / Off 可以开启或关闭声音。

推荐浏览器：
- Google Chrome
- Microsoft Edge
- Safari
- Firefox

电脑玩家可以使用键盘操作，手机玩家可以使用触屏操作。

---

## Game Overview / 遊び方 / 玩法

You pilot a small space fighter through multiple space stages.

Destroy enemies, defeat stage bosses, increase your score, and clear all stages.

The game includes:
- Space flight shooting
- Multiple enemy types
- Multiple stages
- Multiple bosses
- Local save data
- Sound toggle
- Multilingual UI
- Touch controls for mobile
- Landscape orientation requirement

---

## Controls / 操作方法 / 控制方法

### PC / 英語 / 简体中文

- WASD or arrow keys: move
- Space: fire
- B: bomb
- P or Escape: pause

### Mobile / モバイル / 手机

- Left stick: move your fighter
- FIRE button: shoot
- BOMB button: use bomb
- Pause button is displayed during play

Important:
- The game is designed for landscape mode.
- Portrait mode will show a rotate-device warning.

---

## Sound / サウンド / 声音

Audio can be toggled from:
- Title screen
- Pause menu

When enabled, sound effects will play.
When disabled, the game can be played silently.

Note:
On some browsers, audio starts only after the first user interaction.

---

## Languages / 言語切替 / 语言切换

The game supports the following languages:

- 日本語
- English
- 中文

Language can be changed from the title screen.
The selected language is saved in browser local storage.

---

## Save Data / セーブデータ / 存档数据

Progress and high scores are saved locally in your browser using localStorage.

Saved data may include:
- Selected language
- Sound setting
- Unlocked stages
- Stage high scores

To reset all data, clear the browser storage for this page or use private mode.

Note:
Saving is per browser and per device.
Different browsers or devices do not share the same save data.

---

## Technical Details / 技術情報 / 技术信息

- Built with Three.js
- No build process required
- No package manager required
- Single HTML file
- Uses CDN for Three.js:
  https://cdn.jsdelivr.net/npm/three@0.160.0/build/three.min.js

Because the Three.js library is loaded from a CDN, an internet connection is required unless you modify the file to use a local copy.

---

## Browser Notes / ブラウザの注意 / 浏览器注意事项

If the game does not start:

1. Use a recent browser.
2. Enable JavaScript.
3. Allow WebGL.
4. Make sure your device can rotate to landscape.
5. If loading fails, check your network connection.
6. Try another browser if WebGL is not supported.

For better performance, close other browser tabs and programs.

---

## Privacy Note / プライバシー / 隐私说明

The game does not send game data to a server.

Game data is stored locally in the browser.
Language selection and sound settings are also saved locally.

---

## Game Elements / ゲーム内容 / 游戏内容

The game contains:

- Many enemy types
- Many stages
- Multiple bosses
- Bomb special attack
- Player health and bomb gauge
- Score and local high scores
- Stage unlock system
- Pause system
- Landscape-optimized mobile controls

---

## Troubleshooting / トラブルシューティング / 故障排除

### Japanese

画面が横表示にならない:
- 端末の自動回転設定を確認してください。
- ブラウザの画面回転ロックを解除してください。

音が鳴らない:
- Sound On を確認してください。
- ブラウザタブの音量設定を確認してください。
- ページ上で一度タップまたはクリックしてください。

起動しない:
- JavaScript を有効にしてください。
- WebGL 対応ブラウザを使用してください。
- ネットワーク接続を確認してください。

保存データが消えない:
- ブラウザのサイトデータを削除してください。
- シークレットモードで開いてください。

### English

Landscape warning appears:
- Enable device rotation.
- Disable browser screen orientation lock.

No sound:
- Confirm Sound On is enabled.
- Check browser tab volume.
- Interact with the page once by tapping or clicking.

Game does not start:
- Enable JavaScript.
- Use a WebGL-capable browser.
- Check your network connection.

Saved data cannot be reset:
- Clear site data for this page.
- Open the game in private mode.

### 简体中文

不横屏:
- 请开启设备自动旋转。
- 请解除浏览器方向锁定。

没有声音:
- 请确认 Sound On。
- 请检查浏览器标签页音量。
- 请先在页面上点击或触摸一次。

无法启动:
- 请启用 JavaScript。
- 请使用支持 WebGL 的浏览器。
- 请检查网络连接。

存档无法重置:
- 请删除该页面的浏览器数据。
- 请在隐私模式打开。

---

## Notes

This README is intentionally written without embedded code blocks inside the markdown text, so it can be copied directly into README.md.

If you need a shorter README, this file can be reduced to only the supported-language instructions.