# HRGrow — Social Media Intelligence

HRGrow adalah prototype real-project foundation untuk bisnis HR Tech & Payroll. Fokusnya menghubungkan social media performance ke content intelligence, lead scoring, funnel, recommendations, calendar, dan reporting.

## Modul
- Overview & KPI
- Content Intelligence
- Content Pillar Intelligence
- Lead Intelligence
- Marketing Funnel
- Recommendations
- Content Calendar
- CSV Reporting
- Workspace Settings

## Arsitektur saat ini
Frontend statis HTML/CSS/JS dengan data simulasi di `app.js`. Tidak membutuhkan build step. Buka `index.html` untuk menjalankan aplikasi.

## Roadmap production
1. Ganti data array dengan REST API.
2. Tambahkan database PostgreSQL/Supabase.
3. Tambahkan autentikasi dan role Admin, Marketing, Sales.
4. Integrasikan API resmi platform yang tersedia untuk akun bisnis.
5. Buat ingestion job berkala dan tabel historical metrics.
6. Tambahkan model scoring/recommendation yang dapat diaudit.
7. Tambahkan validation, rate limits, secrets management, audit log, error monitoring, dan tests.

## Rumus inti
- Engagement Rate = Engagement / Reach × 100
- Funnel Conversion = Stage berikutnya / Stage saat ini × 100
- Content Score = weighted combination of engagement, lead generation, and business relevance.

## Data
Angka pada versi ini merupakan data simulasi untuk demonstrasi/prototyping, bukan data platform aktual.
