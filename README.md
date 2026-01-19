# Does Student Debt Pay Off?

## Examining the Debt-Earnings Relationship Across U.S. Colleges

This repository contains the code, data documentation, and supporting materials for a course project completed as part of **S470/670 - Exploratory Data Analysis (Fall 2025)** at **Indiana University Bloomington**.

**Authors:** Yash Takte & Meryl Sarah Jacob

---

## Project Overview

Student loan debt in the United States exceeds **$1.7 trillion**, yet the relationship between borrowing for college and post-graduation earnings remains widely debated. A common belief is that higher tuition and higher debt lead to better career outcomes.

This project examines whether that assumption holds across different types of U.S. colleges.

Using institution-level data from the U.S. Department of Education’s College Scorecard, we analyze how **student debt**, **graduation rates**, and **earnings one year after graduation** interact across **1,430 four-year U.S. institutions**.

---

## Research Question

**Does borrowing for college lead to higher earnings after graduation, and does this relationship vary by:**

* Institution type (Public vs. Private Nonprofit)
* Institutional quality (measured through graduation rates)

---

## Data Description

* **Source:** U.S. Department of Education - College Scorecard
* **Institutions analyzed:** 1,430 four-year U.S. colleges
* **Institution types:** Public and Private Nonprofit

### Key Variables

* Median student debt at graduation
* Graduation rate (6-year completion rate)
* Median earnings one year after graduation

The analysis focuses on **graduates only** and captures **short-term (one-year) earnings outcomes**.

---

## Methodology

* Exploratory Data Analysis (EDA) to examine distributions and relationships
* Stratified analysis by institution type and graduation-rate tiers
* Flexible modeling to capture nonlinear patterns between debt, graduation rates, and earnings

The models explain approximately **18-22% of earnings variation**, highlighting the importance of unobserved factors such as field of study, student background, and career choices.

---

## Key Findings

* **Public universities:** Graduation rates dominate earnings outcomes. High-completion institutions produce stronger earnings even when students borrow more.
* **Risk zone:** Institutions with graduation rates around 40–50% show weak earnings outcomes regardless of debt levels.
* **Private nonprofit institutions:** Higher debt correlates with higher earnings, reflecting institutional selectivity and prestige rather than debt’s causal effect.
* **Overall:** Moderate debt at high-graduation-rate institutions yields better outcomes than minimal debt at struggling schools.

---

## Limitations

* Earnings are measured **one year after graduation**, not long-term outcomes
* Non-completers are excluded from the analysis
* Field of study and program-level differences are not directly modeled
* Results reflect associations, not causal effects

---

## Course Information

* **Course:** S470/670 - Exploratory Data Analysis
* **Semester:** Fall 2025
* **Institution:** Indiana University Bloomington

---

## Acknowledgments

Data provided by the U.S. Department of Education College Scorecard.

This project was completed for academic purposes as part of coursework.
