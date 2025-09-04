# data-science-job-trends-europe
A study of data science jobs in Europe at the moment.

This file will contain an indept explanation of the project goal, and the steps taken. 

## Step 1: Set up your project structure (30–45 min)
Create a new GitHub repo: data-science-job-trends-europe
Inside it, set up folders:
- data/ (raw & cleaned datasets)
- notebooks/ (your Jupyter notebooks)
- plots/ (your visualizations)
- README.md (explain project goal & steps)

## Step 2: Find your dataset (30–60 min)
1. Go to Kaggle and search:
  - “Job postings”
  - “Skills demand”
  - “European job market”
2. Candidates:
  - Kaggle: Data Science Job Postings (global, but you can filter for Europe)
  - Kaggle: Job Skills Dataset
  - Eurostat datasets (employment in ICT/tech)
3. Download 1 dataset and drop it in data/.

## Step 3: Open a Jupyter Notebook and explore the data (1–2 hrs)
1. Load dataset with Pandas.
2. Do df.head() and df.info() to understand structure.
3. Identify key columns (e.g. job title, skills, location, description).

## Step 4: Define 2–3 research questions (30 min)
Example:
- Which countries have the most DS job postings?
- What skills are most requested (Python, R, SQL, ML, etc.)?
- How do requirements differ between Denmark, Spain, Switzerland, Italy?
👉 Pick just 2 questions to keep it small.

## Step 5: Clean & preprocess data (1–2 hrs)
- Standardize job titles (remove duplicates, normalize “Data Scientist” vs “Data Science Specialist”).
- Extract skill keywords from descriptions (e.g., “Python,” “SQL,” “Machine Learning”).
- Handle missing values.

## Step 6: Analyze & visualize (2–3 hrs)
- Count skills frequency (value_counts(), Counter from collections).
- Plot Top 10 Skills in Europe (bar chart).
- Compare skills demand by country (grouped bar plot).

## Step 7: Wrap up results (1–2 hrs)
- Save key plots in plots/.
- Write up short conclusions in your notebook:
    e.g., “Python appears in 70% of job postings in Denmark, vs 50% in Italy.”
- Push everything to GitHub.

## Step 8: Make it “portfolio-ready” (1–2 hrs)
1. Write a README.md with:
  - Project description
  - Dataset source
  - Methods
  - Key findings (include 1–2 plots as images)
2. Publish repo.

## Step 9 (Optional, powerful): Share on LinkedIn (30 min)
Write a short post:
“As part of my job search, I built a small project analyzing job postings in Europe to see which skills are most in-demand for data science roles. Turns out Python dominates in Denmark, while [interesting insight]. I really enjoyed combining data cleaning, Pandas, and visualization for this. Repo here: [GitHub link].”
