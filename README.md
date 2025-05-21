# Solar Challenge Week 1

This repository contains data analysis and visualization scripts for solar energy datasets from Benin, Sierra Leone, and Togo. The project uses Python and Jupyter notebooks to explore and clean the data.

## Project Structure

```
.gitignore
app.py
README.md
report.txt
requirements.txt
.github/
    workflows/
        ci.yml
data/
    benin-malanville.csv
    cleaned_Benin_solar_data.csv
    cleaned_sierraleone_solar_data.csv
    cleaned_Togo_solar_data.csv
    sierraleone-bumbuna.csv
    togo-dapaong_qc.csv
notebook/
    benin._eda.ipynb
    sierraleone.ipynb
    Togo_eda.ipynb
    .ipynb_checkpoints/
        benin._eda-checkpoint.ipynb
        sierraleone-checkpoint.ipynb
        Togo_eda-checkpoint.ipynb
venv3/
    lib64
    pyvenv.cfg
    bin/
        python
    include/
    lib/
    share/
```

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Nebiyuu/solar-challenge-week1.git
cd solar-challenge-week1
```

### Set Up a Python Virtual Environment

Using `venv` (Built-in):

```bash
python -m venv venv3          # Create virtual environment
source venv3/bin/activate     # Activate (Linux/Mac)
venv3\Scripts\activate        # Activate (Windows)
```

### Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Notebooks

The following Jupyter notebooks are included for exploratory data analysis (EDA):

- **Benin:** `notebook/benin._eda.ipynb`
- **Sierra Leone:** `notebook/sierraleone.ipynb`
- **Togo:** `notebook/Togo_eda.ipynb`

## Data

The `data/` directory contains raw and cleaned datasets for Benin, Sierra Leone, and Togo.

## Requirements

The project uses the following Python packages (see [`requirements.txt`](requirements.txt)):

- `matplotlib`
- `numpy`
- `pandas`
- `seaborn`
- And more...

## Running the Notebooks

To run the notebooks, ensure the virtual environment is activated and launch Jupyter:

```bash
jupyter notebook
```

Open the desired notebook from the `notebook/` directory.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.