# movie-recommended-system

## Project Description
This project is a simple movie recommendation system based on **Genre** and **IMDb Rating**, implemented using the **pandas crosstab** method.  
The user selects a genre, and the system recommends movies from that genre, sorted by their IMDb ratings.

---

## Workflow
1. **Load the dataset** from the original CSV file.  
2. **Clean the data** (remove null values, convert column types, remove outliers).  
3. **Select important features** (Genre, Title, IMDb Rating).  
4. **Sample selection** for testing the system (e.g., 20 random movies).  
5. **Build a Crosstab table** to show the relationship between genres and movie ratings.  
6. **Recommend movies** based on the selected genre.

---

## Requirements
- Python 3.10+
- Libraries:
  ```bash
  pip install pandas numpy
