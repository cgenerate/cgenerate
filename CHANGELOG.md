# Cgenerate Changelog

Notable public product improvements are documented in this file.

## August 2026

### Added

- Google Sheets recipient import
- PNG certificate export
- Quick Generate three-step workflow
- Sample certificate template
- Sample CSV and Excel (`.xlsx`) recipient files
- Live certificate preview
- Recipient-name controls for font, size, spacing, color, alignment, and placement
- Public About, Contact, Privacy, and Terms pages
- Certificate creation, bulk generation, and template-preparation guides

### Improved

- Bulk certificate generation for up to 1,000 recipients per file
- Validation for required columns, missing IDs, empty names, duplicate IDs, long values, and row limits
- Support for PNG, JPG, JPEG, and first-page PDF certificate templates
- Template validation for dimensions up to 8,000 pixels per side and 16 megapixels
- PDF, JPG, and PNG certificate export
- Safe recipient-based filenames
- ZIP package downloads for bulk certificates
- Browser-based certificate processing and privacy information

### Data Import

Bulk Generate supports recipient information from:

- CSV files
- Excel (`.xlsx`) files
- Google Sheets

Recipient data must contain the following columns:

- `ID`
- `Full Name`

### Privacy

Certificate templates, recipient information, previews, and generated files are processed inside the browser session. No account is required to use the certificate generators.
