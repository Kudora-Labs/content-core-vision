# content-core-vision
This repository holds the foundational documents that define Kudora’s vision, values, intent, and guiding principles. It serves as a shared reference for all community members (new and old) to understand the “why” behind the project. Contributions are welcome through pull requests. The vision grows with us.

## How to Contribute to the Whitepaper

The whitepaper is organized into multiple sections, each as a separate Markdown file in the `sections/` folder. The order and inclusion of sections is managed by the `whitepaper.json` manifest file.

### Editing Sections
- Each section is a Markdown file (e.g. `introduction.md`, `vision.md`).
- To edit a section, open its file and update the content using Markdown syntax.
- Do not change the filename unless you also update `whitepaper.json`.

### Structure and Formatting
- Use headings to organize content:
  - `#` (H1) for the main section title (should be the first line).
  - `##` (H2) for subsections within the section.
  - `###` (H3) for sub-subsections if needed.
- **Maximum depth:** Only use up to three heading levels (H1, H2, H3). Do not use H4 or deeper.
- Keep content clear and concise. Use lists, quotes, and code blocks as needed.

### Manifest File (`whitepaper.json`)
- The manifest lists all section files in order. Example:
  ```json
  {
    "sections": [
      "introduction.md",
      "vision.md",
      "problems.md"
      // ...
    ]
  }
  ```
- To add or remove a section, update both the manifest and the `sections/` folder.

### Rendering and Navigation
- The website loads all sections in order and generates navigation from headings.
- H1 and H2 headings become main navigation items; H3 headings appear as sub-items.
- Use descriptive headings for clarity and easy navigation.

---
For questions or suggestions, open an issue or pull request.
