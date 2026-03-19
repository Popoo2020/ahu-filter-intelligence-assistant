# ahu-filter-intelligence-assistant

## Overview

This project provides a specialized assistant built on large language models to help field technicians, facility managers and purchasers identify the correct filters for air handling units (AHUs) and ventilation units. It addresses the common problem of missing or inconsistent filter data by combining available documentation, standards and best practices into a structured decision-support tool.

## Features

- **Filter identification**: Quickly identify the correct OEM or compatible aftermarket filters for a given AHU or ventilation unit using brand/model, unit details, dimensions or existing filter markings.
- **Compatibility checking**: Distinguish between supply and extract stages, pre filters and final filters, and confirm dimensional and class compatibility.
- **OEM and aftermarket support**: Provide both original filters and high‑quality compatible replacements where available, with reliability scores.
- **Confidence & reliability scoring**: Each recommendation includes confidence levels and reliability scores so users can judge when manual verification is required.
- **Bilingual support**: Handles input and produces output in Danish and English.
- **Field-ready workflows**: Designed for use on site or in fast‑paced service environments with minimal questions and clear next steps.
- **Transparent standards**: Uses current filter classification standards (e.g. ISO 16890) and clearly distinguishes confirmed data from assumptions.
- **Future extensibility**: Built with the intention to expand into a mobile app and to integrate private knowledge bases.

## How It Works

Users provide whatever information is available about their unit—brand, model, serial number, size, filter dimensions or markings. The assistant cross‑references this input against accessible documentation and known configurations to narrow down the correct filter. It will ask for only the most critical missing detail and then provide a structured recommendation that separates confirmed facts from probable matches and assumptions. When data is incomplete, it suggests simple verification steps before ordering.

## Usage

This assistant can be used inside ChatGPT or integrated into custom workflows:

1. Provide the unit brand and model (e.g. “Systemair Topvex TR09”) or details such as filter dimensions.
2. Review the structured filter recommendation, confidence rating and notes.
3. Confirm dimensions or other key details when prompted before placing an order.
4. Use the field decision guidance (“Can order now”, “Needs one check”, etc.) to plan the next step.

A future mobile app will make it even easier to scan labels, select units, and retrieve filter information on site.

## Future Work

- Integrate with manufacturer data or internal ERP exports to improve exact model‑to‑filter mapping.
- Expand the multilingual support beyond Danish and English.
- Add a comprehensive knowledge base of filter catalogs and manuals.
- Develop a dedicated mobile application with camera scanning and offline capabilities.
- Offer automated ordering options once the correct filter is confirmed.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is currently unlicensed. You may use the code and documentation for reference or inspiration but please contact the author before commercial use.
