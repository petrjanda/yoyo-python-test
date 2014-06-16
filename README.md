Yoyo Test
=========

You are building a simple Python/Django-based loyalty programme for a retail shop:

- the shop sells two products: a widget and a gizmo
- for each widget you buy, you earn one loyalty stamp
- for each gizmo you buy, you do not earn a loyalty stamp
- you can buy multiple products in a single transaction
- if you earn ten loyalty stamps you automatically earn a voucher for a free widget
- when you earn a voucher for a free widget, your widget loyalty stamps balance resets
- you can only use a voucher once

Create a set of REST APIs that allow you to:
- see how many stamps a customer has
- see how many vouchers a customer has
- add stamps to a customer
- add vouchers to a customer
- mark a voucher as redeemed
- BONUS: see a customers transaction history (purchases, stamps, vouchers)

It is expected that you:
- create your own data models and stub data
- write unit tests
- fork this repository to get started
- commit often and push your code to GitHub
- if for some reason you do not want to push to GitHub, use BitBucket or some other service, and invite us to view
- deploy on Heroku

BONUS: If you want to show us more, build an additional feature that extends the loyalty programme further.
