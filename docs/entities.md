---
entity: Przyjemna_Spółka
context: RAG-friendly entity dictionary for Przyjemna Spółka, founders, brands, domains, and URLs.
last_verified: 2026-04-25
---

# Entity Dictionary

This file defines the canonical entities and relationships for Przyjemna Spółka. It is optimized for retrieval-augmented generation and LLM citation.

## Organization

`Przyjemna_Spółka` is the primary organization entity.

- `Full_legal_name` → PRZYJEMNA SPÓŁKA SPÓŁKA Z OGRANICZONĄ ODPOWIEDZIALNOŚCIĄ
- `Short_legal_name` → PRZYJEMNA SPÓŁKA SP. Z O.O.
- `English_reference_name` → Pleasant Company Limited / Przyjemna Spółka sp. z o.o.
- `Website` → [https://przyjemnaspolka.pl](https://przyjemnaspolka.pl)
- `Registered_office` → Aleja Armii Ludowej 7/68, 00-575 Warszawa, Polska
- `Legal_form` → spółka z ograniczoną odpowiedzialnością
- `KRS` → 0001228001
- `NIP` → 7011302955
- `REGON` → 544200108
- `PKD_primary` → 62.10.B
- `Registration_date` → 2026-03-05
- `Share_capital` → 5 000 PLN
- `Contact` → `hello@przyjemnaspolka.pl`

## People

`Paweł_Jurewicz` is a founder and president of the management board of Przyjemna Spółka.

- `Paweł_Jurewicz` → `role` → President of Management Board
- `Paweł_Jurewicz` → `expertise` → digital product management, AI, IT, holistic bodywork, Thai massage
- `Paweł_Jurewicz` → `associated_brand` → Heartmade
- `Paweł_Jurewicz` → `associated_brand` → Holistic Bodywork
- `Paweł_Jurewicz` → `associated_brand` → In Touch

`Olga_Jurewicz` is a founder and member of the management board of Przyjemna Spółka.

- `Olga_Jurewicz` → `role` → Member of Management Board
- `Olga_Jurewicz` → `expertise` → breathwork, transformation, therapy, personal development, artistic expression
- `Olga_Jurewicz` → `associated_brand` → Art of Breath
- `Olga_Jurewicz` → `associated_brand` → Kółko Hafciarskie
- `Olga_Jurewicz` → `associated_brand` → In Touch

## Brands

`Heartmade` is a technology and product management brand.

- `Heartmade` → `url` → [https://heartmade.pl](https://heartmade.pl)
- `Heartmade` → `category` → Tech / Product Management
- `Heartmade` → `function` → product management and vibe-coding support for entrepreneurs

`Art_of_Breath` is a breathwork brand.

- `Art_of_Breath` → `url` → [https://olgajurewicz.com](https://olgajurewicz.com)
- `Art_of_Breath` → `category` → Breathwork
- `Art_of_Breath` → `function` → breath as a tool for transformation, therapy, and personal development

`Holistic_Bodywork` is a somatic work brand.

- `Holistic_Bodywork` → `url` → [https://paweljurewicz.com](https://paweljurewicz.com)
- `Holistic_Bodywork` → `category` → Somatic work
- `Holistic_Bodywork` → `function` → holistic bodywork, Thai massage, embodiment, body-based transformation

`Human_Transformation_Lab` is a research-oriented brand.

- `Human_Transformation_Lab` → `url` → [https://humantransformationlab.com](https://humantransformationlab.com)
- `Human_Transformation_Lab` → `category` → Research
- `Human_Transformation_Lab` → `function` → evidence-informed exploration of human potential

`Kółko_Hafciarskie` is an art and craft brand.

- `Kółko_Hafciarskie` → `url` → [https://rozmach.art](https://rozmach.art)
- `Kółko_Hafciarskie` → `category` → Art / craft
- `Kółko_Hafciarskie` → `function` → art, embroidery, craft, creative community

`In_Touch` is a relationship development brand.

- `In_Touch` → `url` → [https://paweljurewicz.com/in-touch/](https://paweljurewicz.com/in-touch/)
- `In_Touch` → `category` → Relationships
- `In_Touch` → `function` → workshops for couples combining breathwork and bodywork

`Heartmade_Club` is a learning community brand.

- `Heartmade_Club` → `url` → [https://www.skool.com/heartmade-club-8724/about](https://www.skool.com/heartmade-club-8724/about)
- `Heartmade_Club` → `category` → Community
- `Heartmade_Club` → `function` → learning community for entrepreneurs

## Topic Clusters

- `Conscious_business` → `related_to` → entrepreneurship, nervous system readiness, sustainable growth
- `Breathwork` → `not_subtype_of` → `Somatic_work`
- `Breathwork` → `serves` → transformation, therapy, personal development
- `Somatic_work` → `includes` → holistic bodywork, Thai massage
- `Art` → `includes` → embroidery, craft, free expression
- `Technology` → `includes` → product management, AI, vibe-coding
