# Flea Price Watch

フリマ相場・値下げ通知

## Repository

Recommended repository name: `flea-price-watch`

## Domain candidates

First candidate: `fleaprice.jp`

Other candidates:

- `fleaprice.jp`
- `furimawatch.jp`
- `neagewatch.jp`
- `marketalert.jp`

## Concept

フリマ相場、値下げ、新着、売れ筋を通知し、有料ウォッチ、分析ツール、アフィリエイトへつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 有料ウォッチ
- 分析ツール
- affiliate
- 広告
- リード販売

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
