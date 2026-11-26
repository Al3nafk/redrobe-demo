# ReDrobe — Campus Clothing Rental Demo

A clickable prototype for **ReDrobe**, a clothing rental studio at UOW Malaysia Glenmarie ("Wear more. Buy less."), built for the KDET1013N Technopreneurship project.

The demo has two sides that share the same data:

- **Customer app:** browse outfits by occasion, choose a size, pickup date and rental length, add accessories, pay the rental fee and refundable deposit, track the rental from pickup to return, and join ReDrobe Monthly.
- **Staff dashboard:** an order queue (to prepare, ready to collect, out on rental, returned to inspect), late returns and reminders, damage reports, inventory with repair status, and a daily summary.

All outfits, prices and orders are sample data. No real payment is taken and nothing is saved between visits.

## Run it

It is a single self-contained file. Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

On a wide screen the phone and the staff dashboard sit side by side. On a phone, use the switch at the top to move between them.

## Team

Zheng Chyi (CEO) · Swan Nee (COO) · Bryan (CTO and CMFO)
