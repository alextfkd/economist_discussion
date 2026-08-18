# Session #003 真実機械の裁定問題

復元品質：A（討議録の相当部分を逐語回収）

## 記事
- タイトル：予測市場と契約決済の困難（Kalshi）
- 号・セクション：2026年7月号
- チャットURL：https://claude.ai/chat/0744c2c8-0858-49d4-82ea-da78f3eeddac
- 日付：2026-07-29

## 争点と応酬
### 争点1：予測市場価格は人類の最良推定か
### 争点2：成長は情報インフラ需要か規制裁定によるギャンブルか
- 解決：後者。Kalshi取引量の約85%・手数料収入の89%がスポーツ由来
### 争点3：最も信頼できる裁定アーキテクチャは何か
- 解決：公開判例を持つ独立中立裁定者が当事者投票型（UMA等）に優る。ただし中央集権委員会もISDAの数十年の統治闘争が示す通り恒久的な問題を抱える
- 補足：最上位でも曖昧性は消えず管理されるのみ。決済可能性と問いの価値のトレードオフ
### 争点4：LLMは裁定をスケールできるか
- 解決（双方更新）：LLMは裁定点（ex post）ではなく上流（ex ante：曖昧性リンター、判例矛盾検出、定義書QA）に置くべき。「判断のスケール」ではなく「判断が不要になる設計のスケール」
- Claudeの反対根拠：(a)無限オフラインクエリによる敵対的最適化 (b)一貫性と攻撃耐性の同時不成立 (c)automation bias (d)効率化益が曖昧契約の増産に食われるJevons的帰結

## データ
- Kalshi累計取引量の約85%がスポーツ、2025年手数料収入の89%（$234.6M/$263.5M）— https://www.sgieurope.com/technology/kalshi-booms-on-sports/121847.article
- 2024年7月以降のKalshi総取引量の80%がスポーツ（Pew）— https://www.pewresearch.org/short-reads/2026/05/27/trading-volume-on-prediction-markets-has-soared-in-recent-months/
- W杯期間、予測市場が米合法スポーツ賭博量の約27% — https://bettorsinsider.com/news/2026/07/28/prediction-markets-capture-27-of-us-sports-betting-during-world-cup/
- Theo事件：匿名複数口座で$30M超投入、約$85M獲得 — https://www.cbsnews.com/news/french-whale-made-over-80-million-on-polymarket-betting-on-trump-election-win-60-minutes/
- GJ加重予測調査はICPMより34.7%正確 — https://forum.effectivealtruism.org/posts/JQaeuuWiFfXCGDKNp/comparing-superforecasting-and-the-intelligence-community
- ForecastBench：2026年7月、複数AIがスーパーフォーキャスターと統計的に区別不能 — https://forecastingresearch.substack.com/p/ai-models-have-likely-reached-parity（GJ側反論 https://goodjudgment.substack.com/p/what-superforecasters-actually-said）
- ISDA DC批判・Hovnanian事件 — https://www.promarket.org/2024/07/09/determination-committees-deciding-on-credit-event-decisions-should-bolster-independence/

## 未決の問い
- [#003] 較正実績加重はスケールするか（AIフォーキャスター群は市場という集約器を代替しうるか）— open
- [#003] 精密性と関連性のフロンティアはex ante設計でどこまで押し広げられるか — open
- [#003] 予測市場のスポーツ賭博化の公衆衛生コストは便益と比較可能な形で測れるか — open
- [#003] LLM裁定への敵対的最適化は実際に観測されるか — open

## 過去セッションとの接続
実質的な討議録の原点（当時は検索失敗により初回と誤認）。

## 方法論上の確定事項
- 「更新」は勝敗ではなく成果物として数える（adversarial collaboration）
- warrant攻撃の語彙化（本セッションで勝俣が実演）
- Claudeは常に全力で議論し、セッション末に最弱の未攻撃論点を自己開示する方式を採択
