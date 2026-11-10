# Awesome MCP AI

AI エージェント向けの Model Context Protocol (MCP) リポジトリのキュレーションリストです。

[English README](README.md)

**掲載基準**

- ★ 100 以上のスター
- 直近 3 か月以内に push があること(2026-07-31 以降の push)
- MCP に実際に関連していること(サーバー、クライアント、SDK、ゲートウェイ、MCP ネイティブなツール)
- 例外(新しい分野やニッチな分野。スター基準を下げるが、3 か月以内の push は必須):
  - [ArtCraft エコシステム](#artcraft-エコシステム例外-100-未満): スター数不問
  - [CAE・工学シミュレーション](#cae工学シミュレーション): ★ 10 以上
  - [計測・計測機器](#計測計測機器): ★ 1 以上
  - [コンプライアンス・GRC・ISMS](#コンプライアンスgrcisms): ★ 10 以上
  - [Entra ID・ID管理・エンドポイント](#entra-idid管理エンドポイント): ★ 10 以上

スナップショット日: 2026-10-31(GitHub 検索 API のデータによる)。
注: 「push」はいずれかのブランチへの最新の push を指し、最新コミットのほぼ代用になります。

⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。last commit バッジは最新コミット日をリアルタイム表示します(shields.io)。リリース日バッジは定期更新タスクで追加されます。

## 目次

- [SDK・フレームワーク・学習](#sdkフレームワーク学習)
- [Awesome リスト・ディレクトリ](#awesome-リストディレクトリ)
- [コーディング・開発者ツール](#コーディング開発者ツール)
- [ブラウザ・Web・スクレイピング](#ブラウザwebスクレイピング)
- [画像・動画・音声の操作](#画像動画音声の操作)
  - [画像・デザイン](#画像デザイン)
  - [動画](#動画)
  - [音声・サウンド](#音声サウンド)
  - [オールインワン・クリエイティブスタジオ](#オールインワンクリエイティブスタジオ)
  - [ArtCraft エコシステム(例外: ★100 未満)](#artcraft-エコシステム例外-100-未満)
- [3D・CAD・ゲームエンジン・シミュレーション](#3dcadゲームエンジンシミュレーション)
  - [3D・Blender](#3dblender)
  - [CAD・3D プリント](#cad3d-プリント)
  - [ゲームエンジン](#ゲームエンジン)
- [CAE・工学シミュレーション](#cae工学シミュレーション)
- [計測・計測機器](#計測計測機器)
  - [計測機器制御・試験装置](#計測機器制御試験装置)
  - [ロジックアナライザ・組込みデバッグ](#ロジックアナライザ組込みデバッグ)
  - [LabVIEW](#labview)
  - [データ収集・センサ・産業用プロトコル](#データ収集センサ産業用プロトコル)
- [ノート・ナレッジベース](#ノートナレッジベース)
  - [Obsidian・Markdown Vault](#obsidianmarkdown-vault)
  - [Notion](#notion)
  - [Zotero・Logseq・Joplin・Apple Notes](#zoterologseqjoplinapple-notes)
- [Microsoft 365](#microsoft-365)
  - [Graph・管理](#graph管理)
  - [Teams・Outlook・カレンダー](#teamsoutlookカレンダー)
  - [Excel・Office 文書](#exceloffice-文書)
  - [OneDrive・SharePoint・Dataverse](#onedrivesharepointdataverse)
- [セキュリティ](#セキュリティ)
  - [SOC・SIEM・脅威インテリジェンス](#socsiem脅威インテリジェンス)
  - [OSINT](#osint)
  - [攻撃的セキュリティ・脆弱性スキャン](#攻撃的セキュリティ脆弱性スキャン)
  - [リバースエンジニアリング・マルウェア解析](#リバースエンジニアリングマルウェア解析)
  - [MCP・エージェントセキュリティ](#mcpエージェントセキュリティ)
  - [コンプライアンス・GRC・ISMS](#コンプライアンスgrcisms)
  - [Entra ID・ID管理・エンドポイント](#entra-idid管理エンドポイント)
- [ノーコードデータベース・データベース管理](#ノーコードデータベースデータベース管理)
  - [ノーコードデータベース(NocoDB 型)](#ノーコードデータベースnocodb-型)
  - [SQL クライアント・スキーマ・API ジェネレータ](#sql-クライアントスキーマapi-ジェネレータ)
  - [データベース別 MCP サーバー](#データベース別-mcp-サーバー)
  - [監視・DBA・ガバナンス](#監視dbaガバナンス)
- [データベース・検索・RAG](#データベース検索rag)
- [メモリ・コンテキスト](#メモリコンテキスト)
- [エージェント基盤・ゲートウェイ・クライアント](#エージェント基盤ゲートウェイクライアント)
- [クラウド・DevOps](#クラウドdevops)
- [生産性・ナレッジ](#生産性ナレッジ)
- [分野別アプリ](#分野別アプリ)
- [貢献方法](#貢献方法)
- [shvyac の awesome リスト](#shvyac-の-awesome-リスト)

## SDK・フレームワーク・学習

- [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/modelcontextprotocol/python-sdk?style=flat) - MCP サーバー/クライアント向けの公式 Python SDK。
- [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/modelcontextprotocol/typescript-sdk?style=flat) - MCP サーバー/クライアント向けの公式 TypeScript SDK。
- [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) ![GitHub stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft/mcp-for-beginners?style=flat) - .NET・Java・TypeScript・Rust・Python のサンプルを備えたオープンソースの MCP カリキュラム。
- [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) ![GitHub stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mcp-use/mcp-use?style=flat) - MCP アプリと MCP サーバーのためのフルスタック MCP フレームワーク。
- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) ![GitHub stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mastra-ai/mastra?style=flat) - MCP に対応した AI エージェント向け TypeScript フレームワーク。

## Awesome リスト・ディレクトリ

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/punkpeye/awesome-mcp-servers?style=flat) - 最大規模の MCP サーバー集。
- [yzfly/Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) ![GitHub stars](https://img.shields.io/github/stars/yzfly/Awesome-MCP-ZH?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/yzfly/Awesome-MCP-ZH?style=flat) - 中国語の MCP リソース・サーバー・クライアント集。
- [punkpeye/awesome-remote-mcp-servers](https://github.com/punkpeye/awesome-remote-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-remote-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/punkpeye/awesome-remote-mcp-servers?style=flat) - リモート MCP サーバー集。
- [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/jaw9c/awesome-remote-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/jaw9c/awesome-remote-mcp-servers?style=flat) - もう一つのリモート MCP サーバーリスト。
- [YuzeHao2023/Awesome-MCP-Servers](https://github.com/YuzeHao2023/Awesome-MCP-Servers) ![GitHub stars](https://img.shields.io/github/stars/YuzeHao2023/Awesome-MCP-Servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/YuzeHao2023/Awesome-MCP-Servers?style=flat) - 厳選された MCP サーバーのリスト。
- [TensorBlock/awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/TensorBlock/awesome-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/TensorBlock/awesome-mcp-servers?style=flat) - 網羅的な MCP サーバーコレクション。
- [MobinX/awesome-mcp-list](https://github.com/MobinX/awesome-mcp-list) ![GitHub stars](https://img.shields.io/github/stars/MobinX/awesome-mcp-list?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MobinX/awesome-mcp-list?style=flat) - 簡潔な MCP サーバーリスト。
- [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/soxoj/awesome-osint-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/soxoj/awesome-osint-mcp-servers?style=flat) - OSINT 向け MCP サーバー集。
- [punkpeye/awesome-mcp-devtools](https://github.com/punkpeye/awesome-mcp-devtools) ![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-devtools?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/punkpeye/awesome-mcp-devtools?style=flat) - MCP サーバー開発向けの開発ツール・SDK・テストユーティリティ集。
- [BlockRunAI/awesome-finance-mcp](https://github.com/BlockRunAI/awesome-finance-mcp) ![GitHub stars](https://img.shields.io/github/stars/BlockRunAI/awesome-finance-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/BlockRunAI/awesome-finance-mcp?style=flat) - 金融エージェント向けの MCP サーバー集。
- [e2b-dev/awesome-mcp-gateways](https://github.com/e2b-dev/awesome-mcp-gateways) ![GitHub stars](https://img.shields.io/github/stars/e2b-dev/awesome-mcp-gateways?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/e2b-dev/awesome-mcp-gateways?style=flat) - MCP ゲートウェイ集。
- [mcpHQ/awesome-mcp-servers](https://github.com/mcpHQ/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/mcpHQ/awesome-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mcpHQ/awesome-mcp-servers?style=flat) - カテゴリ別の MCP サーバーカタログ。
- [SciSharp/Awesome-DotNET-MCP](https://github.com/SciSharp/Awesome-DotNET-MCP) ![GitHub stars](https://img.shields.io/github/stars/SciSharp/Awesome-DotNET-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/SciSharp/Awesome-DotNET-MCP?style=flat) - .NET 向け MCP リソース集。
- [AlexMili/Awesome-MCP](https://github.com/AlexMili/Awesome-MCP) ![GitHub stars](https://img.shields.io/github/stars/AlexMili/Awesome-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/AlexMili/Awesome-MCP?style=flat) - MCP 全般のリソース集。
- [ever-works/awesome-mcp-servers](https://github.com/ever-works/awesome-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/ever-works/awesome-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ever-works/awesome-mcp-servers?style=flat) - 厳選された MCP サーバーとツール。

## コーディング・開発者ツール

- [upstash/context7](https://github.com/upstash/context7) ![GitHub stars](https://img.shields.io/github/stars/upstash/context7?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/upstash/context7?style=flat) - AI エージェントに最新のドキュメントを提供。
- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) ![GitHub stars](https://img.shields.io/github/stars/ChromeDevTools/chrome-devtools-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ChromeDevTools/chrome-devtools-mcp?style=flat) - コーディングエージェント向けの Chrome DevTools。
- [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) ![GitHub stars](https://img.shields.io/github/stars/DeusData/codebase-memory-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/DeusData/codebase-memory-mcp?style=flat) - エージェント向けのローカルコードインテリジェンスグラフ。
- [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) ![GitHub stars](https://img.shields.io/github/stars/DayuanJiang/next-ai-draw-io?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/DayuanJiang/next-ai-draw-io?style=flat) - AI で draw.io 図を作成・編集。MCP サーバー付き。
- [github/github-mcp-server](https://github.com/github/github-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/github/github-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/github/github-mcp-server?style=flat) - GitHub 公式の MCP サーバー。
- [mksglu/context-mode](https://github.com/mksglu/context-mode) ![GitHub stars](https://img.shields.io/github/stars/mksglu/context-mode?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mksglu/context-mode?style=flat) - コーディングエージェント向けのコンテキストウィンドウ最適化。
- [oraios/serena](https://github.com/oraios/serena) ![GitHub stars](https://img.shields.io/github/stars/oraios/serena?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/oraios/serena?style=flat) - コーディングエージェント向けのセマンティック検索・編集ツールキット。
- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) ![GitHub stars](https://img.shields.io/github/stars/czlonkowski/n8n-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/czlonkowski/n8n-mcp?style=flat) - n8n ワークフローを構築するための MCP。
- [MinishLab/semble](https://github.com/MinishLab/semble) ![GitHub stars](https://img.shields.io/github/stars/MinishLab/semble?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MinishLab/semble?style=flat) - エージェント向けの高速コード検索。
- [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) ![GitHub stars](https://img.shields.io/github/stars/vitali87/code-graph-rag?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/vitali87/code-graph-rag?style=flat) - モノレポ向けのグラフ RAG。
- [duty1g/x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/duty1g/x64dbg-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/duty1g/x64dbg-mcp-server?style=flat) - x64dbg デバッガ用の MCP プラグイン。
- [aoci-spec/aoci-code](https://github.com/aoci-spec/aoci-code) ![GitHub stars](https://img.shields.io/github/stars/aoci-spec/aoci-code?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/aoci-spec/aoci-code?style=flat) - エージェント向けの Git 管理されたコードベース/スキーママップ。
- [jkudish/jev-mcp](https://github.com/jkudish/jev-mcp) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/jkudish/jev-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/jkudish/jev-mcp?style=flat) - TypeSafe の Jev モデルを型付き判定ツール（検証、分類、再ランク、抽出、レビューなど）として公開する MCP サーバー。

## ブラウザ・Web・スクレイピング

- [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) ![GitHub stars](https://img.shields.io/github/stars/D4Vinci/Scrapling?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/D4Vinci/Scrapling?style=flat) - MCP サーバー付きの Web スクレイピングフレームワーク。
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ![GitHub stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft/playwright-mcp?style=flat) - 公式 Playwright MCP サーバー。
- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/apify/apify-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/apify/apify-mcp-server?style=flat) - 数千の既成スクレイパーを MCP 経由で利用。
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/firecrawl/firecrawl-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/firecrawl/firecrawl-mcp-server?style=flat) - 公式 Firecrawl MCP サーバー。
- [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) ![GitHub stars](https://img.shields.io/github/stars/BrowserMCP/mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/BrowserMCP/mcp?style=flat) - AI アプリからブラウザを操作。
- [KnockOutEZ/wigolo](https://github.com/KnockOutEZ/wigolo) ![GitHub stars](https://img.shields.io/github/stars/KnockOutEZ/wigolo?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/KnockOutEZ/wigolo?style=flat) - ローカルファーストの Web 検索・取得・クロールを MCP で提供。
- [vibheksoni/stealth-browser-mcp](https://github.com/vibheksoni/stealth-browser-mcp) ![GitHub stars](https://img.shields.io/github/stars/vibheksoni/stealth-browser-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/vibheksoni/stealth-browser-mcp?style=flat) - CDP 経由のステルスブラウザ自動化。
- [zhizhuodemao/js-reverse-mcp](https://github.com/zhizhuodemao/js-reverse-mcp) ![GitHub stars](https://img.shields.io/github/stars/zhizhuodemao/js-reverse-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/zhizhuodemao/js-reverse-mcp?style=flat) - JS リバースエンジニアリング用 MCP サーバー。
- [brightdata/brightdata-mcp](https://github.com/brightdata/brightdata-mcp) ![GitHub stars](https://img.shields.io/github/stars/brightdata/brightdata-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/brightdata/brightdata-mcp?style=flat) - 公開 Web へのアクセスを提供する MCP サーバー。
- [A9T9/RPA](https://github.com/A9T9/RPA) ![GitHub stars](https://img.shields.io/github/stars/A9T9/RPA?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/A9T9/RPA?style=flat) - MCP サーバー付きのブラウザ/デスクトップ自動化。
- [vmoranv/jshookmcp](https://github.com/vmoranv/jshookmcp) ![GitHub stars](https://img.shields.io/github/stars/vmoranv/jshookmcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/vmoranv/jshookmcp?style=flat) - 735 ツールを備えたリバースエンジニアリング用ワークスペース。
- [opentabs-dev/opentabs](https://github.com/opentabs-dev/opentabs) ![GitHub stars](https://img.shields.io/github/stars/opentabs-dev/opentabs?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/opentabs-dev/opentabs?style=flat) - ボタンをクリックする代わりに Web アプリの API を呼び出す。
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) ![GitHub stars](https://img.shields.io/github/stars/feder-cr/invisible_playwright_mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/feder-cr/invisible_playwright_mcp?style=flat) - 検出されにくい Playwright MCP サーバー。
- [vostride/agent-qa](https://github.com/vostride/agent-qa) ![GitHub stars](https://img.shields.io/github/stars/vostride/agent-qa?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/vostride/agent-qa?style=flat) - memidex の永続メモリと検証付き自己改善を備え、Web・Android・iOS を自然言語でテスト。ローカル MCP サーバーでテストと実行証拠を扱う。 [公式サイト](https://vostride.com).

## 画像・動画・音声の操作
画像・動画・音声の生成、編集、解析、処理をエージェントに行わせる MCP サーバーとツール。
MCP servers and tools that let agents generate, edit, analyze, or process images, video and sound.

### 画像・デザイン

- [Manavarya09/design-extract](https://github.com/Manavarya09/design-extract) ![GitHub stars](https://img.shields.io/github/stars/Manavarya09/design-extract?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Manavarya09/design-extract?style=flat) - Web サイトのデザインシステム(トークン、Figma 変数、Tailwind)を MCP サーバーで抽出。
- [glincker/thesvg](https://github.com/glincker/thesvg) ![GitHub stars](https://img.shields.io/github/stars/glincker/thesvg?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/glincker/thesvg?style=flat) - MCP で検索できるオープンな SVG ブランド/クラウドアイコンライブラリ。
- [jau123/MeiGen-AI-Design-MCP](https://github.com/jau123/MeiGen-AI-Design-MCP) ![GitHub stars](https://img.shields.io/github/stars/jau123/MeiGen-AI-Design-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/jau123/MeiGen-AI-Design-MCP?style=flat) - 最新の AI モデルでインスピレーション探しと画像・動画の作成。
- [marvkr/better-design](https://github.com/marvkr/better-design) ![GitHub stars](https://img.shields.io/github/stars/marvkr/better-design?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/marvkr/better-design?style=flat) - デザインシステム MCP サーバーと shadcn/ui レジストリ。

### 動画

- [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) ![GitHub stars](https://img.shields.io/github/stars/kajisho5/ffmpeg-skill?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kajisho5/ffmpeg-skill?style=flat) - カット・字幕・リフレーム・書き出し用のローカル FFmpeg ツール 42 個と MCP サーバー。
- [jordanrendric/claude-video-vision](https://github.com/jordanrendric/claude-video-vision) ![GitHub stars](https://img.shields.io/github/stars/jordanrendric/claude-video-vision?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/jordanrendric/claude-video-vision?style=flat) - Claude に動画を見せて理解させる(フレーム抽出と音声解析)。
- [xixihhhh/clipforge](https://github.com/xixihhhh/clipforge) ![GitHub stars](https://img.shields.io/github/stars/xixihhhh/clipforge?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/xixihhhh/clipforge?style=flat) - EC 向けのオープンソース AI ショート動画ジェネレータ(MCP 対応)。

### 音声・サウンド

- [MiniMax-AI/MiniMax-MCP](https://github.com/MiniMax-AI/MiniMax-MCP) ![GitHub stars](https://img.shields.io/github/stars/MiniMax-AI/MiniMax-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MiniMax-AI/MiniMax-MCP?style=flat) - MiniMax 公式 MCP: 音声合成、ボイスクローン、画像・動画生成。
- [kanaworksai-hue/audio-studio-mcp](https://github.com/kanaworksai-hue/audio-studio-mcp) ![GitHub stars](https://img.shields.io/github/stars/kanaworksai-hue/audio-studio-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kanaworksai-hue/audio-studio-mcp?style=flat) - ローカルで動く AI BGM/効果音生成(Stable Audio 3)。クラウドも API キーも不要。

### オールインワン・クリエイティブスタジオ

- [artokun/comfyui-mcp](https://github.com/artokun/comfyui-mcp) ![GitHub stars](https://img.shields.io/github/stars/artokun/comfyui-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/artokun/comfyui-mcp?style=flat) - ComfyUI 用の MCP サーバー兼エージェント: 画像・動画・音声、178 ツール。
- [guaardvark/guaardvark](https://github.com/guaardvark/guaardvark) ![GitHub stars](https://img.shields.io/github/stars/guaardvark/guaardvark?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/guaardvark/guaardvark?style=flat) - ローカルの動画・画像・音楽・音声生成を備えたセルフホスト AI スタジオ(MCP サーバー付き)。

### ArtCraft エコシステム(例外: ★100 未満)
[ArtCraft](https://github.com/storytold/artcraft) は AI による画像・動画制作のためのオープンソース「アーティスト向け IDE」です。その周辺に Rust 製の「Craft」アプリ群があり、以下のサードパーティ製プロジェクトが MCP・CLI・スキルを通じてエージェントから使えるようにしています。いずれも 2026 年に作成され最近も更新されていますが、大半は ★100 未満のため、初期段階のものとして扱ってください。
[ArtCraft](https://github.com/storytold/artcraft) (★37.9k) is an open-source "IDE for artists" for AI image and video creation. A family of Rust "Craft" apps surrounds it; third-party projects below expose them to agents through MCP, CLI or skills. All of these were created in 2026 and pushed recently, but most have fewer than 100 stars, so treat them as early-stage.
ホストアプリ(MCP 面は以下のサードパーティ製プロジェクトのドキュメントによるもので、各 README では未検証):
Host apps (MCP surface is documented by the third-party projects below, not verified in each README):
[PhotoCraft](https://github.com/storytold/photocraft) ★75.4k (photo editor) · [LightCraft](https://github.com/storytold/lightcraft) ★15.1k (RAW editor) · [VectorCraft](https://github.com/storytold/vectorcraft) ★11.1k (vector art) · [FilmCraft](https://github.com/storytold/filmcraft) ★17.0k (video editor) · [EffectCraft](https://github.com/storytold/effectcraft) ★8.2k (motion graphics)
MCP サーバー、ゲートウェイ、スキル:
MCP servers, gateways and skills:

- [herdodp/snapgent-connector](https://github.com/herdodp/snapgent-connector) ![GitHub stars](https://img.shields.io/github/stars/herdodp/snapgent-connector?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/herdodp/snapgent-connector?style=flat) - 多数のアプリを MCP でつなぐチャットボットコネクタ。
- [midasmatterhorn/artcraft-skills](https://github.com/midasmatterhorn/artcraft-skills) ![GitHub stars](https://img.shields.io/github/stars/midasmatterhorn/artcraft-skills?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/midasmatterhorn/artcraft-skills?style=flat) - ArtCraft スイート向けの、証拠で検証されたエージェントスキル(MCP と CLI)。
- [theCosmicCrafter/artcraft-mcp](https://github.com/theCosmicCrafter/artcraft-mcp) ![GitHub stars](https://img.shields.io/github/stars/theCosmicCrafter/artcraft-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/theCosmicCrafter/artcraft-mcp?style=flat) - ArtCraft 用の Rust 製 MCP サーバー。
- [devsolux/storytold](https://github.com/devsolux/storytold) ![GitHub stars](https://img.shields.io/github/stars/devsolux/storytold?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/devsolux/storytold?style=flat) - 13 個のヘッドレス Craft MCP アプリ(写真、ベクター、動画、RAW、音声、モーションなど)を操作する Claude Code/Codex プラグイン。
- [smoermeow/artcraft-mcp](https://github.com/smoermeow/artcraft-mcp) ![GitHub stars](https://img.shields.io/github/stars/smoermeow/artcraft-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/smoermeow/artcraft-mcp?style=flat) - Hermes Agent 向けの ArtCraft サブスクリプション MCP サーバー(画像・動画生成)。
- [kjranyone/artcraft-agent-skills](https://github.com/kjranyone/artcraft-agent-skills) ![GitHub stars](https://img.shields.io/github/stars/kjranyone/artcraft-agent-skills?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kjranyone/artcraft-agent-skills?style=flat) - CLI・MCP・GUI ブリッジで FilmCraft(動画編集)と EffectCraft(モーショングラフィックス/VFX)を操作するスキル。
- [xiewg1987/artcraft-command-bridge](https://github.com/xiewg1987/artcraft-command-bridge) ![GitHub stars](https://img.shields.io/github/stars/xiewg1987/artcraft-command-bridge?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/xiewg1987/artcraft-command-bridge?style=flat) - 13 個すべての Craft アプリ向けの単一 MCP サーバー(799 ツールを 5 ツールに集約)。
- [jw2122-kiwi/artcraft-mcp](https://github.com/jw2122-kiwi/artcraft-mcp) ![GitHub stars](https://img.shields.io/github/stars/jw2122-kiwi/artcraft-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/jw2122-kiwi/artcraft-mcp?style=flat) - 13 個の Craft アプリを 1 つの HTTP エンドポイントにまとめる MCP ゲートウェイ。
- [GadatheGod/artcraft-mcp-unified-router](https://github.com/GadatheGod/artcraft-mcp-unified-router) ![GitHub stars](https://img.shields.io/github/stars/GadatheGod/artcraft-mcp-unified-router?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/GadatheGod/artcraft-mcp-unified-router?style=flat) - 動的ツール探索を備えた統合 MCP ルーター。
- [Shin-seong-su/artcraft-mcp](https://github.com/Shin-seong-su/artcraft-mcp) ![GitHub stars](https://img.shields.io/github/stars/Shin-seong-su/artcraft-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Shin-seong-su/artcraft-mcp?style=flat) - ChatGPT からローカルの ArtCraft アプリを操作(macOS インストーラ、ベータ)。
- [sandraschi/democraft-mcp](https://github.com/sandraschi/democraft-mcp) ![GitHub stars](https://img.shields.io/github/stars/sandraschi/democraft-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sandraschi/democraft-mcp?style=flat) - 13 個の Craft アプリが実ファイル(MP4、WAV、DOCX など)を生成するライブデモ。MCP サーバーと Web アプリ。
- [kosecom/art-cli](https://github.com/kosecom/art-cli) ![GitHub stars](https://img.shields.io/github/stars/kosecom/art-cli?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kosecom/art-cli?style=flat) - CLI と stdio MCP による Hermes 向け ArtCraft 連携(Windows/macOS)。
- [dnviti/artcraft-skills](https://github.com/dnviti/artcraft-skills) ![GitHub stars](https://img.shields.io/github/stars/dnviti/artcraft-skills?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/dnviti/artcraft-skills?style=flat) - skills.sh でインストールできる ArtCraft アプリ向けコミュニティスキル。
- [lznnnnn1998/dsh-artcraft](https://github.com/lznnnnn1998/dsh-artcraft) ![GitHub stars](https://img.shields.io/github/stars/lznnnnn1998/dsh-artcraft?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/lznnnnn1998/dsh-artcraft?style=flat) - Craft アプリ(CADCraft、GridCraft、SoundCraft など)を操作する 12 個の DSH プラグイン。
- [verdulife/pi-artcraft](https://github.com/verdulife/pi-artcraft) ![GitHub stars](https://img.shields.io/github/stars/verdulife/pi-artcraft?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/verdulife/pi-artcraft?style=flat) - FigCraft と VectorCraft をセッションごとに切り替え、MCP を接続する Pi パッケージ。
- [joaoalvesmarrucho/patio-artcraft](https://github.com/joaoalvesmarrucho/patio-artcraft) ![GitHub stars](https://img.shields.io/github/stars/joaoalvesmarrucho/patio-artcraft?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/joaoalvesmarrucho/patio-artcraft?style=flat) - 公式 MCP ルート経由で VectorCraft を操作するスキル。
- [anton-belkin/aitocraft](https://github.com/anton-belkin/aitocraft) ![GitHub stars](https://img.shields.io/github/stars/anton-belkin/aitocraft?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/anton-belkin/aitocraft?style=flat) - GridCraft・WordCraft・DeckCraft でドキュメントを開く単一の MCP コネクタ。
- [MGBuilds9/craft-agent-kit](https://github.com/MGBuilds9/craft-agent-kit) ![GitHub stars](https://img.shields.io/github/stars/MGBuilds9/craft-agent-kit?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MGBuilds9/craft-agent-kit?style=flat) - 全 13 アプリ向けの CLI ラッパー、MCP 設定、スキル。
- [esanchma/mcp-trigger](https://github.com/esanchma/mcp-trigger) ![GitHub stars](https://img.shields.io/github/stars/esanchma/mcp-trigger?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/esanchma/mcp-trigger?style=flat) - ツール呼び出し時にだけ ArtCraft デスクトップアプリを起動する stdio MCP サーバー。
- [MGrunwald42/safecraft-mcp](https://github.com/MGrunwald42/safecraft-mcp) ![GitHub stars](https://img.shields.io/github/stars/MGrunwald42/safecraft-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MGrunwald42/safecraft-mcp?style=flat) - サンドボックス内で MCP 経由の ArtCraft ツールを実行。
- [xouel/artcraft-ai-bridge](https://github.com/xouel/artcraft-ai-bridge) ![GitHub stars](https://img.shields.io/github/stars/xouel/artcraft-ai-bridge?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/xouel/artcraft-ai-bridge?style=flat) - Windows 上で FigCraft・PhotoCraft・GridCraft をつなぐ C#/WPF 製 MCP ブリッジ。
- [kleinhansda/artcraft-mcp-ha](https://github.com/kleinhansda/artcraft-mcp-ha) ![GitHub stars](https://img.shields.io/github/stars/kleinhansda/artcraft-mcp-ha?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kleinhansda/artcraft-mcp-ha?style=flat) - VectorCraft・PhotoCraft・PdfCraft をリモート MCP サーバーとして公開する Home Assistant アドオン。

## 3D・CAD・ゲームエンジン・シミュレーション
エージェントに 3D ツール、CAD、3D プリンタ、ゲームエンジンを操作させる MCP サーバー。工学シミュレーションは [CAE・工学シミュレーション](#cae工学シミュレーション) を参照。
MCP servers that let agents drive 3D tools, CAD, 3D printers and game engines. For engineering simulation see [CAE & Engineering Simulation](#cae--engineering-simulation).

### 3D・Blender

- [ahujasid/mcp-for-blender](https://github.com/ahujasid/mcp-for-blender) ![GitHub stars](https://img.shields.io/github/stars/ahujasid/mcp-for-blender?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ahujasid/mcp-for-blender?style=flat) - 任意の LLM で Blender 3D を操作するコミュニティプラグイン(Blender MCP)。
- [pascalorg/editor](https://github.com/pascalorg/editor) ![GitHub stars](https://img.shields.io/github/stars/pascalorg/editor?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/pascalorg/editor?style=flat) - ローカル CLI と MCP ツールを備えたオープンソースの 3D 建築エディタ。
- [scenario-labs/skills](https://github.com/scenario-labs/skills) ![GitHub stars](https://img.shields.io/github/stars/scenario-labs/skills?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/scenario-labs/skills?style=flat) - Scenario MCP による画像・動画・音声・3D のスキルと、Blender・Maya・ZBrush・Unreal・Unity を操作するチーム向けスキル。
- [scenario-labs/blender-plugin](https://github.com/scenario-labs/blender-plugin) ![GitHub stars](https://img.shields.io/github/stars/scenario-labs/blender-plugin?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/scenario-labs/blender-plugin?style=flat) - AI 画像・動画・3D・PBR マテリアルとローカル MCP サーバーを備えた Blender 拡張。
- [EL4CTEO/blender-skills](https://github.com/EL4CTEO/blender-skills) ![GitHub stars](https://img.shields.io/github/stars/EL4CTEO/blender-skills?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/EL4CTEO/blender-skills?style=flat) - プロ向け Blender ワークフロー(モデリング、UV、PBR、リギング、書き出し)をエージェントスキル化。
- [reality-opened/openreality](https://github.com/reality-opened/openreality) ![GitHub stars](https://img.shields.io/github/stars/reality-opened/openreality?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/reality-opened/openreality?style=flat) - スマホ動画から、AI が問い合わせ可能な 3D シーンを生成(MCP ツール付き)。
- [squall01337/mixamo-llm-mocap](https://github.com/squall01337/mixamo-llm-mocap) ![GitHub stars](https://img.shields.io/github/stars/squall01337/mixamo-llm-mocap?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/squall01337/mixamo-llm-mocap?style=flat) - 任意の動画を Mixamo リグのアニメーションに変換し、MCP 経由で Blender に適用。
- [instruktlabs/kiln](https://github.com/instruktlabs/kiln) ![GitHub stars](https://img.shields.io/github/stars/instruktlabs/kiln?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/instruktlabs/kiln?style=flat) - ローカル MCP サーバーと GLB 書き出しを備えた手続き型 3D アセットビルダー。
- [nirholas/three.ws](https://github.com/nirholas/three.ws) ![GitHub stars](https://img.shields.io/github/stars/nirholas/three.ws?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/nirholas/three.ws?style=flat) - 3D AI エージェントとリグ付き GLB アバターのためのプラットフォーム(リモート MCP サーバー付き)。
- [HoldMyBeer-gg/blenderwright](https://github.com/HoldMyBeer-gg/blenderwright) ![GitHub stars](https://img.shields.io/github/stars/HoldMyBeer-gg/blenderwright?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/HoldMyBeer-gg/blenderwright?style=flat) - モデリング・マテリアル・レンダリング用の数百ツールを持つ Blender MCP サーバー。

### CAD・3D プリント

- [spkane/freecad-addon-robust-mcp-server](https://github.com/spkane/freecad-addon-robust-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/spkane/freecad-addon-robust-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/spkane/freecad-addon-robust-mcp-server?style=flat) - 堅牢な FreeCAD 用 MCP サーバーとブリッジワークベンチ。
- [DMontgomery40/mcp-3D-printer-server](https://github.com/DMontgomery40/mcp-3D-printer-server) ![GitHub stars](https://img.shields.io/github/stars/DMontgomery40/mcp-3D-printer-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/DMontgomery40/mcp-3D-printer-server?style=flat) - 3D プリンタ API(OctoPrint、Klipper、Bambu など)と STL 操作のための MCP。
- [DMontgomery40/bambu-printer-mcp](https://github.com/DMontgomery40/bambu-printer-mcp) ![GitHub stars](https://img.shields.io/github/stars/DMontgomery40/bambu-printer-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/DMontgomery40/bambu-printer-mcp?style=flat) - Bambu Lab プリンタ向け MCP: STL ツール、スライス、プリンタ制御。
- [codeofaxel/Kiln](https://github.com/codeofaxel/Kiln) ![GitHub stars](https://img.shields.io/github/stars/codeofaxel/Kiln?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/codeofaxel/Kiln?style=flat) - Git 風のデザインバージョン管理を備えた 3D プリント用 MCP サーバー。
- [U-C4N/Autocad-MCP](https://github.com/U-C4N/Autocad-MCP) ![GitHub stars](https://img.shields.io/github/stars/U-C4N/Autocad-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/U-C4N/Autocad-MCP?style=flat) - DWG/DXF の作図・編集・読取りができる 240 以上のツールを持つ AutoCAD MCP サーバー。
- [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) ![GitHub stars](https://img.shields.io/github/stars/earthtojake/text-to-cad?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/earthtojake/text-to-cad?style=flat) - AI コーディングエージェント向けの MIT ライセンス CAD スキル集(build123d スクリプトから STEP/STL/3MF/GLB、DFM チェック、製図、DXF、URDF、G-code)。

### ゲームエンジン

- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) ![GitHub stars](https://img.shields.io/github/stars/IvanMurzak/Unity-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/IvanMurzak/Unity-MCP?style=flat) - Unity Engine 向けの AI スキル、MCP ツール、CLI。
- [ChiR24/Unreal_mcp](https://github.com/ChiR24/Unreal_mcp) ![GitHub stars](https://img.shields.io/github/stars/ChiR24/Unreal_mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ChiR24/Unreal_mcp?style=flat) - C++ Automation Bridge プラグイン経由で Unreal Engine を制御する MCP サーバー。
- [kevinpbuckley/VibeUE](https://github.com/kevinpbuckley/VibeUE) ![GitHub stars](https://img.shields.io/github/stars/kevinpbuckley/VibeUE?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kevinpbuckley/VibeUE?style=flat) - MCP サーバー付きの Unreal Engine バイブコーディングツール。
- [AnkleBreaker-Studio/unity-mcp-server](https://github.com/AnkleBreaker-Studio/unity-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/AnkleBreaker-Studio/unity-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/AnkleBreaker-Studio/unity-mcp-server?style=flat) - エディタと Unity Hub 向けの 268 ツールを持つ Unity MCP サーバー。
- [tugcantopaloglu/godot-mcp](https://github.com/tugcantopaloglu/godot-mcp) ![GitHub stars](https://img.shields.io/github/stars/tugcantopaloglu/godot-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/tugcantopaloglu/godot-mcp?style=flat) - 157 ツールを持つ Godot 4.x 用 MCP サーバー。
- [db-lyon/ue-mcp](https://github.com/db-lyon/ue-mcp) ![GitHub stars](https://img.shields.io/github/stars/db-lyon/ue-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/db-lyon/ue-mcp?style=flat) - MCP ツールとして公開された Unreal Engine 開発ツールキット。
- [IvanMurzak/Godot-MCP](https://github.com/IvanMurzak/Godot-MCP) ![GitHub stars](https://img.shields.io/github/stars/IvanMurzak/Godot-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/IvanMurzak/Godot-MCP?style=flat) - C# による Godot エディタ向け MCP 連携。
- [FunplayAI/funplay-unity-mcp](https://github.com/FunplayAI/funplay-unity-mcp) ![GitHub stars](https://img.shields.io/github/stars/FunplayAI/funplay-unity-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/FunplayAI/funplay-unity-mcp?style=flat) - コード実行とプレイモード自動化を備えた Unity エディタ MCP サーバー。

## CAE・工学シミュレーション
構造解析(FEA)、流体解析(CFD)、マルチフィジックス、数値計算。この分野はまだ若いため、このセクションのスター基準は ★10 以上です。
Structural (FEA), fluid (CFD), multiphysics and numerical computing. Star bar for this section is ★10+ because the field is young.

- [matlab/matlab-mcp-server](https://github.com/matlab/matlab-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/matlab/matlab-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/matlab/matlab-mcp-server?style=flat) - MathWorks 公式の MATLAB MCP サーバー。
- [tangency-labs/fieldcraft](https://github.com/tangency-labs/fieldcraft) ![GitHub stars](https://img.shields.io/github/stars/tangency-labs/fieldcraft?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/tangency-labs/fieldcraft?style=flat) - 構造・熱・流体向けの Rust 製モデラー: メッシュ生成、非線形 FEA、格子ボルツマン CFD。エンジニアとエージェント向け。
- [yusong652/itasca-mcp](https://github.com/yusong652/itasca-mcp) ![GitHub stars](https://img.shields.io/github/stars/yusong652/itasca-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/yusong652/itasca-mcp?style=flat) - ITASCA エンジン(PFC、FLAC、3DEC)用 MCP サーバー: 地盤工学・地質力学シミュレーション。
- [Whfkl/Abaqus-Control-MCP](https://github.com/Whfkl/Abaqus-Control-MCP) ![GitHub stars](https://img.shields.io/github/stars/Whfkl/Abaqus-Control-MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Whfkl/Abaqus-Control-MCP?style=flat) - Abaqus/CAE をリアルタイム制御するローカル MCP ブリッジ。
- [gokeshenzhen/TraceWeave](https://github.com/gokeshenzhen/TraceWeave) ![GitHub stars](https://img.shields.io/github/stars/gokeshenzhen/TraceWeave?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/gokeshenzhen/TraceWeave?style=flat) - RTL シミュレーションのデバッグ(VCS/Xcelium ログ、波形、UVM)用 MCP サーバー。
- [hongwenwang36-eng/ANSYS-Workbench-mcp](https://github.com/hongwenwang36-eng/ANSYS-Workbench-mcp) ![GitHub stars](https://img.shields.io/github/stars/hongwenwang36-eng/ANSYS-Workbench-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/hongwenwang36-eng/ANSYS-Workbench-mcp?style=flat) - Ansys Workbench と MAPDL のバッチ自動化用ローカル MCP ブリッジ。
- [cavoiie/fluent-cfd-skill](https://github.com/cavoiie/fluent-cfd-skill) ![GitHub stars](https://img.shields.io/github/stars/cavoiie/fluent-cfd-skill?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/cavoiie/fluent-cfd-skill?style=flat) - Ansys Fluent と PyFluent の CFD ワークフロー用スキル。
- [armpro24-blip/cad-cae-copilot](https://github.com/armpro24-blip/cad-cae-copilot) ![GitHub stars](https://img.shields.io/github/stars/armpro24-blip/cad-cae-copilot?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/armpro24-blip/cad-cae-copilot?style=flat) - MCP ツール付きのテキストから CAD/CAE を生成するワークベンチ(build123d/OpenCASCADE、CalculiX)。
- [ansys/pyfluent-mcp](https://github.com/ansys/pyfluent-mcp) ![GitHub stars](https://img.shields.io/github/stars/ansys/pyfluent-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ansys/pyfluent-mcp?style=flat) - 公式 PyFluent MCP サーバー。
- [kimimgo/awesome-ai-cae](https://github.com/kimimgo/awesome-ai-cae) ![GitHub stars](https://img.shields.io/github/stars/kimimgo/awesome-ai-cae?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kimimgo/awesome-ai-cae?style=flat) - AI 対応 CAE ツール 100 件超の厳選リスト(CFD、FEA、SPH、DEM、MCP サーバー)。
- [ansys/pymechanical-mcp](https://github.com/ansys/pymechanical-mcp) ![GitHub stars](https://img.shields.io/github/stars/ansys/pymechanical-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ansys/pymechanical-mcp?style=flat) - 公式 PyMechanical MCP サーバー。
- [sandraschi/freecad-mcp](https://github.com/sandraschi/freecad-mcp) ![GitHub stars](https://img.shields.io/github/stars/sandraschi/freecad-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sandraschi/freecad-mcp?style=flat) - FluidX3D と OpenFOAM の CFD 拡張を備えた FreeCAD 自動化。
- [ansys/pyaedt-mcp](https://github.com/ansys/pyaedt-mcp) ![GitHub stars](https://img.shields.io/github/stars/ansys/pyaedt-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ansys/pyaedt-mcp?style=flat) - 公式 PyAEDT MCP サーバー(電磁界解析)。
- [open-PASO/openPASO](https://github.com/open-PASO/openPASO) ![GitHub stars](https://img.shields.io/github/stars/open-PASO/openPASO?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/open-PASO/openPASO?style=flat) - クロスコード連成が可能な、9 種の有限要素/マルチフィジックスコードを実行する MCP サーバー。
- [Tomsabay/abaqus_agent](https://github.com/Tomsabay/abaqus_agent) ![GitHub stars](https://img.shields.io/github/stars/Tomsabay/abaqus_agent?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Tomsabay/abaqus_agent?style=flat) - 検証ゲート付きの AI 駆動 Abaqus ワークベンチ。
- [ansys/pyansys-common-mcp](https://github.com/ansys/pyansys-common-mcp) ![GitHub stars](https://img.shields.io/github/stars/ansys/pyansys-common-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ansys/pyansys-common-mcp?style=flat) - 公式 PyAnsys 共通 MCP。
- [kimimgo/viznoir](https://github.com/kimimgo/viznoir) ![GitHub stars](https://img.shields.io/github/stars/kimimgo/viznoir?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kimimgo/viznoir?style=flat) - CFD と OpenFOAM の結果向け、AI 対応の VTK 可視化。
- [isabecurtis023-lang/HarnessFOAM](https://github.com/isabecurtis023-lang/HarnessFOAM) ![GitHub stars](https://img.shields.io/github/stars/isabecurtis023-lang/HarnessFOAM?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/isabecurtis023-lang/HarnessFOAM?style=flat) - OpenFOAM CFD シミュレーションを自動化するマルチエージェントフレームワーク(LangGraph、MCP)。

## 計測・計測機器
物理計測、試験装置、組込みデバッグ、産業用プロトコル向けの MCP サーバー。分野が非常に新しく(ほぼ全てが 2026 年に登場)、スター基準は ★1 以上です。粗削りな部分があることを想定してください。
MCP servers for physical measurement, test equipment, embedded debugging and industrial protocols. Star bar for this section is ★1+ because the field is very young (almost everything here appeared in 2026). Expect rough edges.

### 計測機器制御・試験装置

- [lagerdata/lager](https://github.com/lagerdata/lager) ![GitHub stars](https://img.shields.io/github/stars/lagerdata/lager?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/lagerdata/lager?style=flat) - ハードウェアテスト自動化: ノート PC や CI から実機の計測器や組込みターゲットを操作。
- [Anai-Guo/LabAgent](https://github.com/Anai-Guo/LabAgent) ![GitHub stars](https://img.shields.io/github/stars/Anai-Guo/LabAgent?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Anai-Guo/LabAgent?style=flat) - GPIB/PyVISA 計測器(Keithley、Lakeshore)向け 46 種の測定テンプレートを持つ AI ラボアシスタント。
- [mrn2se/AgenticWebInstrumentControl](https://github.com/mrn2se/AgenticWebInstrumentControl) ![GitHub stars](https://img.shields.io/github/stars/mrn2se/AgenticWebInstrumentControl?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mrn2se/AgenticWebInstrumentControl?style=flat) - 安価な USB オシロスコープ/ロジックアナライザの Web・AI エージェント・SCPI 制御。
- [techmanual-ai/lablink-mcp](https://github.com/techmanual-ai/lablink-mcp) ![GitHub stars](https://img.shields.io/github/stars/techmanual-ai/lablink-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/techmanual-ai/lablink-mcp?style=flat) - VISA/SCPI、SSH、REST、シリアル経由のラボ機器向け統合 MCP サーバー。
- [sandraschi/oscilloscope-mcp](https://github.com/sandraschi/oscilloscope-mcp) ![GitHub stars](https://img.shields.io/github/stars/sandraschi/oscilloscope-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sandraschi/oscilloscope-mcp?style=flat) - USB PC オシロスコープ用 FastMCP サーバー。
- [reinhardjvv/labrat](https://github.com/reinhardjvv/labrat) ![GitHub stars](https://img.shields.io/github/stars/reinhardjvv/labrat?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/reinhardjvv/labrat?style=flat) - ラボ自動化(計測器制御、SCPI)のためのユニバーサルインターフェース。
- [mabl/pyMSO5000](https://github.com/mabl/pyMSO5000) ![GitHub stars](https://img.shields.io/github/stars/mabl/pyMSO5000?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mabl/pyMSO5000?style=flat) - Rigol MSO5000 オシロスコープ用 Python クライアントと MCP サーバー。
- [KenosInc/dwf-mcp-server](https://github.com/KenosInc/dwf-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/KenosInc/dwf-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/KenosInc/dwf-mcp-server?style=flat) - Digilent Analog Discovery 3(スコープ、信号発生器、ロジック解析)用 MCP サーバー。
- [fengbihe/ScopeBridge](https://github.com/fengbihe/ScopeBridge) ![GitHub stars](https://img.shields.io/github/stars/fengbihe/ScopeBridge?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/fengbihe/ScopeBridge?style=flat) - Web UI、オフライン音声、MCP ツールを備えたローカルオシロスコープワークベンチ。
- [colingimenez/SCPI_MCP](https://github.com/colingimenez/SCPI_MCP) ![GitHub stars](https://img.shields.io/github/stars/colingimenez/SCPI_MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/colingimenez/SCPI_MCP?style=flat) - SCPI 経由で波形発生器、マルチメータ、オシロスコープ、電源を操作。
- [mp911de/siglent-scpi-mcp](https://github.com/mp911de/siglent-scpi-mcp) ![GitHub stars](https://img.shields.io/github/stars/mp911de/siglent-scpi-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mp911de/siglent-scpi-mcp?style=flat) - Siglent オシロスコープ用 MCP サーバー(TCP 上の SCPI)。
- [RainfallMax/instr-core](https://github.com/RainfallMax/instr-core) ![GitHub stars](https://img.shields.io/github/stars/RainfallMax/instr-core?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/RainfallMax/instr-core?style=flat) - AI アシスタントと物理計測器の間に置く型システム兼安全ファイアウォール。
- [sandraschi/spectrum-analyzer-mcp](https://github.com/sandraschi/spectrum-analyzer-mcp) ![GitHub stars](https://img.shields.io/github/stars/sandraschi/spectrum-analyzer-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sandraschi/spectrum-analyzer-mcp?style=flat) - RTL-SDR と TinySA 向けスペクトラムアナライザ MCP。
- [BonBear/open-ps3005d](https://github.com/BonBear/open-ps3005d) ![GitHub stars](https://img.shields.io/github/stars/BonBear/open-ps3005d?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/BonBear/open-ps3005d?style=flat) - Velleman PS3005D ラボ電源を MCP サーバーで制御。
- [f-steff/KUAIQU-NICE-PSU](https://github.com/f-steff/KUAIQU-NICE-PSU) ![GitHub stars](https://img.shields.io/github/stars/f-steff/KUAIQU-NICE-PSU?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/f-steff/KUAIQU-NICE-PSU?style=flat) - KUAIQU-NICE-POWER プログラマブル直流電源を stdio MCP サーバーで制御するコントローラ。

### ロジックアナライザ・組込みデバッグ

- [Clifford-Swartz/peripheral-pretender](https://github.com/Clifford-Swartz/peripheral-pretender) ![GitHub stars](https://img.shields.io/github/stars/Clifford-Swartz/peripheral-pretender?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Clifford-Swartz/peripheral-pretender?style=flat) - ロジックアナライザのタイムライン、フォールトインジェクション、MCP を備えた Microchip ボードの QEMU デジタルツイン。
- [YaoIsAI/SerialRUN](https://github.com/YaoIsAI/SerialRUN) ![GitHub stars](https://img.shields.io/github/stars/YaoIsAI/SerialRUN?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/YaoIsAI/SerialRUN?style=flat) - Modbus・PLC・CAN・I2C/SPI に対応し、MCP サーバーを備えたシリアルポートデバッグアシスタント。
- [keyuraghao/chipwhisperer-studio](https://github.com/keyuraghao/chipwhisperer-studio) ![GitHub stars](https://img.shields.io/github/stars/keyuraghao/chipwhisperer-studio?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/keyuraghao/chipwhisperer-studio?style=flat) - スコープ・ロジックアナライザ・MCP サーバーを備えた ChipWhisperer のサイドチャネル/フォールトインジェクションスタジオ。
- [Kyin-code/KDock](https://github.com/Kyin-code/KDock) ![GitHub stars](https://img.shields.io/github/stars/Kyin-code/KDock?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Kyin-code/KDock?style=flat) - 組込み向け AI エージェント基盤: シリアル/ネットワーク I/O、書込み、スコープ、ロジックアナライザツール。
- [KenosInc/sigrok-mcp-server](https://github.com/KenosInc/sigrok-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/KenosInc/sigrok-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/KenosInc/sigrok-mcp-server?style=flat) - sigrok-cli によるシグナルキャプチャとプロトコルデコードの AI ロジックアナライザ制御。
- [hugelzhang/atk-logic-mcp](https://github.com/hugelzhang/atk-logic-mcp) ![GitHub stars](https://img.shields.io/github/stars/hugelzhang/atk-logic-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/hugelzhang/atk-logic-mcp?style=flat) - 208 個の sigrok デコーダを持つ ALIENTEK ATK-Logic アナライザ用 MCP サーバー。
- [sandraschi/logic-analyzer-mcp](https://github.com/sandraschi/logic-analyzer-mcp) ![GitHub stars](https://img.shields.io/github/stars/sandraschi/logic-analyzer-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sandraschi/logic-analyzer-mcp?style=flat) - sigrok バックエンドを使う USB ロジックアナライザ MCP。
- [ling99LL/ag32-logic-analyzer](https://github.com/ling99LL/ag32-logic-analyzer) ![GitHub stars](https://img.shields.io/github/stars/ling99LL/ag32-logic-analyzer?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ling99LL/ag32-logic-analyzer?style=flat) - AG32VF303 上の 4 チャネルロジックアナライザ(信号発生器と MCP サーバー付き)。
- [controlpaths/tramuntana](https://github.com/controlpaths/tramuntana) ![GitHub stars](https://img.shields.io/github/stars/controlpaths/tramuntana?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/controlpaths/tramuntana?style=flat) - 組込みシステムのデバッグ(SPI/I2C/UART、スコープ、ロジックアナライザ)用オープンハードウェアツール(MCP サーバー付き)。

### LabVIEW

- [Zuehlke/labview-mcp](https://github.com/Zuehlke/labview-mcp) ![GitHub stars](https://img.shields.io/github/stars/Zuehlke/labview-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Zuehlke/labview-mcp?style=flat) - AI を LabVIEW に接続。
- [JanGoebel/LabVIEW-MCP-Server-Toolkit](https://github.com/JanGoebel/LabVIEW-MCP-Server-Toolkit) ![GitHub stars](https://img.shields.io/github/stars/JanGoebel/LabVIEW-MCP-Server-Toolkit?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/JanGoebel/LabVIEW-MCP-Server-Toolkit?style=flat) - LabVIEW から MCP サーバーをホストするためのツールキット。
- [chinayuren2022-2025/labview-native-mcp](https://github.com/chinayuren2022-2025/labview-native-mcp) ![GitHub stars](https://img.shields.io/github/stars/chinayuren2022-2025/labview-native-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/chinayuren2022-2025/labview-native-mcp?style=flat) - Windows 向けネイティブ LabVIEW 2021 VI スクリプティング MCP(COM 経由で VI の作成・配線・実行)。
- [abcdefghkang/labview-vi-mcp](https://github.com/abcdefghkang/labview-vi-mcp) ![GitHub stars](https://img.shields.io/github/stars/abcdefghkang/labview-vi-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/abcdefghkang/labview-vi-mcp?style=flat) - LabVIEW Native MCP サーバー経由の LabVIEW VI 開発と HMI 復元スキル。
- [kostandrey/labview-mcp](https://github.com/kostandrey/labview-mcp) ![GitHub stars](https://img.shields.io/github/stars/kostandrey/labview-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kostandrey/labview-mcp?style=flat) - 自己駆動型 LabVIEW コード生成の初期概念実証。
- [JorgenSteen/labview-mcp-skills](https://github.com/JorgenSteen/labview-mcp-skills) ![GitHub stars](https://img.shields.io/github/stars/JorgenSteen/labview-mcp-skills?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/JorgenSteen/labview-mcp-skills?style=flat) - LabVIEW MCP を効果的に使うためのスキル集。
- [LYXLCF/-LabVIEW-CSM-MCP-Server](https://github.com/LYXLCF/-LabVIEW-CSM-MCP-Server) ![GitHub stars](https://img.shields.io/github/stars/LYXLCF/-LabVIEW-CSM-MCP-Server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/LYXLCF/-LabVIEW-CSM-MCP-Server?style=flat) - LabVIEW CSM(Communicable State Machine)ブロックダイアグラム用 MCP サーバー。

### データ収集・センサ・産業用プロトコル

- [stixez/droid-mcp](https://github.com/stixez/droid-mcp) ![GitHub stars](https://img.shields.io/github/stars/stixez/droid-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/stixez/droid-mcp?style=flat) - センサやカメラを含む 157 のデバイスツールを公開する Android SDK と MCP サーバー。
- [nobrega8/modbench](https://github.com/nobrega8/modbench) ![GitHub stars](https://img.shields.io/github/stars/nobrega8/modbench?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/nobrega8/modbench?style=flat) - デバイステストとレジスタデバッグ用のクロスプラットフォーム Modbus TCP/RTU クライアント(MCP サーバートピック)。
- [daqifi/daqifi-core](https://github.com/daqifi/daqifi-core) ![GitHub stars](https://img.shields.io/github/stars/daqifi/daqifi-core?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/daqifi/daqifi-core?style=flat) - MCP サーバー付き DAQiFi ワイヤレスデータ収集デバイス向け公式 .NET SDK。
- [Sgh1107/FieldLink-Modbus-DataAcquisition](https://github.com/Sgh1107/FieldLink-Modbus-DataAcquisition) ![GitHub stars](https://img.shields.io/github/stars/Sgh1107/FieldLink-Modbus-DataAcquisition?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Sgh1107/FieldLink-Modbus-DataAcquisition?style=flat) - MCP 対応の Qt6 産業用 Modbus データ収集プラットフォーム(TCP/RTU、MQTT、アラーム)。

## ノート・ナレッジベース

### Obsidian・Markdown Vault

- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) ![GitHub stars](https://img.shields.io/github/stars/MarkusPfundstein/mcp-obsidian?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MarkusPfundstein/mcp-obsidian?style=flat) - Local REST API プラグイン経由の Obsidian 用 MCP サーバー。
- [coddingtonbear/obsidian-local-rest-api](https://github.com/coddingtonbear/obsidian-local-rest-api) ![GitHub stars](https://img.shields.io/github/stars/coddingtonbear/obsidian-local-rest-api?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/coddingtonbear/obsidian-local-rest-api?style=flat) - Obsidian Vault 向けの安全な REST API と MCP サーバー。
- [tianma-if/edgeever](https://github.com/tianma-if/edgeever) ![GitHub stars](https://img.shields.io/github/stars/tianma-if/edgeever?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/tianma-if/edgeever?style=flat) - ネイティブ MCP を備えた AI ネイティブのナレッジベース(Evernote/Obsidian の代替)。
- [bitbonsai/mcpvault](https://github.com/bitbonsai/mcpvault) ![GitHub stars](https://img.shields.io/github/stars/bitbonsai/mcpvault?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/bitbonsai/mcpvault?style=flat) - 安全に Obsidian Vault へアクセスする軽量 MCP サーバー。
- [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) ![GitHub stars](https://img.shields.io/github/stars/StevenStavrakis/obsidian-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/StevenStavrakis/obsidian-mcp?style=flat) - シンプルな Obsidian 用 MCP サーバー。
- [cyanheads/obsidian-mcp-server](https://github.com/cyanheads/obsidian-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/cyanheads/obsidian-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/cyanheads/obsidian-mcp-server?style=flat) - MCP 経由で Obsidian のノート、タグ、フロントマターを読み書き・検索・編集。
- [docsagent/docsagent](https://github.com/docsagent/docsagent) ![GitHub stars](https://img.shields.io/github/stars/docsagent/docsagent?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/docsagent/docsagent?style=flat) - Zotero・Obsidian・Apple Notes を横断するプライベートなナレッジベース検索。
- [rotbit/xedit](https://github.com/rotbit/xedit) ![GitHub stars](https://img.shields.io/github/stars/rotbit/xedit?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/rotbit/xedit?style=flat) - AI 向け MCP を備えたローカルファーストの Markdown エディタ(Obsidian/Notion 風)。
- [andylow92/file-system-brain-mcp](https://github.com/andylow92/file-system-brain-mcp) ![GitHub stars](https://img.shields.io/github/stars/andylow92/file-system-brain-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/andylow92/file-system-brain-mcp?style=flat) - 24 ツールの MCP サーバー、セマンティック検索、RAG を備えた Markdown Vault。

### Notion

- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/makenotion/notion-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/makenotion/notion-mcp-server?style=flat) - 公式 Notion MCP サーバー。
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) ![GitHub stars](https://img.shields.io/github/stars/suekou/mcp-notion-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/suekou/mcp-notion-server?style=flat) - Notion を MCP クライアントに接続する MCP サーバー。
- [awkoy/notion-mcp-server](https://github.com/awkoy/notion-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/awkoy/notion-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/awkoy/notion-mcp-server?style=flat) - トークン認証と小さなツール群を備えた Notion MCP サーバー。
- [makenotion/lore](https://github.com/makenotion/lore) ![GitHub stars](https://img.shields.io/github/stars/makenotion/lore?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/makenotion/lore?style=flat) - Notion を基盤にした、永続的で共有される AI メモリ。

### Zotero・Logseq・Joplin・Apple Notes

- [54yyyu/zotero-mcp](https://github.com/54yyyu/zotero-mcp) ![GitHub stars](https://img.shields.io/github/stars/54yyyu/zotero-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/54yyyu/zotero-mcp?style=flat) - Zotero ライブラリを AI アシスタントに接続。
- [papersgpt/papersgpt-for-zotero](https://github.com/papersgpt/papersgpt-for-zotero) ![GitHub stars](https://img.shields.io/github/stars/papersgpt/papersgpt-for-zotero?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/papersgpt/papersgpt-for-zotero?style=flat) - MCP サーバーを内蔵した Zotero 向け AI リサーチツール。
- [cookjohn/zotero-mcp](https://github.com/cookjohn/zotero-mcp) ![GitHub stars](https://img.shields.io/github/stars/cookjohn/zotero-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/cookjohn/zotero-mcp?style=flat) - MCP 経由で AI アシスタント連携を可能にする Zotero プラグイン。
- [ergut/mcp-logseq](https://github.com/ergut/mcp-logseq) ![GitHub stars](https://img.shields.io/github/stars/ergut/mcp-logseq?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ergut/mcp-logseq?style=flat) - ローカル HTTP API 経由の LogSeq 用 MCP サーバー。
- [introfini/ZotSeek](https://github.com/introfini/ZotSeek) ![GitHub stars](https://img.shields.io/github/stars/introfini/ZotSeek?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/introfini/ZotSeek?style=flat) - MCP サーバーを内蔵した、Zotero 向けローカル AI セマンティック検索。
- [alondmnt/joplin-mcp](https://github.com/alondmnt/joplin-mcp) ![GitHub stars](https://img.shields.io/github/stars/alondmnt/joplin-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/alondmnt/joplin-mcp?style=flat) - ノートアプリ Joplin 用 MCP サーバー。
- [sweetrb/apple-notes-mcp](https://github.com/sweetrb/apple-notes-mcp) ![GitHub stars](https://img.shields.io/github/stars/sweetrb/apple-notes-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sweetrb/apple-notes-mcp?style=flat) - macOS 上で Apple Notes の読取り・検索・作成・編集。
- [kujenga/zotero-mcp](https://github.com/kujenga/zotero-mcp) ![GitHub stars](https://img.shields.io/github/stars/kujenga/zotero-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/kujenga/zotero-mcp?style=flat) - Zotero API 用の軽量 MCP サーバー。

## Microsoft 365

### Graph・管理

- [Softeria/ms-365-mcp-server](https://github.com/Softeria/ms-365-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/Softeria/ms-365-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Softeria/ms-365-mcp-server?style=flat) - Graph API 経由の Microsoft 365/Office サービス用 MCP サーバー。
- [merill/lokka](https://github.com/merill/lokka) ![GitHub stars](https://img.shields.io/github/stars/merill/lokka?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/merill/lokka?style=flat) - Microsoft Graph を含む Microsoft 365 用 MCP。
- [pnp/cli-microsoft365-mcp-server](https://github.com/pnp/cli-microsoft365-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/pnp/cli-microsoft365-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/pnp/cli-microsoft365-mcp-server?style=flat) - MCP サーバー(CLI for Microsoft 365)で Microsoft 365 を管理。

### Teams・Outlook・カレンダー

- [Vexa-ai/vexa](https://github.com/Vexa-ai/vexa) ![GitHub stars](https://img.shields.io/github/stars/Vexa-ai/vexa?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Vexa-ai/vexa?style=flat) - Google Meet・Microsoft Teams・Zoom の会議文字起こし API(MCP サーバー付き)。
- [ridafkih/keeper.sh](https://github.com/ridafkih/keeper.sh) ![GitHub stars](https://img.shields.io/github/stars/ridafkih/keeper.sh?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ridafkih/keeper.sh?style=flat) - カレンダー同期とユニバーサルカレンダー MCP サーバー(Google、Outlook、Office 365、iCloud、CalDAV)。
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) ![GitHub stars](https://img.shields.io/github/stars/InditexTech/mcp-teams-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/InditexTech/mcp-teams-server?style=flat) - Microsoft Teams メッセージの読取り・作成・返信。
- [floriscornel/teams-mcp](https://github.com/floriscornel/teams-mcp) ![GitHub stars](https://img.shields.io/github/stars/floriscornel/teams-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/floriscornel/teams-mcp?style=flat) - Microsoft Teams と Graph API へのアクセス: メッセージ、検索、ユーザー管理。
- [tecnologicachile/mail-mcp](https://github.com/tecnologicachile/mail-mcp) ![GitHub stars](https://img.shields.io/github/stars/tecnologicachile/mail-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/tecnologicachile/mail-mcp?style=flat) - Rust 製のセキュアな IMAP/SMTP/EWS/Graph メール MCP サーバー(Microsoft 365、Gmail など)。

### Excel・Office 文書

- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/haris-musa/excel-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/haris-musa/excel-mcp-server?style=flat) - グラフ、ピボットテーブル、数式付きの Excel ファイルを作成・編集(Excel 不要)。
- [sbroenne/mcp-server-excel](https://github.com/sbroenne/mcp-server-excel) ![GitHub stars](https://img.shields.io/github/stars/sbroenne/mcp-server-excel?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sbroenne/mcp-server-excel?style=flat) - 実際の Microsoft Excel を自動化: Power Query、DAX、VBA、ピボットテーブル。
- [harumiWeb/exstruct](https://github.com/harumiWeb/exstruct) ![GitHub stars](https://img.shields.io/github/stars/harumiWeb/exstruct?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/harumiWeb/exstruct?style=flat) - LLM パイプライン向けに Excel を構造化 JSON へ変換。CLI と MCP でエージェントが読み書き。
- [Aimino-Tech/opendocswork-mcp](https://github.com/Aimino-Tech/opendocswork-mcp) ![GitHub stars](https://img.shields.io/github/stars/Aimino-Tech/opendocswork-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Aimino-Tech/opendocswork-mcp?style=flat) - Excel・Word・PowerPoint を処理する Rust 製 MCP サーバー。

### OneDrive・SharePoint・Dataverse

- [microsoft/Dataverse-skills](https://github.com/microsoft/Dataverse-skills) ![GitHub stars](https://img.shields.io/github/stars/microsoft/Dataverse-skills?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft/Dataverse-skills?style=flat) - Dataverse MCP サーバー、CLI、Python SDK をラップした AI エージェント向け Dataverse スキル。
- [lionello/onedrive-cli](https://github.com/lionello/onedrive-cli) ![GitHub stars](https://img.shields.io/github/stars/lionello/onedrive-cli?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/lionello/onedrive-cli?style=flat) - OneDrive 用のコマンドラインインターフェースと MCP。
- [microsoft/SharePoint-Embedded-Samples](https://github.com/microsoft/SharePoint-Embedded-Samples) ![GitHub stars](https://img.shields.io/github/stars/microsoft/SharePoint-Embedded-Samples?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft/SharePoint-Embedded-Samples?style=flat) - AI コーディングエージェント向け MCP サーバーを含む SharePoint Embedded のサンプル。

## セキュリティ
防御・攻撃の両面のセキュリティ作業向け MCP サーバー。攻撃的ツールは、テストの許可を得たシステムでのみ使用してください。他のセクションに載っているリバースエンジニアリングツールは [x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server)、[js-reverse-mcp](https://github.com/zhizhuodemao/js-reverse-mcp)、[jshookmcp](https://github.com/vmoranv/jshookmcp) も参照。
MCP servers for defensive and offensive security work. Use offensive tools only on systems you are authorized to test. For reverse-engineering tools listed elsewhere see [x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server), [js-reverse-mcp](https://github.com/zhizhuodemao/js-reverse-mcp) and [jshookmcp](https://github.com/vmoranv/jshookmcp).

### SOC・SIEM・脅威インテリジェンス

- [7onez/cti-expert](https://github.com/7onez/cti-expert) ![GitHub stars](https://img.shields.io/github/stars/7onez/cti-expert?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/7onez/cti-expert?style=flat) - 79 個の型付き MCP ツールと ICD-203 レポートを備えたサイバー脅威インテリジェンス/OSINT 分析スキル。
- [google/mcp-security](https://github.com/google/mcp-security) ![GitHub stars](https://img.shields.io/github/stars/google/mcp-security?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/google/mcp-security?style=flat) - Google Security Operations(Chronicle SIEM/SOAR)、脅威インテリジェンス、Security Command Center の MCP サーバー。
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) ![GitHub stars](https://img.shields.io/github/stars/CrowdStrike/falcon-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/CrowdStrike/falcon-mcp?style=flat) - セキュリティ分析と脅威ハンティングのための CrowdStrike Falcon 公式 MCP。
- [gensecaihq/Wazuh-MCP-Server](https://github.com/gensecaihq/Wazuh-MCP-Server) ![GitHub stars](https://img.shields.io/github/stars/gensecaihq/Wazuh-MCP-Server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/gensecaihq/Wazuh-MCP-Server?style=flat) - 55 ツールの Wazuh SIEM MCP サーバー: アラートトリアージ、脅威ハンティング、脆弱性管理、コンプライアンスマッピング(PCI DSS、GDPR、HIPAA、NIST CSF、ISO 27001)。
- [Sentinel-One/purple-mcp](https://github.com/Sentinel-One/purple-mcp) ![GitHub stars](https://img.shields.io/github/stars/Sentinel-One/purple-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Sentinel-One/purple-mcp?style=flat) - MCP 経由の SentinelOne Purple AI とセキュリティサービス: アラート、脆弱性、設定不備、インベントリ。

### OSINT

- [OpenOSINT/OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) ![GitHub stars](https://img.shields.io/github/stars/OpenOSINT/OpenOSINT?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/OpenOSINT/OpenOSINT?style=flat) - CLI・MCP サーバー・Web UI で使える 21 ツールのパッシブ OSINT エンジン。
- [w0h1v/mcp-maigret](https://github.com/w0h1v/mcp-maigret) ![GitHub stars](https://img.shields.io/github/stars/w0h1v/mcp-maigret?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/w0h1v/mcp-maigret?style=flat) - maigret による数千サイトのユーザー名検索。
- [OSINT-Experts-Society/Consensus-OSINT](https://github.com/OSINT-Experts-Society/Consensus-OSINT) ![GitHub stars](https://img.shields.io/github/stars/OSINT-Experts-Society/Consensus-OSINT?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/OSINT-Experts-Society/Consensus-OSINT?style=flat) - 9,700 以上の照会チェックと MCP サーバーを備えたユーザー名/メール/電話番号 OSINT。
- [w0h1v/mcp-shodan](https://github.com/w0h1v/mcp-shodan) ![GitHub stars](https://img.shields.io/github/stars/w0h1v/mcp-shodan?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/w0h1v/mcp-shodan?style=flat) - Shodan MCP: デバイス、IP 偵察、DNS、CVE/CPE インテリジェンス。
- [w0h1v/mcp-virustotal](https://github.com/w0h1v/mcp-virustotal) ![GitHub stars](https://img.shields.io/github/stars/w0h1v/mcp-virustotal?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/w0h1v/mcp-virustotal?style=flat) - URL・ファイル・IP・ドメイン向けの VirusTotal MCP。
- More: [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ★535 (curated list).

### 攻撃的セキュリティ・脆弱性スキャン

- [0x4m4/hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) ![GitHub stars](https://img.shields.io/github/stars/0x4m4/hexstrike-ai?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/0x4m4/hexstrike-ai?style=flat) - ペンテストやバグバウンティ向けに 150 以上のセキュリティツールを実行できる MCP サーバー。
- [ZeroDayEvil/ai-security-tool](https://github.com/ZeroDayEvil/ai-security-tool) ![GitHub stars](https://img.shields.io/github/stars/ZeroDayEvil/ai-security-tool?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ZeroDayEvil/ai-security-tool?style=flat) - MCP 付きの AI セキュリティターミナル兼脆弱性スキャナ(CVE、SBOM)。
- [Aletheore/Aletheore](https://github.com/Aletheore/Aletheore) ![GitHub stars](https://img.shields.io/github/stars/Aletheore/Aletheore?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Aletheore/Aletheore?style=flat) - MCP サーバー、シークレット検出、依存関係の脆弱性チェックを備えた、根拠ベースのリポジトリ監査 CLI。
- [ARCANGEL0/Mitsu](https://github.com/ARCANGEL0/Mitsu) ![GitHub stars](https://img.shields.io/github/stars/ARCANGEL0/Mitsu?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ARCANGEL0/Mitsu?style=flat) - 165 以上の MCP 接続ツールを持つエージェント型ペンテストオペレータ。
- [shinthink/blitzstrike](https://github.com/shinthink/blitzstrike) ![GitHub stars](https://img.shields.io/github/stars/shinthink/blitzstrike?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/shinthink/blitzstrike?style=flat) - MCP セキュリティ監査ツールベルト: 偵察、分析、検証。
- [hahwul/gori](https://github.com/hahwul/gori) ![GitHub stars](https://img.shields.io/github/stars/hahwul/gori?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/hahwul/gori?style=flat) - 人間とエージェントのためのキーボード駆動の HTTP 傍受プロキシ兼ペンテストツールキット。
- [sinewaveai/agent-security-scanner-mcp](https://github.com/sinewaveai/agent-security-scanner-mcp) ![GitHub stars](https://img.shields.io/github/stars/sinewaveai/agent-security-scanner-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sinewaveai/agent-security-scanner-mcp?style=flat) - コーディングエージェント向けセキュリティスキャナ: プロンプトインジェクションファイアウォール、パッケージ幻覚検出、SAST。
- [RamKansal/pentestMCP](https://github.com/RamKansal/pentestMCP) ![GitHub stars](https://img.shields.io/github/stars/RamKansal/pentestMCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/RamKansal/pentestMCP?style=flat) - ペネトレーションテスター向けに設計された MCP。

### リバースエンジニアリング・マルウェア解析

- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) ![GitHub stars](https://img.shields.io/github/stars/mrexodia/ida-pro-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mrexodia/ida-pro-mcp?style=flat) - MCP 経由で IDA Pro を言語モデルに橋渡し。
- [bethington/ghidra-mcp](https://github.com/bethington/ghidra-mcp) ![GitHub stars](https://img.shields.io/github/stars/bethington/ghidra-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/bethington/ghidra-mcp?style=flat) - 200 以上のツールを持つ Ghidra MCP サーバー(GUI プラグインとヘッドレスサーバー)。
- [CYB3RMX/Qu1cksc0pe](https://github.com/CYB3RMX/Qu1cksc0pe) ![GitHub stars](https://img.shields.io/github/stars/CYB3RMX/Qu1cksc0pe?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/CYB3RMX/Qu1cksc0pe?style=flat) - MCP サーバー付きのオールインワンマルウェア解析ツール。
- [miscusi-peek/cheatengine-mcp-bridge](https://github.com/miscusi-peek/cheatengine-mcp-bridge) ![GitHub stars](https://img.shields.io/github/stars/miscusi-peek/cheatengine-mcp-bridge?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/miscusi-peek/cheatengine-mcp-bridge?style=flat) - エージェントを Cheat Engine に接続し、メモリ解析とリバースエンジニアリングを行う。
- [qybaihe/bla](https://github.com/qybaihe/bla) ![GitHub stars](https://img.shields.io/github/stars/qybaihe/bla?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/qybaihe/bla?style=flat) - AI リバースエンジニアリングエージェントからバイナリやバンドルを守る敵対的防御シールド。
- [LING71671/open-reverselab](https://github.com/LING71671/open-reverselab) ![GitHub stars](https://img.shields.io/github/stars/LING71671/open-reverselab?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/LING71671/open-reverselab?style=flat) - Ghidra・Frida・x64dbg・Rizin 用の AI リバースエンジニアリング基盤兼 MCP サーバー。
- [alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered) ![GitHub stars](https://img.shields.io/github/stars/alexgaoth/awesome-reverse-engineered?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/alexgaoth/awesome-reverse-engineered?style=flat) - リバースエンジニアリングで作られた 17,000 以上のオープンソースツール。検索サイトと MCP サーバー付き。
- [cyberkaida/reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant) ![GitHub stars](https://img.shields.io/github/stars/cyberkaida/reverse-engineering-assistant?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/cyberkaida/reverse-engineering-assistant?style=flat) - Ghidra でのリバースエンジニアリング用 MCP サーバー。
- [sjkim1127/Reversecore_MCP](https://github.com/sjkim1127/Reversecore_MCP) ![GitHub stars](https://img.shields.io/github/stars/sjkim1127/Reversecore_MCP?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sjkim1127/Reversecore_MCP?style=flat) - リバースエンジニアリング・マルウェア解析・フォレンジック向けのセキュリティファースト MCP(Radare2、YARA、LIEF)。

### MCP・エージェントセキュリティ
エージェントと MCP サーバーのためのゲートウェイ、ガードレール、シークレット、ID、監査証跡。
Gateways, guardrails, secrets, identity and audit trails for agents and MCP servers.

- [casdoor/casdoor](https://github.com/casdoor/casdoor) ![GitHub stars](https://img.shields.io/github/stars/casdoor/casdoor?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/casdoor/casdoor?style=flat) - OAuth・OIDC・SAML・SCIM・WebAuthn・TOTP・MFA に対応した、エージェントファーストの IAM および MCP/LLM ゲートウェイ。
- [archestra-ai/archestra](https://github.com/archestra-ai/archestra) ![GitHub stars](https://img.shields.io/github/stars/archestra-ai/archestra?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/archestra-ai/archestra?style=flat) - ガードレール、MCP レジストリ、ゲートウェイを備えたエンタープライズ AI プラットフォーム。
- [octelium/octelium](https://github.com/octelium/octelium) ![GitHub stars](https://img.shields.io/github/stars/octelium/octelium?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/octelium/octelium?style=flat) - API/AI/MCP ゲートウェイとしても動作するセルフホスト型ゼロトラストアクセス基盤(SSO、MFA、ポリシー・アズ・コード)。
- [mnemox-ai/tradememory-protocol](https://github.com/mnemox-ai/tradememory-protocol) ![GitHub stars](https://img.shields.io/github/stars/mnemox-ai/tradememory-protocol?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mnemox-ai/tradememory-protocol?style=flat) - 改ざん検知ハッシュチェーンを備えた、AI トレーディングエージェントの判断監査証跡。
- [agentic-community/mcp-gateway-registry](https://github.com/agentic-community/mcp-gateway-registry) ![GitHub stars](https://img.shields.io/github/stars/agentic-community/mcp-gateway-registry?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/agentic-community/mcp-gateway-registry?style=flat) - OAuth・Keycloak・Entra ID 連携と監査に配慮したツールアクセスを備えたエンタープライズ MCP ゲートウェイ/レジストリ。
- [VibeTensor/attestix](https://github.com/VibeTensor/attestix) ![GitHub stars](https://img.shields.io/github/stars/VibeTensor/attestix?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/VibeTensor/attestix?style=flat) - エージェントの ID、署名付き資格情報、委任された権限、ガバナンス証跡。
- [HelpCode-ai/anythingmcp](https://github.com/HelpCode-ai/anythingmcp) ![GitHub stars](https://img.shields.io/github/stars/HelpCode-ai/anythingmcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/HelpCode-ai/anythingmcp?style=flat) - REST・GraphQL・SOAP・SQL の API をツール化する MCP ゲートウェイ(RBAC、SSO、監査ログ付き)。
- [notinferred/keypaste](https://github.com/notinferred/keypaste) ![GitHub stars](https://img.shields.io/github/stars/notinferred/keypaste?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/notinferred/keypaste?style=flat) - AI エージェントを扱う人向けの KeePass 互換パスワード/シークレット管理。
- [sandbaseai/sandbase-harness](https://github.com/sandbaseai/sandbase-harness) ![GitHub stars](https://img.shields.io/github/stars/sandbaseai/sandbase-harness?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sandbaseai/sandbase-harness?style=flat) - サンドボックス化されたセッション、資格情報、監査/リプレイを備えたローカルファーストのエージェントランタイム兼 MCP ブリッジ。
- [awslabs/iam-policy-autopilot](https://github.com/awslabs/iam-policy-autopilot) ![GitHub stars](https://img.shields.io/github/stars/awslabs/iam-policy-autopilot?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/awslabs/iam-policy-autopilot?style=flat) - コードからベースラインの AWS IAM ポリシーを生成(CLI と MCP サーバー)。
- [btsouth/toolport](https://github.com/btsouth/toolport) ![GitHub stars](https://img.shields.io/github/stars/btsouth/toolport?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/btsouth/toolport?style=flat) - OS キーチェーンのシークレット、ツール整合性チェック、隔離機能を備えたローカルファースト MCP ゲートウェイ。
- [MCP-Manager/MCP-Security-Checklists](https://github.com/MCP-Manager/MCP-Security-Checklists) ![GitHub stars](https://img.shields.io/github/stars/MCP-Manager/MCP-Security-Checklists?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MCP-Manager/MCP-Security-Checklists?style=flat) - MCP サーバー・クライアント・ホスト向けセキュリティチェックリスト。
- [Bevel-Software/Hexis](https://github.com/Bevel-Software/Hexis) ![GitHub stars](https://img.shields.io/github/stars/Bevel-Software/Hexis?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Bevel-Software/Hexis?style=flat) - 組織全体でエージェントのスキル、ツール、権限、ID を一元管理。

### コンプライアンス・GRC・ISMS
このサブセクションのスター基準は ★10 以上です。ISO 27001 のカバレッジはまだ薄く、スナップショット時点で ISO 27001 専用の MCP サーバーは 1 件のみです。
Star bar for this subsection is ★10+. ISO 27001 coverage is still thin: only one dedicated ISO 27001 MCP server exists at the snapshot date.

- [intuitem/ciso-assistant-community](https://github.com/intuitem/ciso-assistant-community) ![GitHub stars](https://img.shields.io/github/stars/intuitem/ciso-assistant-community?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/intuitem/ciso-assistant-community?style=flat) - 200 以上のフレームワーク(ISO 27001、NIST CSF、SOC 2、NIS2、DORA、GDPR)に対応するリスク/コンプライアンス/監査用 GRC プラットフォーム(MCP 対応)。
- [arthurpanhku/DocSentinel](https://github.com/arthurpanhku/DocSentinel) ![GitHub stars](https://img.shields.io/github/stars/arthurpanhku/DocSentinel?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/arthurpanhku/DocSentinel?style=flat) - セキュリティ文書と質問票を評価する MCP サーバー: リスク、コンプライアンスギャップ、是正策。
- [Farenhytee/database-sentinel](https://github.com/Farenhytee/database-sentinel) ![GitHub stars](https://img.shields.io/github/stars/Farenhytee/database-sentinel?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Farenhytee/database-sentinel?style=flat) - Supabase 用の読取り専用セキュリティ監査 MCP サーバー(RLS、露出キー)。スコア付きレポート。
- [Sushegaad/MCP-Server-for-ISO27001](https://github.com/Sushegaad/MCP-Server-for-ISO27001) ![GitHub stars](https://img.shields.io/github/stars/Sushegaad/MCP-Server-for-ISO27001?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Sushegaad/MCP-Server-for-ISO27001?style=flat) - ステートフルな ISO 27001:2022 ISMS サーバー: ギャップ評価、リスク管理、ポリシー生成、証跡管理、監査(暗号化ローカル SQLite)。
- [NISD2/open-isms](https://github.com/NISD2/open-isms) ![GitHub stars](https://img.shields.io/github/stars/NISD2/open-isms?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/NISD2/open-isms?style=flat) - EU NIS 2 指令(GDPR、EU AI 法、CRA)向けの無料でセルフホスト可能な ISMS(MCP 対応)。
- [writer/cerebro](https://github.com/writer/cerebro) ![GitHub stars](https://img.shields.io/github/stars/writer/cerebro?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/writer/cerebro?style=flat) - セキュリティ・ID・クラウド・コンプライアンスのデータを、エージェント向けの証拠付きコンテキストに変換。
- [ComplianceCow/cow-mcp](https://github.com/ComplianceCow/cow-mcp) ![GitHub stars](https://img.shields.io/github/stars/ComplianceCow/cow-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ComplianceCow/cow-mcp?style=flat) - GRC 業務を自動化する MCP サーバー群(Rules、Insights、Workflow、Assistant)。
- [Threat-Vector-Security/guardian-agent](https://github.com/Threat-Vector-Security/guardian-agent) ![GitHub stars](https://img.shields.io/github/stars/Threat-Vector-Security/guardian-agent?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Threat-Vector-Security/guardian-agent?style=flat) - スコープ付き MCP による脅威モデリングと GRC を備えたローカルのワークステーション/ネットワークセキュリティ(Entra ID 連携は任意)。
- [AmanSK5/shadow-ai-guard](https://github.com/AmanSK5/shadow-ai-guard) ![GitHub stars](https://img.shields.io/github/stars/AmanSK5/shadow-ai-guard?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/AmanSK5/shadow-ai-guard?style=flat) - 組織が実際に使っている AI ツール(MCP を含む)を可視化し、ガバナンスポータルを提供(ISO 27001/ISO 42001 志向)。

### Entra ID・ID管理・エンドポイント
このサブセクションのスター基準は ★10 以上です。Microsoft Entra ID、Intune、ID 対応の MCP アクセス。[Microsoft 365](#microsoft-365) も参照。
Star bar for this subsection is ★10+. Microsoft Entra ID, Intune and identity-aware MCP access. See also [Microsoft 365](#microsoft-365).

- [okieselbach/AutopilotMonitor](https://github.com/okieselbach/AutopilotMonitor) ![GitHub stars](https://img.shields.io/github/stars/okieselbach/AutopilotMonitor?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/okieselbach/AutopilotMonitor?style=flat) - AI 支援トラブルシューティング用 MCP サーバーを備えた Windows Autopilot と Intune 登録の監視。
- [Jinssi/AuthFlowMap](https://github.com/Jinssi/AuthFlowMap) ![GitHub stars](https://img.shields.io/github/stars/Jinssi/AuthFlowMap?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Jinssi/AuthFlowMap?style=flat) - OAuth、条件付きアクセス、Entra Agent ID、MCP 認証フローのインタラクティブマップ(学習リソース)。
- [OpenAdminOS/greybeard](https://github.com/OpenAdminOS/greybeard) ![GitHub stars](https://img.shields.io/github/stars/OpenAdminOS/greybeard?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/OpenAdminOS/greybeard?style=flat) - テナントへの書込みごとに人間の承認ゲートを置く、Microsoft 365・Intune・Entra 管理スキルと MCP サーバー。
- [babs/mcp-auth-proxy](https://github.com/babs/mcp-auth-proxy) ![GitHub stars](https://img.shields.io/github/stars/babs/mcp-auth-proxy?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/babs/mcp-auth-proxy?style=flat) - プライベート MCP サーバー向けの OAuth 2.1/OIDC ブリッジ(Keycloak から Entra への連携に対応)。
- [aixolotl/microsoft-planner-mcp](https://github.com/aixolotl/microsoft-planner-mcp) ![GitHub stars](https://img.shields.io/github/stars/aixolotl/microsoft-planner-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/aixolotl/microsoft-planner-mcp?style=flat) - Graph と Entra ID の委任認証を使う非公式の Microsoft Planner MCP サーバー。
- [microsoft/entrabot](https://github.com/microsoft/entrabot) ![GitHub stars](https://img.shields.io/github/stars/microsoft/entrabot?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft/entrabot?style=flat) - デバイスローカルの AI エージェントに独自の Microsoft Entra ID を与えるリファレンス実装(Agent 365、Entra Agent ID)。
- [nelladath/Intune-mcp-server](https://github.com/nelladath/Intune-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/nelladath/Intune-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/nelladath/Intune-mcp-server?style=flat) - Graph 経由の Microsoft Intune 管理用 MCP サーバー。

## ノーコードデータベース・データベース管理
SQL を手書きせずに SQL データを管理するツールと、データベース別の MCP サーバー、DBA ツール。
Tools for managing SQL data without hand-writing SQL, plus per-database MCP servers and DBA tooling.

### ノーコードデータベース(NocoDB 型)
SQL データベースの上で動くセルフホスト可能な Airtable 代替。「MCP 内蔵」と記したプラットフォームについては、ドキュメントではなく各リポジトリのソースを検索して MCP コードを確認しました。セットアップは各プロジェクトのドキュメントを確認してください。
Self-hostable Airtable alternatives that sit on top of SQL databases. For the five platforms marked "built-in MCP", MCP code was confirmed by searching each repository's source (not by reading documentation), so check the project docs for setup.

- [nocodb/nocodb](https://github.com/nocodb/nocodb) ![GitHub stars](https://img.shields.io/github/stars/nocodb/nocodb?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/nocodb/nocodb?style=flat) - PostgreSQL/SQLite 上のセルフホスト可能な Airtable 代替。MCP 内蔵(ソース内に MCP サービスとトークンあり)。
- [directus/directus](https://github.com/directus/directus) ![GitHub stars](https://img.shields.io/github/stars/directus/directus?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/directus/directus?style=flat) - SQL データベース(Postgres、MySQL、SQLite、MSSQL)をヘッドレス CMS と管理アプリに変換。MCP 内蔵(ソース内に OAuth サービスあり)。
- [teableio/teable](https://github.com/teableio/teable) ![GitHub stars](https://img.shields.io/github/stars/teableio/teable?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/teableio/teable?style=flat) - PostgreSQL 上の AI スプレッドシート。ソース内に MCP 関連の OAuth コンポーネントあり。
- [gristlabs/grist-core](https://github.com/gristlabs/grist-core) ![GitHub stars](https://img.shields.io/github/stars/gristlabs/grist-core?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/gristlabs/grist-core?style=flat) - リレーショナルなスプレッドシート型データベース。クライアントに MCP 接続バナーあり。
- [baserow/baserow](https://github.com/baserow/baserow) ![GitHub stars](https://img.shields.io/github/stars/baserow/baserow?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/baserow/baserow?style=flat) - PostgreSQL 上のノーコードデータベース/アプリビルダー。MCP 内蔵(ソース内に MCP バックエンドモジュールあり。公式設定リポジトリ [baserow/baserow-mcp](https://github.com/baserow/baserow-mcp) ![GitHub stars](https://img.shields.io/github/stars/baserow/baserow-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/baserow/baserow-mcp?style=flat))。
- [supabase/mcp](https://github.com/supabase/mcp) ![GitHub stars](https://img.shields.io/github/stars/supabase/mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/supabase/mcp?style=flat) - Supabase 公式 MCP サーバー(Postgres、認証、ストレージ)。
- [julien040/anyquery](https://github.com/julien040/anyquery) ![GitHub stars](https://img.shields.io/github/stars/julien040/anyquery?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/julien040/anyquery?style=flat) - 60 以上のツール(Notion、Airtable、GitHub)を MCP で公開する単一の SQL インターフェース。
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/domdomegg/airtable-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/domdomegg/airtable-mcp-server?style=flat) - Airtable MCP サーバー。
- [saltmd/salt.md](https://github.com/saltmd/salt.md) ![GitHub stars](https://img.shields.io/github/stars/saltmd/salt.md?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/saltmd/salt.md?style=flat) - ドキュメント、データベース、リアルタイム共同編集と MCP サーバーを、単一の Go バイナリと SQLite ファイル 1 つに集約。

### SQL クライアント・スキーマ・API ジェネレータ

- [TabularisDB/tabularis](https://github.com/TabularisDB/tabularis) ![GitHub stars](https://img.shields.io/github/stars/TabularisDB/tabularis?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/TabularisDB/tabularis?style=flat) - MCP サーバー、SQL ノートブック、ビジュアル EXPLAIN を内蔵したデスクトップ SQL ワークスペース。
- [bytebase/dbhub](https://github.com/bytebase/dbhub) ![GitHub stars](https://img.shields.io/github/stars/bytebase/dbhub?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/bytebase/dbhub?style=flat) - Postgres・MySQL・SQL Server・Oracle・MariaDB・SQLite 向けの、トークン消費に配慮したデータベース MCP サーバー。
- [dineug/erd-editor](https://github.com/dineug/erd-editor) ![GitHub stars](https://img.shields.io/github/stars/dineug/erd-editor?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/dineug/erd-editor?style=flat) - エージェントが MCP 経由でライブ編集できる ERD エディタ。
- [pgplex/pgconsole](https://github.com/pgplex/pgconsole) ![GitHub stars](https://img.shields.io/github/stars/pgplex/pgconsole?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/pgplex/pgconsole?style=flat) - 速度・コラボレーション・AI(MCP サーバー)に対応したミニマルな Postgres エディタ。
- [faucetdb/faucet](https://github.com/faucetdb/faucet) ![GitHub stars](https://img.shields.io/github/stars/faucetdb/faucet?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/faucetdb/faucet?style=flat) - 任意の SQL データベースを、RBAC と MCP 対応のガバナンスされた REST API に変換。

### データベース別 MCP サーバー

- [timescale/pg-aiguide](https://github.com/timescale/pg-aiguide) ![GitHub stars](https://img.shields.io/github/stars/timescale/pg-aiguide?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/timescale/pg-aiguide?style=flat) - Postgres のスキルとドキュメントを提供する MCP サーバー兼 Claude プラグイン。
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) ![GitHub stars](https://img.shields.io/github/stars/designcomputer/mysql_mcp_server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/designcomputer/mysql_mcp_server?style=flat) - MySQL 用のセキュアな MCP サーバー。
- [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/mongodb-js/mongodb-mcp-server?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mongodb-js/mongodb-mcp-server?style=flat) - MongoDB と MongoDB Atlas の公式 MCP サーバー。
- [redis/mcp-redis](https://github.com/redis/mcp-redis) ![GitHub stars](https://img.shields.io/github/stars/redis/mcp-redis?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/redis/mcp-redis?style=flat) - Redis 公式 MCP サーバー。
- [timescale/tiger-cli](https://github.com/timescale/tiger-cli) ![GitHub stars](https://img.shields.io/github/stars/timescale/tiger-cli?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/timescale/tiger-cli?style=flat) - 本番レベルの Postgres コード向け MCP サーバーを備えた Tiger Cloud CLI。

### 監視・DBA・ガバナンス

- [BetterDB-inc/monitor](https://github.com/BetterDB-inc/monitor) ![GitHub stars](https://img.shields.io/github/stars/BetterDB-inc/monitor?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/BetterDB-inc/monitor?style=flat) - Valkey と Redis のリアルタイム監視、スローログ分析、監査証跡。
- [erikdarlingdata/PerformanceMonitor](https://github.com/erikdarlingdata/PerformanceMonitor) ![GitHub stars](https://img.shields.io/github/stars/erikdarlingdata/PerformanceMonitor?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/erikdarlingdata/PerformanceMonitor?style=flat) - AI 分析用 MCP サーバーを備えた SQL Server/Postgres のパフォーマンス監視。
- [ashishsinha1602/schemagate](https://github.com/ashishsinha1602/schemagate) ![GitHub stars](https://img.shields.io/github/stars/ashishsinha1602/schemagate?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ashishsinha1602/schemagate?style=flat) - Text-to-SQL のアクセス制御: 呼び出し元が読めるテーブルだけを LLM に渡す(行レベルセキュリティ対応)。
- [call518/MCP-PostgreSQL-Ops](https://github.com/call518/MCP-PostgreSQL-Ops) ![GitHub stars](https://img.shields.io/github/stars/call518/MCP-PostgreSQL-Ops?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/call518/MCP-PostgreSQL-Ops?style=flat) - 30 以上の PostgreSQL DBA ツール: パフォーマンス、ブロート、ロック、autovacuum。
- [postgres-ai/postgresai](https://github.com/postgres-ai/postgresai) ![GitHub stars](https://img.shields.io/github/stars/postgres-ai/postgresai?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/postgres-ai/postgresai?style=flat) - 人間と AI エージェントのための Postgres オブザーバビリティ。
- [benseverndev-oss/goldenmatch](https://github.com/benseverndev-oss/goldenmatch) ![GitHub stars](https://img.shields.io/github/stars/benseverndev-oss/goldenmatch?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/benseverndev-oss/goldenmatch?style=flat) - 97 の MCP ツールを持つエンティティ解決/マスターデータ管理(Postgres、DuckDB)。

## データベース・検索・RAG
データベースクライアントと DBA ツールは [ノーコードデータベース・データベース管理](#ノーコードデータベースデータベース管理) を参照。
For database clients and DBA tooling see [No-code Databases & Database Management](#no-code-databases--database-management).

- [xerj-org/xerj](https://github.com/xerj-org/xerj) ![GitHub stars](https://img.shields.io/github/stars/xerj-org/xerj?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/xerj-org/xerj?style=flat) - Rust 製の検索エンジン兼 MCP サーバー(BM25、ベクトル、ハイブリッド)。
- [pipeshub-ai/pipeshub-ai](https://github.com/pipeshub-ai/pipeshub-ai) ![GitHub stars](https://img.shields.io/github/stars/pipeshub-ai/pipeshub-ai?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/pipeshub-ai/pipeshub-ai?style=flat) - 社内ナレッジ(Slack、Drive、Microsoft 365 など)に対する権限認識型のコンテキストレイヤー。

## メモリ・コンテキスト

- [doobidoo/mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) ![GitHub stars](https://img.shields.io/github/stars/doobidoo/mcp-memory-service?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/doobidoo/mcp-memory-service?style=flat) - ナレッジグラフを使ったエージェント向け永続メモリ。
- [mex-memory/mex](https://github.com/mex-memory/mex) ![GitHub stars](https://img.shields.io/github/stars/mex-memory/mex?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/mex-memory/mex?style=flat) - Git で共有するチームメモリ。
- [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) ![GitHub stars](https://img.shields.io/github/stars/headroomlabs-ai/headroom?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/headroomlabs-ai/headroom?style=flat) - ツール出力と RAG チャンクを圧縮(ライブラリ、プロキシ、MCP サーバー)。

## エージェント基盤・ゲートウェイ・クライアント

- [n8n-io/n8n](https://github.com/n8n-io/n8n) ![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/n8n-io/n8n?style=flat) - MCP クライアント/サーバーを備えたワークフロー自動化。
- [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) ![GitHub stars](https://img.shields.io/github/stars/google-gemini/gemini-cli?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/google-gemini/gemini-cli?style=flat) - ターミナル上の Gemini エージェント。
- [cheaper-inference/OmniRoute](https://github.com/cheaper-inference/OmniRoute) ![GitHub stars](https://img.shields.io/github/stars/cheaper-inference/OmniRoute?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/cheaper-inference/OmniRoute?style=flat) - MCP/A2A に対応した AI ゲートウェイ。
- [ruvnet/ruflo](https://github.com/ruvnet/ruflo) ![GitHub stars](https://img.shields.io/github/stars/ruvnet/ruflo?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ruvnet/ruflo?style=flat) - マルチエージェントのスウォームハーネス。
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) ![GitHub stars](https://img.shields.io/github/stars/CherryHQ/cherry-studio?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/CherryHQ/cherry-studio?style=flat) - MCP クライアント付きの AI ワークスペース。
- [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot) ![GitHub stars](https://img.shields.io/github/stars/AstrBotDevs/AstrBot?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/AstrBotDevs/AstrBot?style=flat) - MCP 対応のエージェントアシスタントフレームワーク。
- [Kong/kong](https://github.com/Kong/kong) ![GitHub stars](https://img.shields.io/github/stars/Kong/kong?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Kong/kong?style=flat) - MCP ゲートウェイ機能を備えた API/AI ゲートウェイ。
- [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) ![GitHub stars](https://img.shields.io/github/stars/bytedance/UI-TARS-desktop?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/bytedance/UI-TARS-desktop?style=flat) - マルチモーダル AI エージェントスタック。
- [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) ![GitHub stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/assafelovic/gpt-researcher?style=flat) - 自律型のディープリサーチエージェント。
- [deepset-ai/haystack](https://github.com/deepset-ai/haystack) ![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/deepset-ai/haystack?style=flat) - AI オーケストレーションフレームワーク。
- [activepieces/activepieces](https://github.com/activepieces/activepieces) ![GitHub stars](https://img.shields.io/github/stars/activepieces/activepieces?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/activepieces/activepieces?style=flat) - 約 400 の MCP サーバーによる自動化。
- [triggerdotdev/trigger.dev](https://github.com/triggerdotdev/trigger.dev) ![GitHub stars](https://img.shields.io/github/stars/triggerdotdev/trigger.dev?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/triggerdotdev/trigger.dev?style=flat) - 耐久性のある AI エージェントとワークフロー。
- [pacifio/atlas](https://github.com/pacifio/atlas) ![GitHub stars](https://img.shields.io/github/stars/pacifio/atlas?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/pacifio/atlas?style=flat) - コーディングエージェント向けのソース管理。
- [osaurus-ai/osaurus](https://github.com/osaurus-ai/osaurus) ![GitHub stars](https://img.shields.io/github/stars/osaurus-ai/osaurus?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/osaurus-ai/osaurus?style=flat) - AI エージェント向けのネイティブ macOS ハーネス。
- [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) ![GitHub stars](https://img.shields.io/github/stars/ThinkInAIXYZ/deepchat?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ThinkInAIXYZ/deepchat?style=flat) - MCP 対応の AI アシスタントクライアント。
- [lemma-work/lemma-platform](https://github.com/lemma-work/lemma-platform) ![GitHub stars](https://img.shields.io/github/stars/lemma-work/lemma-platform?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/lemma-work/lemma-platform?style=flat) - チーム向けのマルチプレイヤーエージェントハーネス。
- [herdrdev/herdr](https://github.com/herdrdev/herdr) ![GitHub stars](https://img.shields.io/github/stars/herdrdev/herdr?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/herdrdev/herdr?style=flat) - 多数のコーディングエージェントを並べて動かすターミナルマルチプレクサ/ワークスペースランタイム(自前の MCP サーバーはなく、エージェントの MCP 確認プロンプトを検知)。
- [manaflow-ai/cmux](https://github.com/manaflow-ai/cmux) ![GitHub stars](https://img.shields.io/github/stars/manaflow-ai/cmux?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/manaflow-ai/cmux?style=flat) - AI コーディングエージェント向けに縦タブと通知を備えた Ghostty ベースの macOS ターミナル。MCP 連携あり。
- [stablyai/orca](https://github.com/stablyai/orca) ![GitHub stars](https://img.shields.io/github/stars/stablyai/orca?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/stablyai/orca?style=flat) - Git worktree をまたいでコーディングエージェント群を動かすワークスペース。MCP サーバー設定に対応。
- [generalaction/emdash](https://github.com/generalaction/emdash) ![GitHub stars](https://img.shields.io/github/stars/generalaction/emdash?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/generalaction/emdash?style=flat) - 複数のコーディングエージェントを並列実行するオープンソースのエージェント開発環境。MCP 連携あり。
- [nimbalyst/nimbalyst](https://github.com/nimbalyst/nimbalyst) ![GitHub stars](https://img.shields.io/github/stars/nimbalyst/nimbalyst?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/nimbalyst/nimbalyst?style=flat) - Claude Code・Codex・OpenCode を並列実行するオープンソースのビジュアルワークスペース。MCP 対応。
- [ParadevAI/Paradev](https://github.com/ParadevAI/Paradev) ![GitHub stars](https://img.shields.io/github/stars/ParadevAI/Paradev?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ParadevAI/Paradev?style=flat) - 複数のコーディングエージェントを並列にオーケストレーションするエージェント IDE（旧 Superset）。ワークスペース管理用の MCP サーバーあり。
- [getpaseo/paseo](https://github.com/getpaseo/paseo) ![GitHub stars](https://img.shields.io/github/stars/getpaseo/paseo?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/getpaseo/paseo?style=flat) - 複数のコーディングエージェントをデスクトップとモバイルからオーケストレーションするツール。MCP サーバーを内蔵。
- [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) ![GitHub stars](https://img.shields.io/github/stars/BloopAI/vibe-kanban?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/BloopAI/vibe-kanban?style=flat) - コーディングエージェントを分離された Git worktree で動かすカンバンボード。MCP サーバーあり。プロジェクトは終了（sunsetting）を発表済み。
- [BillionsBobby/JevRouter](https://github.com/BillionsBobby/JevRouter) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/BillionsBobby/JevRouter?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/BillionsBobby/JevRouter?style=flat) - モデル、ツール、サブエージェントを Jev で振り分けるルーター。MCP アダプター（`serve-mcp`）あり。

## クラウド・DevOps

- [awslabs/mcp](https://github.com/awslabs/mcp) ![GitHub stars](https://img.shields.io/github/stars/awslabs/mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/awslabs/mcp?style=flat) - AWS 向けのオープンソース MCP サーバー群。
- [txn2/kubefwd](https://github.com/txn2/kubefwd) ![GitHub stars](https://img.shields.io/github/stars/txn2/kubefwd?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/txn2/kubefwd?style=flat) - MCP サーバー付きの Kubernetes ポートフォワーディング。
- [skyhook-io/radar](https://github.com/skyhook-io/radar) ![GitHub stars](https://img.shields.io/github/stars/skyhook-io/radar?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/skyhook-io/radar?style=flat) - MCP サーバーを内蔵した Kubernetes UI。
- [patrickchugh/terravision](https://github.com/patrickchugh/terravision) ![GitHub stars](https://img.shields.io/github/stars/patrickchugh/terravision?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/patrickchugh/terravision?style=flat) - MCP 経由で Terraform とクラウドアーキテクチャ図を相互変換。

## 生産性・ナレッジ

- [rusq/slackdump](https://github.com/rusq/slackdump) ![GitHub stars](https://img.shields.io/github/stars/rusq/slackdump?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/rusq/slackdump?style=flat) - Slack データをローカルにエクスポート(MCP サーバー付き)。

## 分野別アプリ

- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) ![GitHub stars](https://img.shields.io/github/stars/koala73/worldmonitor?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/koala73/worldmonitor?style=flat) - リアルタイムのグローバルインテリジェンスダッシュボード。
- [sansan0/TrendRadar](https://github.com/sansan0/TrendRadar) ![GitHub stars](https://img.shields.io/github/stars/sansan0/TrendRadar?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/sansan0/TrendRadar?style=flat) - AI 駆動のトレンド/世論モニター。
- [xpzouying/xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) ![GitHub stars](https://img.shields.io/github/stars/xpzouying/xiaohongshu-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/xpzouying/xiaohongshu-mcp?style=flat) - xiaohongshu.com 用 MCP。
- [liketrek/TREK](https://github.com/liketrek/TREK) ![GitHub stars](https://img.shields.io/github/stars/liketrek/TREK?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/liketrek/TREK?style=flat) - MCP サーバー付きの旅行プランナー。
- [budtmo/docker-android](https://github.com/budtmo/docker-android) ![GitHub stars](https://img.shields.io/github/stars/budtmo/docker-android?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/budtmo/docker-android?style=flat) - MCP サーバー付きの Docker 版 Android。
- [irinabuht12-oss/google-ads-meta-ads-mcp](https://github.com/irinabuht12-oss/google-ads-meta-ads-mcp) ![GitHub stars](https://img.shields.io/github/stars/irinabuht12-oss/google-ads-meta-ads-mcp?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/irinabuht12-oss/google-ads-meta-ads-mcp?style=flat) - Google Ads・Meta Ads・GA4 のホスト型 MCP。
- [crbnos/carbon](https://github.com/crbnos/carbon) ![GitHub stars](https://img.shields.io/github/stars/crbnos/carbon?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/crbnos/carbon?style=flat) - MCP サーバー付きの製造業向け ERP/MES/QMS。
- [relaticle/relaticle](https://github.com/relaticle/relaticle) ![GitHub stars](https://img.shields.io/github/stars/relaticle/relaticle?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/relaticle/relaticle?style=flat) - AI エージェントが読み書きできる CRM。

## 貢献方法
掲載する場合は上記の掲載基準を満たすリポジトリのみとし、スター数も併記してください。
Add a repository only if it meets the inclusion criteria above and include its star count.

## shvyac の awesome リスト

[shvyac](https://github.com/shvyac) が管理しているキュレーションリストの一覧:

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-hpc](https://github.com/shvyac/awesome-hpc) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hpc?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-mcp-ai](https://github.com/shvyac/awesome-mcp-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-mcp-ai?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-quantum](https://github.com/shvyac/awesome-quantum) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-quantum?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
