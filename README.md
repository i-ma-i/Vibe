## 仮想マシンの立ち上げ

[VirtualBoxのインストール](https://www.kagoya.jp/howto/it-glossary/server/virtualbox)

[Ubuntuのインストール](https://qiita.com/HirMtsd/items/225c20b77a7cd5194834)

1. Oracle VirtualBox をインストールする。
   1. VirtualBox Platform Packages をダウンロードする。
   2. VirtualBox Extension Pack をダウンロードする。
   3. VirtualBox Installer を起動する。
   4. VirtualBox Extension Pack を起動する。
2. 仮想マシンを立ち上げる。
   1. OSのイメージファイルをダウンロードする。
3. 必要なパッケージをインストールする。
   1. git
      ```
      sudo apt install git -y
      ```
   2. VSCode
      ```
      sudo snap install --classic code
      ```
   3. NodeJS + npm
      ```
      sudo apt install npm -y
      ```
4. Claude Code をインストールする。
```
npm install -g @anthropic-ai/claude-code
```
[Claude Code インストール時のトラブルシューティング](https://docs.anthropic.com/en/docs/claude-code/troubleshooting#linux-permission-issues)
