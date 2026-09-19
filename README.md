# गीता स्वाध्याय · Gita Swadhyay

Self-study and teaching work on the Shrimad Bhagavad Gita.
श्रीमद्भगवद्गीतेचा स्वाध्याय: अभ्यास साधने आणि उपक्रम.

**Live site:** https://gita-swadhyay.link

## दोन मार्ग · Two paths

| Programme | What it is | Link |
|---|---|---|
| **CCK गीता स्वाध्याय** (CCK Gita Swadhyay) | Digital study tool for the study group: chapter-wise concepts, mind maps (मानस-चित्रे), verse references and the debate tool (वादसभा). Chapters 1–9 (अध्याय १ ते ९), with Chapter 10 (विभूतियोग) as a standalone page. | https://gita-swadhyay.link/cck.html |
| **लोकमान्य गीताबोध** (Lokmanya Gitabodh) | A programme by श्री गणेशोत्सव मंडळ, लोकमान्य आळी, ठाणे for member parents and children, based on Lokmanya Tilak's Gitarahasya. Online sessions, Google Classroom, enrolment form. | https://gita-swadhyay.link/lokmanya-ali/ |

## Repository layout

```
├── index.html                  Landing page: choose CCK or Lokmanya Gitabodh
├── cck.html                    CCK गीता स्वाध्याय: main study tool (chapters 1–9)
├── adhyay-10-vibhutiyog.html   Chapter 10 page
├── vadasabha.html              Digital debate tool (वादसभा)
├── data/                       Data used by the study pages
├── images/                     Images used by the study pages
├── lokmanya-ali/               लोकमान्य गीताबोध website
│   ├── index.html              Programme information and enrolment
│   ├── patrak.html             Printable A4 pamphlet (with QR code)
│   ├── config.js               Site settings (registration endpoint, contact)
│   └── assets/                 Photographs and banner
├── CNAME                       Custom domain (gita-swadhyay.link)
└── README.md
```

## Hosting

- Static site on **GitHub Pages**, served at the custom domain `gita-swadhyay.link` (DNS on Cloudflare).
- Enrolment for लोकमान्य गीताबोध is stored in a private Google Sheet through a Google Apps Script web app. The script and the Sheet are not part of this repository.

## Copyright Notice

© 2026 Vivek Bhaskar Sathe. All rights reserved.

This repository contains proprietary educational materials, custom analysis, and layout designs.

* Access to this material is granted strictly for personal educational purposes.
* No part of this repository (text, analysis, or source code) may be reproduced, distributed, or transmitted in any form or by any means without prior written permission from the copyright owner.
* The name, banner and photographs of श्री गणेशोत्सव मंडळ, लोकमान्य आळी, ठाणे in `lokmanya-ali/assets/` belong to their respective owners and are used here only for the लोकमान्य गीताबोध programme.
