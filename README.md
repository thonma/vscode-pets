# VS Code Pets プルート追加版

- [VS Code Pets プルート追加版](#vs-code-pets-プルート追加版)
  - [開発環境構築](#開発環境構築)
    - [Aseprite __(有料)__](#aseprite-有料)
    - [犬の素材 __(有料)__](#犬の素材-有料)
    - [VSCode](#vscode)
    - [ソースコード](#ソースコード)
  - [ビルド](#ビルド)
  - [備考](#備考)
- [VS Code Pets](#vs-code-pets)
  - [Installation](#installation)
  - [Using VS Code Pets](#using-vs-code-pets)
  - [Translation](#translation)
  - [Credits](#credits)
  - [Thank you](#thank-you)

## 開発環境構築

<details>

<summary>gif を作る必要がある場合</summary>

### Aseprite __(有料)__
- Win / Mac
    - https://www.aseprite.org/
    - 2024/10/10 時点で __$19.99 USD = 2,980円__
- Steam
    - https://store.steampowered.com/app/431730/Aseprite/?l=japanese
    - 2024/10/10 時点で __2,050円__
- 備考
    - 機能的にはすべて同じ
    - 試用版はファイル出力ができない
    - __8フレームの gif が作れれば別のソフトでも OK__

### 犬の素材 __(有料)__
- NVPH Studio
    - https://nvph-studio.itch.io/dog-animation-4-different-dogs
    - 2024/10/10 時点で __$1.00 USD = 150円__
- 備考
    - 6つ の gif が 1つ のスプライトになっているのでファイルを分割する必要がある
    - __gif をゼロから作るなら不要__

</details>

### VSCode
- VSCode拡張をインストール
    - ESLint
    - Prettier

### ソースコード
```bash
$ npm i
```

## ビルド
```bash
# VSIX を作成
$ npx vsce package
```

## 備考
- 猫の画像は使えません
    - 理由は `media\README.md` に書いてあります

---
---
---
---

<!-- ここから下は変更不可!! -->
<!-- ここから下は変更不可!! -->
<!-- ここから下は変更不可!! -->
<!-- ここから下は変更不可!! -->
<!-- ここから下は変更不可!! -->
<!-- ここから下は変更不可!! -->
<!-- ここから下は変更不可!! -->
<!-- ここから下は変更不可!! -->

<div align='center'>

# VS Code Pets

![icon](https://github.com/tonybaloney/vscode-pets/raw/main/icon.png)
</div>    

<p align="center">
    Puts a small, bored cat, an enthusiastic dog, a feisty snake, a rubber duck, or Clippy 📎 in your code editor to boost productivity.
    <br>
    <br>
    <a href="https://github.com/tonybaloney/vscode-pets/issues/new?assignees=&labels=feature&template=bug_report.md&title=">Report a Bug</a>
    ·
    <a href="https://github.com/tonybaloney/vscode-pets/issues/new?assignees=&labels=feature&template=feature_request.md&title=">Request feature</a>
</p>

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/tonybaloney.vscode-pets?color=blue&logo=visual-studio)](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets&WT.mc_id=python-17801-anthonyshaw)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/tonybaloney.vscode-pets?logo=visualstudio)](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets&WT.mc_id=python-17801-anthonyshaw)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/tonybaloney.vscode-pets?logo=visualstudio)](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets&WT.mc_id=python-17801-anthonyshaw)

![screenshot](https://github.com/tonybaloney/vscode-pets/raw/main/docs/source/_static/screenshot.gif)

## Installation

Install this extension from the [VS Code marketplace](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets&WT.mc_id=python-17801-anthonyshaw).

OR

With VS Code open, search for `vscode-pets` in the extension panel (`Ctrl+Shift+X` on Windows/Linux or `Cmd(⌘)+Shift+X` on MacOS) and click install.

OR

With VS Code open, launch VS Code Quick Open (`Ctrl+P` on Windows/Linux or `Cmd(⌘)+P` on MacOS), paste the following command, and press enter.

`ext install tonybaloney.vscode-pets`

## Using VS Code Pets

Congrats on installing joy! Enjoy interacting with these cute pixelated pets. Read below to get a full understanding of this extension. Not convinced? Watch our extension spotlight on [Visual Studio Code](https://www.youtube.com/watch?v=aE6Ifj_KstI).

After installing, open the command palette with `Ctrl+Shift+P` on Windows/Linux or `Cmd(⌘)+Shift+P` on MacOS.  

Run the "Start pet coding session" command (`vscode-pets.start`) to see a cat in VS Code:

![Default view](https://github.com/tonybaloney/vscode-pets/raw/main/docs/source/_static/pet-in-default-explorer.png)

[Now checkout the documentation to see what else is possible!](https://tonybaloney.github.io/vscode-pets)

## Translation

Visit the [Crowdin Project](https://crowdin.com/project/vscode-pets) in case you'd like to help with the translations. It will be synced automatically to the repository. You can also request a new language in the [Discussions](https://crowdin.com/project/vscode-pets/discussions) section.

## Credits

The cat animations were designed by [seethingswarm](https://seethingswarm.itch.io/catset). The dog media assets for this extension were designed by [NVPH Studio](https://nvph-studio.itch.io/dog-animation-4-different-dogs). 

The forest theme was designed by [edermunizz](https://edermunizz.itch.io/free-pixel-art-forest). The castle assets were created using artwork by [GuttyKreum](https://guttykreum.itch.io/gothic-castle-game-assets).

[Marc Duiker](https://twitter.com/marcduiker) created the Clippy, Rocky, Zappy, rubber duck, snake, cockatiel, Ferris the crab, and Mod the dotnet bot media assets.

[Elthen](https://twitter.com/pixelthen) created the fox media assets.

[Karen Rustad Tölva](https://www.aldeka.net) designed the original concept of Ferris the crab.

[Kevin Huang](https://github.com/kevin2huang) created the Akita inu media assets.

The turtle animations were designed by enkeefe using [Pixelart](https://www.pixilart.com/draw).

The horse animations were adapted by [Chris Kent](https://github.com/thechriskent) from assets by [Onfe](https://onfe.itch.io/horse-sprite-with-rider-asset-pack). 

[Kennet Shin](https://github.com/WoofWoof0) created the snail media assets.

## Thank you

Thanks to all the [contributors](https://github.com/tonybaloney/vscode-pets/graphs/contributors) to this project.
