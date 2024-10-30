## Technical Assessment: ZNPHI Public Health Intelligence Officer – Bioinformatics & Big Data Visualization

### Overview
This repository contains the technical assessment for the ZNPHI Public Health Intelligence Officer position, focusing on Bioinformatics and Big Data Visualisation. It includes data analysis scripts, visualisations, and summary reports for public health data.

### Project Structure
- **data/**: Contains the input datasets (e.g., maternal deaths, measles lab). [ignored and not uploaded]
- **task/**: Stores various project tasks. [ignored and not uploaded]
- **bigdata_env/**: Virtual environment to ensure consistency across machines.
- **malambo.ipynb**: Jupyter Notebook for the analysis and visualization of data.
- **README.md**: Project documentation.

### Setup Instructions
1. **Clone the repository**:
    
    git clone https://github.com/malambomutila/Big-Data-Visualisation-Assessment.git
    
   
2. **Set up the virtual environment**:
    ```sh
    python -m venv bigdata_env
    source bigdata_env/bin/activate  # For Linux/Mac
    bigdata_env\Scripts\activate     # For Windows
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

### Running the Analysis
1. Activate the virtual environment as described above.
2. Launch Jupyter Notebook to run the analysis scripts:
    ```sh
    jupyter notebook malambo.ipynb
    ```

### Technical Details
The analysis is carried out using key libraries, such as:
- **Pandas** for data manipulation.
- **Matplotlib** and **Seaborn** for data visualization.
- **GeoPandas** and **Folium** for spatial data analysis.




