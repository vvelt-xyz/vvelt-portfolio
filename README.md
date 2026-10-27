# vvelt-portfolio

[vvelt.xyz](https://vvelt.xyz) / **株式会社WELT** の公開 Web・システム・ポートフォリオ・ハブ。

本番プロダクトのリポジトリは private のままです。ここに載るのは、切り出してリビルドした **ショーケース** への目次です。

型の正本（組織内）: `00_vvelt-development` の `docs/portfolio.md`  
リビルド規約: 同 `docs/portfolio-rebuild.md`（本番相当・アーカイブして新規・デモクラウド統制）  
カタログ: 同 `docs/portfolio-catalog.md`  
Skill: `portfolio-showcase`

## Showcases

| 名前 | GitHub | Demo | 証明すること |
|---|---|---|---|
| WELT POS | [portfolio-pos](https://github.com/vvelt-xyz/portfolio-pos) | [vvelt-portfolio-pos.vercel.app](https://vvelt-portfolio-pos.vercel.app) | フロア起点の案内→注文→提供→会計（税・端数・複数端末同期）を Auth 付きで本番相当に実装できる |

旧 `portfolio-pos-lite`（薄い SPA）は 2026-10-27 にアーカイブ済み。ハブからは外す。

## 見方

1. Demo で動作確認  
2. GitHub でコード・`docs/pitch.md`・差分表を確認  
3. 本番案件のソースそのものではない点に注意  

## 追加方針

新しいショーケースは `portfolio-<slug>` の public リポとして起票し、本 README と母艦カタログを同一作業で更新する。Skill `portfolio-showcase` の手順に従う（不合格葉は継ぎ足さずアーカイブ→新規）。
