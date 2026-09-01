# Contributing to the Ungur Group Website

Contributions are strictly limited to members of the group. Members of the organization are given access to the repository and should make changes directly to the `main` branch. Contributions from external parties are not welcome, but feature requests can be made via issues.

## Workflow
1. Pull the latest changes from the `main` branch.
2. Make your changes directly on the `main` branch.
3. Push your changes.

## Adding Publications
We maintain a strict directory structure for publications.

1. **Directory:** Place files in `assets/publications/YYYY/` where `YYYY` is the year of publication.
2. **Naming Convention:** Use the format `Author_Journal_Year.ext` (e.g., `Petit_DT_2007.pdf`).
3. **Supporting Files:**
   - Always include the main PDF.
   - Include `_SI.pdf` for Supporting Information if available.
   - Include `.cif` or `.png` files if they are part of the publication assets.

## Updating Team Members
To update the team list, edit the `_data/people.yaml` file. Please ensure you follow the existing YAML structure.

## Styling
- Styles are located in `assets/css/`.
- We use SCSS. Please ensure any new styles are added to the appropriate file (e.g., `_footer.scss`, `_header.scss`, or `style.scss`).
