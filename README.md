# CafePOS

POS web app starter for cafe operations.

## Scope
- Cashier POS: product catalog, cart, order notes, discounts, taxes, payment methods
- Customer QR ordering foundation
- Kitchen/bar order workflow
- Inventory & stock movement foundation
- Staff roles and permissions foundation
- Receipt customization with store name/logo
- Sales dashboard and reporting foundation
- Table/order management foundation

## Suggested stack
- Next.js + TypeScript
- Tailwind CSS
- PostgreSQL + Prisma
- Zod
- Auth.js / role-based access
- PWA support
- ESC/POS-ready receipt printing adapter

## Domain flow
Customer QR / Cashier -> Order -> Payment -> Kitchen/Bar tickets -> Stock deduction -> Receipt -> Reports

## MVP priorities
1. Products/categories
2. POS checkout
3. Order status / kitchen tickets
4. QR customer order
5. Receipt
6. Daily sales report
7. Inventory
8. Users/roles

This repository currently contains the product specification and architecture seed.