# 🌱 Digital Brain Garden

**サイト：** https://nya-sci.github.io/digital_brain_garden/

Nya-Sci の頭の中を、ときに雑多に、自由気ままにアウトプットしていく「デジタル脳苑」です。
完成した記事集ではなく、メモの延長として育っていく有機的なポートフォリオを目指しています。

## 主な区画

- **研究** — 継続して取り組んでいる研究テーマ（例：NGS 解析処理の FPGA によるハードウェアアクセラレーション）
- **tale** — 研究とは別に、興味の赴くままに学んだこと・考えたことの記録（勉強ノート、AI 壁打ちなど）
- **ものつくり** — 自作したいモノ・自作しているモノの構想と設計ログ

## 構成

| 役割 | 使っているもの |
| --- | --- |
| 執筆 | [Obsidian](https://obsidian.md/)（`content/` が Vault） |
| サイト生成 | [Quartz v5](https://quartz.jzhao.xyz/)（設定：`quartz.config.yaml`） |
| 公開 | GitHub Pages（`v5` ブランチへの push で `.github/workflows/deploy.yml` が自動デプロイ） |

ローカルでのプレビュー：

```bash
npx quartz build --serve
```

## 注意事項

- 内容は個人の学習・研究記録であり、正確性・完全性を保証するものではありません。
- 所属組織や特定の製品・企業とは一切関係のない、個人の見解です。
- 一部の記事は、AI との対話を活用して作成・整理しています。

## 連絡先

- X: [@Nya_Sci](https://x.com/Nya_Sci)
- GitHub: [Nya-Sci](https://github.com/Nya-Sci)

## Credits

This site is built with [Quartz](https://github.com/jackyzha0/quartz) by jackyzha0, licensed under the MIT License (see `LICENSE.txt`).
