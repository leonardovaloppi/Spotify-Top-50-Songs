![Spotify Banner](https://raw.githubusercontent.com/leonardovaloppi/Spotify-Top-50-Songs/main/ST50_banner.jpg)

# Spotify Top Hits 2020 Analysis 🎶

*NOTE: This project is part of **Sprint 2 of Module 4** in the Data Analytics program at **Turing College**.*

## Table of Contents

- [Goal](#goal-)  
- [Project Files](#project-files-%EF%B8%8F)  
- [Dataset Source](#dataset-source-%EF%B8%8F)  
- [Report Chapters](#report-chapters-)  
- [Tools & Technologies](#tools--technologies-%EF%B8%8F)  
- [How to Access the Report](#how-to-access-the-report-)
  - [Using Conda](#method-a--using-conda-recommended)  
  - [Using Pip](#method-b--using-pip)  
- [More from Leonardo Valoppi](#more-from-leonardo-valoppi-)

---

## Goal 🎯
Perform exploratory data analysis on the **Spotify's Top 50 Tracks of 2020** and quantify what makes a hit song.  

---

## Project Files 🗂️

- `ST50_dataset.csv` → Dataset used for the analysis  
- `ST50_report.ipynb` → Jupyter Notebook with the analysis report
- `ST50_banner.jpg` → Banner with the Spotify logo
- `ST50_conda-env.yml` → Conda environment with all the packages (requires Conda)
- `ST50_pip-env.txt` → Package list for Pip venv (if you don't use Conda)

---

## Dataset Source 🗃️
`ST50_dataset.csv` comes from the **[Spotify Top 50 Tracks of 2020](https://www.kaggle.com/datasets/atillacolak/top-50-spotify-tracks-2020)** dataset on Kaggle.  
Originally, the Kaggle dataset was extracted using **[Spotypy](https://spotipy.readthedocs.io/en/2.16.1/)**, a Python library for accessing the Spotify **[Web API](https://developer.spotify.com/documentation/web-api)**.

It includes **50 songs** along with their respective **audio features**.

---

## Report Chapters 📖

- Part 1 → Data Preparation and Cleaning
- Part 2 → First Step Into the Data
- Part 3 → Invastigating Extremes in Song Charateristics
- Part 4 → Examing Genre Popularity and Diversity
- Part 5 → Examing Correlations Between Musical Attributes
- Part 6 → How Musical Features Vary Across Genres
- Part 7 → Final Conclusion: Insights from the Spotify Top 50 Tracks 2020 Dataset

---

## Tools & technologies 🛠️

| Tool | Purpose |
|------|---------|
| **Python v3.11** | Programming language |
| **Pandas v2.2.3** | Python library for data cleaning and manipulation |
| **Jupyter Notebook v7.3.2** | Interactive coding environment |

---

# How to Access The Report 💾

## 1. Clone the Repository & Download Files  📥

First, clone the repository to your local machine using **Git**:

```bash
git clone https://github.com/leonardovaloppi/spotify-top-50.git
```
Alternatively, if you don’t have Git installed, you can download the ZIP file:
- 1 → Click the green `Code` button at the top of the repository.
- 2 → Select `Download ZIP` and extract the folder.

---

## 2. Set Up the Virtual Environment 📦

This project supports both Conda and pip for dependency management. You can choose your preferred method.

*Dependencies include essential tools and libraries needed to access and work with the dataset in Jupyter Notebook. These include Python, Pandas, NumPy, and Jupyter Notebook itself, all in compatible versions to prevent conflicts. Using virtual environments ensures that you can safely manage different tool versions across various projects. Avoid using mismatched versions when accessing these files to prevent potential issues.*

---

### Method A → Using Conda (Recommended)

If you have Conda installed, you can easily create a new environment with all the required dependencies using the provided <br>
 `ST50_conda-env.yml` file.
 
Open your Terminal and move to the folder where you installed the material:

```bash
cd Spotify-Top-50-Songs-main
```

Create a new environment from the `.yml` file:
```bash
conda env create -f ST50_conda-env.yml 
```

Activate it: 
```bash
conda activate ST50_conda-env
```

Once `ST50_conda-env` is active open Jupyter Notebook:
```bash
jupyter notebook
```
A web browser page will open up. Choose the project `ST50_report.ipynb` from the menu and start exploring the report! 🚀

---

### Method B → Using Pip

Open your Terminal and move to the folder where you installed the material:

```bash
cd Spotify-Top-50-Songs-main
```
Create a new empty envorinment called `ST50_env`:
```bash
python -m venv ST50_env
```

Then, activate it:
```bash
source ST50_env/bin/activate  # On Mac/Linux
ST50_env\Scripts\activate     # On Windows
```

Finally, install all the dependencies into `ST50_env` from the `ST50_pip-env.txt` file.
```bash
pip install -r ST50_pip-env.txt
```

Once `ST50_conda-env` is active open Jupyter Notebook:
```bash
jupyter notebook
```

A web browser page will open up. Choose the project `ST50_report.ipynb` from the menu and start exploring the report! 🚀

---

## More from Leonardo Valoppi 👨‍💻

[LinkedIn](https://linkedin.com/in/leonardo-valoppi)

[GitHub Profile](https://github.com/leonardovaloppi)  

[Tableau Public](https://public.tableau.com/app/profile/leonardo.valoppi/vizzes)


---

[Table of Contents](#table-of-contents)

