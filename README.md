# Journal Club

A Quarto-based website for tracking and summarizing articles related to antibody engineering and computational design.

## Project Structure

- `index.qmd`: Main landing page with a table-based listing of articles.
- `post/`: Directory containing article summaries and evaluations.
  - `Biparatopic_antibodies__therapeutic_applications/`: Review of biparatopic antibodies in clinical trials.
  - `260211/`: De novo design of epitope-specific antibodies.
- `about.qmd`: Information about the project.
- `_quarto.yml`: Quarto configuration file.

## Setup and Usage

This project uses [Pixi](https://pixi.sh/) for dependency management.

### Build and Preview

1.  **Install dependencies**:
    ```bash
    pixi install
    ```

2.  **Preview the website**:
    ```bash
    pixi run quarto preview
    ```

3.  **Render the website**:
    ```bash
    pixi run quarto render
    ```

The rendered website is located in the `docs/` directory.
