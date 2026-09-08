## Tech Stack

- Next.js
- Tailwind CSS
- LINE Messaging API
- Google Apps Script
- Google Sheets
- Vercel

## Architecture

```mermaid
graph TD
    A[Patient / Frontline Nurse] -->|Next.js| B[Web Application]
    B -->|API Request| C[Google Apps Script]
    C -->|Store Data| D[(Google Sheets)]
    C -->|Send Notification| E[LINE Messaging API]
```

## Real-World Usage

Currently used by [Kamphaeng Phet City Municipality](https://www.kppmu.go.th/news-detail?hd=1&id=124000).
