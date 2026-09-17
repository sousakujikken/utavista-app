# UTAVISTA

UTAVISTA（うたびすた）は、歌詞アニメーション動画を制作するための macOS 向けデスクトップアプリケーションです。
カラオケ風のテキストアニメーションをテンプレートから組み立て、シェーダーや背景動画と合成して、高品質な動画として書き出せます。

このリポジトリは **ビルド済みアプリの配布用** です。ソースコードは含まれていません。
v1（GPLv3）は [sousakujikken/utavista](https://github.com/sousakujikken/utavista) にあり、本リポジトリの v2 とはライセンスが異なります。

## ダウンロード

最新版は [Releases](https://github.com/sousakujikken/utavista-app/releases) から `.dmg` を取得してください。

> 現在は **ベータ版** です。仕様や操作方法は予告なく変わることがあります。重要なプロジェクトは定期的にバックアップしてください。

## 動作環境

| 項目 | 要件 |
|---|---|
| OS | macOS 13 Ventura 以降 |
| CPU | Apple Silicon（arm64） |
| GPU | WebGPU が利用できること（Apple Silicon 搭載 Mac は対応） |

Intel Mac 向けビルドは現時点では提供していません。

## インストール

1. Releases から `UTAVISTA-<バージョン>-arm64.dmg` をダウンロードします。
2. dmg を開き、`UTAVISTA.app` を `アプリケーション` フォルダにドラッグします。
3. 初回起動時に macOS の確認ダイアログが表示されたら「開く」を選びます。

アプリは Apple Developer ID で署名・公証されています。

## 主な機能

- 歌詞トラック、タイトル、フィルター、シェーダー、背景動画の 5 種類のトラックを重ねて構成
- テンプレートによる歌詞アニメーション（単語単位のスライド、黒帯スワイプ、パーティクルなど）
- WGSL シェーダーによるエフェクト
- H.264 / HEVC での動画書き出し
- 任意機能: ボーカル音声からの歌詞タイミング自動解析（[utalign](https://github.com/sousakujikken/utalign)、アプリ内からインストール可能）
- 任意機能: Claude Code / Codex CLI を使ったテンプレート生成支援（各 CLI と契約は利用者側で用意）

## 不具合報告・質問

[Issues](https://github.com/sousakujikken/utavista-app/issues) で受け付けています。
不具合の場合は、macOS のバージョン、アプリのバージョン、再現手順を添えてください。

## ライセンスとプライバシー

- アプリの利用条件: [LICENSE](LICENSE)
- プライバシー通知: [PRIVACY.md](PRIVACY.md)
- 同梱する第三者コンポーネント: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)

ビルド済みアプリは無償で利用できます。ソースコードは別途の利用許諾に基づいて提供されるもので、本リポジトリの対象外です。
