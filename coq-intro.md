---
marp: true
# backgroundColor: orange
class: invert
---

# Coq 入門

---
<!-- paginate: true -->
# Coq とは

- 証明が正しいことを保証してくれる装置。

---
# インストール
Coq 8.8.0 まではインストーラが用意されている。

- **新しさより簡単さ重視**：[レポジトリ](https://github.com/coq/coq/releases/tag/V8.8.0)からインストーラを入手

- **最新版を入れたい**：[Coq/SSReflect/MathCompの設定](https://staff.aist.go.jp/reynald.affeldt/ssrcoq/install.html#org35ada1b)を参考にコンソール上でインストール
  - `sudo apt get install`でなく`sudo apt install`
  - WSLでは「新しいライブラリの設定が要るかも」の箇所で`sudo apt install -y libgmp-dev`が必要だった([参考](https://www.aise.ics.saitama-u.ac.jp/~gotoh/Coq-SSReflect-MathCompOnUbuntu2004.html))

---
# エディタ

- **VScode+VSCoq**がおすすめ。VScode上で拡張機能(`Ctrl+Shift+X`)から「vscoq」と検索すれば出てくる。
  - Windowsの人はWSL上で動かせるように**Remote - WSL**も入れよう。


- インストーラから入れた場合は**CoqIDE**も利用できる(がVSCoqの方が便利)

