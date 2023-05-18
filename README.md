# DATACAMP SQL Project: Exploring Mental Health of International Students

📚 This project aims to analyze the mental health of international students at a Japanese university using SQL. The study was conducted in 2018 and published the following year, approved by various ethical and regulatory boards.

🔍 The objective is to investigate whether studying in a different country affects the mental health of students, with a focus on the length of stay as a contributing factor.

## 📋 Data Description

![Illustration of silhouetted heads](mentalhealth.jpg)

Does going to university in a different country affect your mental health? A Japanese international university surveyed its students in 2018 and published a study the following year that was approved by several ethical and regulatory boards.

The study found that international students have a higher risk of mental health difficulties than the general population. Explore the `students` data using PostgreSQL to find out if this is true and see if the length of stay is a contributing factor.

Here is a data description of the columns you may find helpful.

| Field Name    | Description                                      | 
| ------------- | ------------------------------------------------ |
| inter_dom     | Types of students                                |
| japanese_cate | Japanese language proficiency                    | 
| english_cate  | English language proficiency                     |
| academic      | Current academic level                           | 
| age           | Current age of student                           |
| stay          | Current length of stay in years                  |
| todep         | Total score of depression (PHQ-9 test)           |
| tosc          | Total score of social connectedness (SCS test)   |
| toas          | Total score of Acculturative Stress (ASISS test) |

## 📊 Exploratory Analysis

To gain insights into the mental health of international students, the following steps were performed using SQL:

1. Counted the number of records in the dataset and per student type.
2. Filtered the data to compare student types.
3. Calculated summary statistics for diagnostic tests for all students.
4. Analyzed the diagnostic test scores for international students.
5. Investigated if the length of stay impacts the test scores for domestic students.

## 🧪 Results and Findings

The analysis revealed the following:

- The dataset consists of 268 student records.
- There are 150 international students and 118 domestic students.
- International students show higher risks of mental health difficulties compared to the general population.
- The average scores for depression, social connectedness, and acculturative stress were calculated for all students and specifically for international students.
- The analysis also examined how the length of stay affects the test scores for both international and domestic students.

## 📑 Queries and Code

The SQL queries used in this project can be found in the [jupyter notebook](students_mental_health.ipynb)) file.

## 📚 References

The study and dataset used in this project are based on the research conducted by [Japanese International University](example-link-to-the-study).

---

This project provides valuable insights into the mental health of international students at a Japanese university. By analyzing the data using SQL, we were able to explore the impact of studying in a different country and the role of the length of stay. Feel free to explore the queries and findings to deepen your understanding of the subject matter.

🌟 Have fun exploring and analyzing the data! If you have any questions or feedback, please don't hesitate to reach out.
