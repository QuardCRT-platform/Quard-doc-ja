.. raw:: html

   <div style="text-align: right"><a href="../../en/latest/index.html">🇺🇸 English</a> | <a href="../../zh-cn/latest/index.html">🇨🇳 简体中文</a> | <a href="../../zh-tw/latest/index.html">🇭🇰 繁體中文</a> | <a href="../../ja/latest/index.html">🇯🇵 日本語</a></div>

quardCRT
----------------------------------

.. image:: https://img.shields.io/github/actions/workflow/status/qqxiaoming/quardCRT/windows.yml?branch=main&logo=windows
   :target: https://github.com/QQxiaoming/quardCRT/actions/workflows/windows.yml
   :alt: Windows ci
.. image:: https://img.shields.io/github/actions/workflow/status/qqxiaoming/quardCRT/linux.yml?branch=main&logo=linux
   :target: https://github.com/QQxiaoming/quardCRT/actions/workflows/linux.yml
   :alt: Linux ci
.. image:: https://img.shields.io/github/actions/workflow/status/qqxiaoming/quardCRT/macos.yml?branch=main&logo=apple
   :target: https://github.com/QQxiaoming/quardCRT/actions/workflows/macos.yml
   :alt: Macos ci
.. image:: https://img.shields.io/codefactor/grade/github/qqxiaoming/quardCRT.svg?logo=codefactor
   :target: https://www.codefactor.io/repository/github/qqxiaoming/quardCRT
   :alt: CodeFactor
.. image:: https://readthedocs.org/projects/quardcrt/badge/?version=latest
   :target: https://quardcrt.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status
.. image:: https://img.shields.io/github/license/qqxiaoming/quardCRT.svg?colorB=f48041&logo=gnu
   :target: https://github.com/QQxiaoming/quardCRT
   :alt: License
.. image:: https://img.shields.io/github/tag/QQxiaoming/quardCRT.svg?logo=git
   :target: https://github.com/QQxiaoming/quardCRT/releases
   :alt: GitHub tag (latest SemVer)
.. image:: https://img.shields.io/github/downloads/QQxiaoming/quardCRT/total.svg?logo=pinboard
   :target: https://github.com/QQxiaoming/quardCRT/releases
   :alt: GitHub All Releases
.. image:: https://img.shields.io/github/stars/QQxiaoming/quardCRT.svg?logo=github
   :target: https://github.com/QQxiaoming/quardCRT
   :alt: GitHub stars
.. image:: https://img.shields.io/github/forks/QQxiaoming/quardCRT.svg?logo=github
   :target: https://github.com/QQxiaoming/quardCRT
   :alt: GitHub forks
.. image:: https://gitee.com/QQxiaoming/quardCRT/badge/star.svg?theme=dark
   :target: https://gitee.com/QQxiaoming/quardCRT
   :alt: Gitee stars
.. image:: https://gitee.com/QQxiaoming/quardCRT/badge/fork.svg?theme=dark
   :target: https://gitee.com/QQxiaoming/quardCRT
   :alt: Gitee forks

QuardCRTは、複数のバックエンドプロトコルをサポートし、依存関係なしにプラットフォーム間で使用でき、Windows/Linux/Macで完全に一貫したユーザーエクスペリエンスを提供する端末エミュレーションおよびリモートデスクトップソフトウェアです。多タブや履歴管理などの伝統的な端末ソフトウェア機能をサポートし、一部のユニークな詳細機能もサポートしています。

.. list-table:: 
   :widths: 33 33 33
   :header-rows: 0

   * - .. image:: ./img/windows.png
          :align: center
          :height: 160px
     - .. image:: ./img/macos.png
          :align: center
          :height: 160px
     - .. image:: ./img/linux.png
          :align: center
          :height: 160px
   * - Windows
     - MacOS
     - Linux

----------------------------------
特徴
----------------------------------

- **クロスプラットフォーム**: Windows、MacOS、Linux
- **複数のプロトコル**: SSH、Telnet、SFTP、Serial、VNC、LocalShell、RawSocket、NamedPipe
- **複数のセッション**: マルチタブ、マルチウィンドウ、マルチモニター、フローティングウィンドウ
- **複数の言語**: 英語、簡体字中国語、繁体字中国語、日本語、韓国語、スペイン語、フランス語、ロシア語
- **複数のテーマ**: ライト、ダーク
- **セッション履歴管理**: セッション履歴管理、セッション履歴検索
- **セッション管理**: セッション管理、セッションのインポートとエクスポート
- **HEX表示**: HEX表示
- **スクリプト**: スクリプトの記録、スクリプトの再生
- **端末のカスタマイズ**: 端末のフォント、色、サイズ、カーソル、スクロールバック、背景など

----------------------------------
特別機能
----------------------------------

- タブのフローティングプレビュー
- フローティングウィンドウサポート、タブのドラッグアンドドロップでフローティングウィンドウ
- SSH2セッションワンクリックでSFTPファイル転送ウィンドウを開く
- 作業ディレクトリブックマーク
- 自動送信
- ターミナルの背景画像はgifアニメーションとビデオをサポート
- ターミナルキーワードハイライトマッチング
- 選択したテキストの翻訳機能
- パスマッチングとワンクリック直接
- 作業パス直接
- Windowsローカルターミナルの強化（Tabキーで完全なコマンドを選択など）

----------------------------------
プラグイン
----------------------------------

quardCRTはV0.4.0からプラグインをサポートし、プラグインはQtプラグインの形式で提供され、動的ライブラリの形式でロードされます。プラグイン開発情報についての詳細は、プラグインオープンプラットフォーム `platform <https://github.com/QuardCRT-platform>`_ を参照してください。このプラットフォームは、プラグイン開発のためのテンプレートリポジトリと関連する例を提供します。現在、プラグイン機能はまだ早期開発段階にあります。良いアイデアや提案がある場合は、 `GitHub <https://github.com/QQxiaoming/quardCRT>`_ または `Gitee <https://gitee.com/QQxiaoming/quardCRT>`_ でissuesやディスカッションを提出してください。

.. toctree::
   :maxdepth: 3
   :caption: 目次:

   インストール<installation.md>
   使い方<usage.md>
   設定<configuration.md>
   よくある質問<faq.md>
   貢献<contributing.md>
   更新履歴<changelog.md>
   ライセンス<license.md>
   ロードマップ<roadmap.md>
   謝辞<acknowledgements.md>
