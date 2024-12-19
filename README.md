# Interactive PCA Explorer

This repository contains the source code for the **Interactive PCA Explorer**, a Shiny web application for performing Principal Component Analysis (PCA) with interactive visualizations and data exploration.

## Features
- **Upload CSV or Excel Files**: Easily upload your dataset for analysis.
- **Interactive PCA Analysis**:
  - Scree plots, biplots, and variable plots.
  - Dynamic selection of principal components for visualization.
- **Data Scaling and Centering**: Choose whether to scale or center your data before analysis.
- **Download Results**: Save the results and visualizations as a PDF file.
- **Data Preview**: View and explore your uploaded data within the app.

## Getting Started

### Prerequisites
Ensure you have the following software installed:
- [R](https://www.r-project.org/)
- [RStudio](https://www.rstudio.com/) (optional but recommended)
- Required R packages:
  - `shiny`
  - `ggplot2`
  - `plotly`
  - `DT`
  - `FactoMineR`
  - `factoextra`
  - `readr`
  - `shinycssloaders`
  - `shinythemes`
  - `readxl`

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/interactive-pca-explorer.git
   cd interactive-pca-explorer
   ```
2. Open R or RStudio and set your working directory to the project folder.
3. Install required packages if not already installed:
   ```R
   install.packages(c("shiny", "ggplot2", "plotly", "DT", "FactoMineR", "factoextra", "readr", "shinycssloaders", "shinythemes", "readxl"))
   ```

### Running the App
Run the following command in your R console:
```R
shiny::runApp()
```
This will launch the app in your default web browser.

## Usage

### Uploading Data
- Use the **"Upload CSV or Excel File"** button to upload your dataset.
- Supported file formats: `.csv` and `.xlsx`.

### PCA Configuration
- **Scaling and Centering**: Toggle these options to preprocess your data.
- **Number of Components**: Specify the number of principal components to retain.
- **Plot Type**: Choose from Scree Plot, Biplot, or Variable Plot.
- **Principal Components**: Dynamically select PCs for biplot or variable plot visualization.

### Downloading Results
- Click **"Download Results as PDF"** to save the analysis and visualizations.

## File Structure
```
interactive-pca-explorer/
├── app.R               # Main ShinyApp script
├── README.md           # Documentation
└── data/               # (Optional) Example datasets
```

## Contributing
We welcome contributions! Please follow these steps:
1. Fork this repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
This project utilizes the following R packages: `shiny`, `ggplot2`, `plotly`, `DT`, `FactoMineR`, `factoextra`, and more. Special thanks to the R community for their invaluable resources.


