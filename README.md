# xxxxholica

余計な手間や迷いをなくすことを意識して、身の回りのツールから遊べる作品まで幅広く開発しています。

## 受賞

Web×IoT メイカーズチャレンジ PLUS in 鳥取

- 2025年度 特別賞 — Safekitty（メイン実装・タスク分担）
- 2024年度 特別賞 — AgriCare Watch（API連携の実装）

[2025年 作品](https://webiotmakers.github.io/gallery/?category=%E3%82%B3%E3%83%9F%E3%83%A5%E3%83%8B%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3&location=%E9%B3%A5%E5%8F%96&year=2025) / [2025年 開催報告](https://webiotmakers.github.io/static/docs/2025/tottori-report.pdf) / [2024年 作品](https://webiotmakers.github.io/gallery/?category=%E9%AB%98%E9%BD%A2%E8%80%85%E3%83%BB%E4%BB%8B%E8%AD%B7&location=%E9%B3%A5%E5%8F%96&year=2024) / [2024年 開催報告](https://webiotmakers.github.io/static/docs/2024/tottori-report.pdf)

## 公開作品

**[gamecenter](https://github.com/xxxxholica/gamecenter)** — TypeScriptとThree.jsによる自作ブラウザアーケードゲーム集

- 規模: 学祭展示3日間で延べ723回起動
- 担当: 全体設計・システム基盤・ゲーム開発
- 機能①: レバーとボタンのみで回遊・自動復帰できる筐体向け共通UI
- 機能②: 死因・死亡座標・軽量リプレイを記録するテレメトリ基盤
- 設計判断: 1日目の離脱ログを根拠に6作品を改修し、翌日の滞在時間を改善

**[kikimimi](https://github.com/xxxxholica/kikimimi)** — Google Cloud TTSとDiscord APIを用いた読み上げボット

- 運用開始: 2025年3月
- 規模: 利用者約20人
- 機能①: ボイスチャンネルの入退室に連動した自動接続・切断
- 機能②: 読み上げと音楽再生の同時利用
- 設計判断: ローカルでの音声生成から、応答速度を優先してGoogle Cloud TTSへ移行
- 安全策: 無料利用枠を超えない自動停止ガード
