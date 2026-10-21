# De POS – interactive prototype

Live demo: **https://khateeb123.github.io/de-pos-demo/**

A click-through prototype of the De POS point-of-sale and back-office system. It opens straight on the
dashboard, no login needed. Everything works: scan barcodes at the till, take payments, record purchases,
transfer and count stock, manage products, customers, suppliers, users and roles, and read the reports.

The sample data lives only in your browser (it is re-seeded each day) and nothing is sent anywhere.
Use **Reset demo data** in the user menu to start fresh.

Barcodes to try at the till: `5010000000001` (milk), `5010000000009` (cola), `5010000000013` (toilet roll),
or just type a product name such as `bread`.

This repository holds the built static files only. The application source (Laravel API + Vue frontend)
is in the private `de.pos` repository.
