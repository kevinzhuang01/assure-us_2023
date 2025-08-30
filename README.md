## What's This About?

Basically, I got curious about student performance and decided to throw some machine learning at the problem. Using a Kaggle dataset with tons of student info (study hours, family income, sleep patterns, etc.), I built models to predict exam scores and see what really moves the needle.

**The Big Question**: Can we predict how well a student will do on exams based on their lifestyle, family background, and study habits?

## The Data 📊

Working with **6,607 student records** from [this Kaggle dataset](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors).

**What we're looking at**:
- Study habits (hours studied, attendance, tutoring)
- Personal stuff (sleep, exercise, motivation)
- Family factors (income, parent education, involvement)
- School environment (teacher quality, resources, school type)
- Demographics and lifestyle choices
- **The target**: Exam scores (ranging from 55-101)

## Tech Stack 🛠️

- **Python** for everything
- **pandas & numpy** for data wrangling
- **scikit-learn** for the ML models
- **matplotlib & seaborn** for pretty charts
- **Google Colab** because who doesn't love free GPUs?

## What I Built

Tested out a bunch of different approaches:
- **Linear Regression** (the classic)
- **Ridge & Lasso** (when you need to be fancy about overfitting)
- **Decision Trees** (for when linear just isn't cutting it)

## How to Run This

**Easy mode**: Just click the Colab badge above and run the cells!
