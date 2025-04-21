# Wye Make Documentation

Welcome to the Wye Make documentation repository. This repository hosts the source files for our comprehensive documentation, powered by MkDocs. The published site is available at [https://docs.wyemake.co.uk/](https://docs.wyemake.co.uk/).

## Contents

- `docs/` – Markdown source files for each section of the documentation
- `mkdocs.yml` – Configuration for MkDocs, defining navigation, theme and plugins
- `requirements.txt` – Python dependencies

## Getting Started

### Prerequisites

- Python 3.7 or later
- pip
- MkDocs (`pip install mkdocs`)

### Installation

1. Clone the repository (using the **tools** branch):
   ```bash
   git clone --branch tools https://github.com/wyemake/docs.git
   ```
2. Change into the repository directory:
   ```bash
   cd docs
   ```
3. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/macOS
   .venv\Scripts\activate    # Windows
   ```
4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Serving Locally

To preview the documentation locally, run:
```bash
mkdocs serve
```
Then open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

### Building the Site

To build the static site files into the `site/` directory, run:
```bash
mkdocs build
```

## Contributing

We welcome contributions to improve and expand our documentation:

1. Fork this repository.
2. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your edits within the `docs/` directory.
4. Commit your changes and push to your fork.
5. Open a Pull Request against the **tools** branch of this repository.

For substantial enhancements or structural changes, please open an issue first to discuss your proposal.

## Deployment

Changes merged into the **tools** branch are automatically deployed via GitHub Actions to [https://docs.wyemake.co.uk/](https://docs.wyemake.co.uk/).

## Licence

This documentation is licensed under the MIT Licence. See [LICENSE](LICENSE) for details.

## Contact

For queries or further assistance, please get in touch with the Wye Make team at [docs@wyemake.co.uk](mailto:docs@wyemake.co.uk).
