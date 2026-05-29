# AHU Filter Intelligence Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview

**AHU Filter Intelligence Assistant** is a product-concept and prompt-architecture repository for an assistant that helps field technicians, facility managers and purchasers identify air-handling-unit filters more reliably.

The project addresses a practical operational problem: AHU and ventilation filter data is often incomplete, inconsistent or spread across manuals, labels and supplier catalogues. The assistant is designed to structure that uncertainty, ask only the most important follow-up questions, and separate confirmed facts from assumptions.

> **Status:** product-concept and prompt-architecture baseline.  
> This is not yet a production application, procurement system or verified manufacturer database.

## Intended capabilities

- **Filter identification:** support brand/model, unit details, dimensions or existing filter markings.
- **Compatibility checking:** distinguish supply/extract stages, pre-filters and final filters.
- **OEM and aftermarket support:** present original and compatible alternatives when data is available.
- **Confidence scoring:** make uncertainty visible before ordering.
- **Bilingual workflow:** support Danish and English usage.
- **Field-ready flow:** keep questions short and operationally useful.
- **Standards awareness:** reference filter-classification concepts such as ISO 16890 where relevant.

## How it works conceptually

Users provide whatever information is available about their unit:

- brand,
- model,
- serial number,
- filter dimensions,
- photos or markings,
- existing supplier notes.

The assistant should then return a structured recommendation that separates:

1. confirmed details,
2. probable matches,
3. assumptions,
4. verification steps before ordering.

## Safety and reliability boundaries

This repository is intentionally conservative:

- It should not claim certainty when manufacturer data is incomplete.
- It should not recommend ordering when dimensions or class compatibility are unclear.
- It should clearly mark assumptions and confidence levels.
- It should encourage manual verification before purchase when the match is uncertain.
- It does not currently include a live product database or supplier integration.

## Future work

- Integrate verified manufacturer data or internal ERP exports.
- Add a structured filter-data schema.
- Add test fixtures for assistant output quality.
- Expand multilingual support beyond Danish and English.
- Add a camera/label-scanning workflow for a future mobile interface.
- Add supplier and ordering integrations only after confidence and verification rules are well defined.

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.
