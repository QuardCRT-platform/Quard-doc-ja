<div style="text-align: right"><a href="../../en/latest/installation.html">🇺🇸 English</a> | <a href="../../zh-cn/latest/installation.html">🇨🇳 简体中文</a> | <a href="../../zh-tw/latest/installation.html">🇭🇰 繁體中文</a> | <a href="../../ja/latest/installation.html">🇯🇵 日本語</a></div>

# インストール

QuardCRTはクロスプラットフォームのターミナルエミュレータで、Windows、MacOS、Linuxをサポートしています。可能であれば、まずはネイティブプラットフォームの公式アプリケーションマーケットを通じてQuardCRTをインストールすることをお勧めします。

## アプリストア

QuardCRTは現在、以下のアプリストアで利用可能です。

- [![Microsoft Store](https://get.microsoft.com/images/ja%20dark.svg)](https://apps.microsoft.com/detail/quardCRT/9p6102k9qb3t?mode=direct)
- [Spark Store](https://www.spark-app.store/store/application/quardcrt)
- Deepin Store

将来、さらに多くのアプリストアが利用可能になります。

もちろん、自分のプラットフォームに応じて対応するインストールパッケージをダウンロードすることもできます。

## ダウンロード

### すべてのプラットフォーム

最新バージョンのQuardCRTをダウンロードしたい場合は、以下のリンクにアクセスしてください。

- [GitHub Releases](https://github.com/QQxiaoming/quardCRT/releases)
- [Gitee Releases](https://gitee.com/QQxiaoming/quardCRT/releases)
- [SourceForge](https://sourceforge.net/projects/quardcrt/files/)

プラットフォームに応じて対応するパッケージをダウンロードする必要があります。以下のパッケージを提供しています。

- Windows: 
    - `quardCRT_windows_Vxxx_x86_64_setup.exe`
    - `quardCRT_windows_Vxxx_x86_64_msvc_setup.exe`
- MacOS: 
    - `quardCRT_macos_Vxxx_x86_64.dmg`
    - `quardCRT_macos_Vxxx_arm64.dmg`
- Linux: 
    - `quardCRT_Linux_Vxxx_x86_64.AppImage`
    - `quardCRT_Linux_Vxxx_x86_64.deb`
- ソースコード: 
    - `quardCRT_Vxxx_source.tar.gz`
    - `quardCRT_Vxxx_source.zip`

### Windows

Windows を使用している場合は、`quardCRT_windows_Vxxx_x86_64_setup.exe` または `quardCRT_windows_Vxxx_x86_64_msvc_setup.exe` パッケージをダウンロードすることができます。`quardCRT_windows_Vxxx_x86_64_setup.exe` パッケージは MinGW でビルドされており、`quardCRT_windows_Vxxx_x86_64_msvc_setup.exe` パッケージは MSVC でビルドされています。必要に応じてパッケージを選択することができます。カスタムプラグインについて気にしない場合は、互換性が高い `quardCRT_windows_Vxxx_x86_64_setup.exe` パッケージを選択することができます。

#### インストール 

QuardCRT をインストールするには、パッケージをダブルクリックし、プロンプトに従ってインストールを完了します。

1. 言語を選択し、「OK」をクリックします。
2. 「次へ」をクリックします。
3. インストールディレクトリを選択し、「次へ」をクリックします。
4. デスクトップショートカットを作成するかどうかを選択し、「次へ」をクリックします。
5. 「インストール」をクリックします。
6. 「完了」をクリックします。

### MacOS

MacOSを使用している場合は、`quardCRT_macos_Vxxx_x86_64.dmg` または `quardCRT_macos_Vxxx_arm64.dmg` パッケージをダウンロードすることができます。`quardCRT_macos_Vxxx_x86_64.dmg` パッケージは x86_64 でビルドされており、`quardCRT_macos_Vxxx_arm64.dmg` パッケージは arm64 でビルドされています。Apple Silicon Mac を使用している場合は、`quardCRT_macos_Vxxx_arm64.dmg` パッケージを選択する必要があります。

#### インストール

QuardCRT をインストールするには、パッケージをダブルクリックし、プロンプトに従ってインストールを完了します。

1. `quardCRT` アイコンをダブルクリックします。
2. `quardCRT` アイコンを `Applications` フォルダにドラッグします。

> 注記: 現在リリースしているプリビルドバイナリパッケージは、Apple によって公式に署名されていないため、初めてプログラムを開くと、プログラムが未確認の開発者から来ているという警告メッセージが表示されることがあります。プログラムを信頼している場合は、ターミナルを開いて `xattr -cr /Applications/quardCRT.app` を実行して、quardCRT.app の quarantine 属性を削除する必要があります。しかし、プログラムを信頼していない場合は、実行しないでください。自分でプログラムをソースコンパイルすることもできます。

### Linux

Linux を使用している場合は、`quardCRT_Linux_Vxxx_x86_64.AppImage` または `quardCRT_Linux_Vxxx_x86_64.deb` パッケージをダウンロードすることができます。`quardCRT_Linux_Vxxx_x86_64.AppImage` パッケージは AppImage パッケージであり、`quardCRT_Linux_Vxxx_x86_64.deb` パッケージは deb パッケージです。必要に応じてパッケージを選択することができます。

#### Install

- AppImage

AppImage パッケージはポータブルパッケージであり、インストールせずに直接実行することができます。実行可能にするには、次のコマンドを実行することができます。

```bash
chmod +x quardCRT_Linux_Vxxx_x86_64.AppImage
```

- deb

deb パッケージをダブルクリックし、プロンプトに従ってインストールを完了します。

1. パッケージをダブルクリックします。
2. `インストール` をクリックします。
3. パスワードを入力し、`認証` をクリックします。
4. `閉じる` をクリックします。

または、次のコマンドを実行して deb パッケージをインストールすることができます。

```bash
sudo dpkg -i quardCRT_Linux_Vxxx_x86_64.deb
```
