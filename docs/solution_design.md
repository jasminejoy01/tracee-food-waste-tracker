# Solution Design

## User Flow
1. Capture grocery receipt.
2. OCR extracts items, prices, and purchase date.
3. User assigns storage location.
4. System estimates best-before date based on item + storage.
5. Notifications sent when items near best-before.
6. Outcomes logged: used, donated, repurposed, discarded.

## Core Components
- **OCR Service**: Tesseract, Google Vision API
- **Storage Mapping Rules**: JSON or database table mapping `(item, storage)` to `days_until_expiry`
- **Notification Engine**: Cron/scheduler to send reminders
- **Analytics Dashboard**: Waste %, $ lost, most-frequently wasted items
