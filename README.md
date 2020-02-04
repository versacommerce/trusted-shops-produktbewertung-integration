[<img src="versacommerce.png" width="250px" align="right" alt="VersaCommerce.de">](https://www.versacommerce.de/?utm_source=github)
[<img src="trustedshops.png" width="90px" align="right" alt="business.trustedshops.de">](https://business.trustedshops.de/?utm_source=www.versacommerce.de)

[VersaCommerce] [integration] [javascript] [TrustedShopsProduktbewertung]

# Trusted Shops Produktbewertung Integration for VersaCommerce

## Trusted Shops Produktbewertung
This Integration makes it possible to show customer reviews of products and will automatically ask customers for a review after their order.

## VersaCommerce

[VersaCommerce](https://www.versacommerce.de/?utm_source=github) is a popular european e-commerce plattform that allows to build and manage online stores and digital sales channels.

## Installation
This integration is pre-installed with every VersaCommerce store. To enable it, go to your store settings and to Integrations. You can configure and enable it with just a few clicks.

## Files

### head.liquid
This file is empty because it's not needed for this integration.

### body.liquid
All code for this integration takes places in body.liquid, which is injected inside ```<body>...</body>``` of the rendered html document.

### email.liquid
This file is empty because it's not needed for this integration.

## Configuration options for this integration.
| Label                       | Key                | Default Value            | Validates presence? |
| --------------------------- | ------------------ | :----------------------: | :-----------------: |
| Ihre Trusted Shops ID       | tsid               |                          |     √               |
| Rahmenfarbe                 | borderColor        | #0DBEDC                  |                     |
| Hintergrundfarbe            | backgroundColor    | #ffffff                  |                     |
| Sternfarbe                  | starColor          | #FFDC0F                  |                     |
| Rahmenfarbe Kommentare      | commentBorderColor | #dad9d5                  |                     |
| Kommentarpfeil verbergen    | commentHideArrow   | false                    |                     |
| Sterngröße                  | starSize           | 15px                     |                     |
| Zusammenfassung             | ratingSummary      | false                    |                     |
| Leere Bewertung verbergen   | hideEmptySticker   | false                    |                     |
| Text                        | introtext          | Was unsere Kunden sagen: |                     |
| Schriftgröße                | fontSize           | 12                       |                     |
| Sterne anzeigen             | showRating         | true                     |                     |
| Zu den Bewertungen scrollen | scrollToReviews    | false                    |                     |
| Platzhalter ermöglichen     | enablePlaceholder  | false                    |                     |


##  Customization
* Create a developer account at [https://www.versacommerce.de/partner](https://www.versacommerce.de/partner?utm_source=github).
* Create a free developer store.
* Create an integration in your developer area.

## License

```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|

The MIT License (MIT)

Copyright (c) 2014 VersaCommerce GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
