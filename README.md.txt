# 🧠 AI-Powered Data Analysis Assistant

A prompt-engineered system that transforms raw datasets into structured insights and actionable business recommendations using AI.

---

## 📌 Overview

Manual data analysis can be time-consuming and inconsistent. This project demonstrates how structured prompt engineering can be used to guide AI models to:

* Analyze raw datasets
* Extract meaningful insights
* Identify trends and anomalies
* Generate clear, decision-ready reports

---

## 🎯 Objectives

* Automate data analysis workflows using AI
* Ensure consistent and structured outputs
* Reduce manual effort in interpreting datasets
* Deliver actionable business insights

---

## 🛠️ Tech Stack

* Prompt Engineering
* Large Language Models (LLMs)
* Data Analysis Concepts
* Markdown for structured reporting

---

## ⚙️ How It Works

### 1. Input

Provide a dataset (CSV or tabular format)

### 2. Prompt Execution

The dataset is passed into a structured prompt that:

* Assigns the AI a role (data analyst)
* Defines output structure
* Enforces rules for clarity and accuracy

### 3. Output

The AI generates a structured report including:

* Summary
* Key insights
* Problems
* Recommendations

---

## 🧾 Core Prompt

```text
You are a professional data analyst.

Analyze the dataset provided and produce a structured report.

Follow this format strictly:

1. SUMMARY
- Total revenue
- Average revenue
- Top-performing product
- Total revenue for each Region
- Average revenue for each Region
- Top-performing product for each Region


2. KEY INSIGHTS
- Identify trends
- Highlight best-performing regions
- Mention any patterns

3. PROBLEMS
- Identify underperforming areas
- Highlight inconsistencies or risks

4. RECOMMENDATIONS
- Provide 3–5 actionable business recommendations

Rules:
- Be clear and concise
- Use bullet points
- Do not make assumptions beyond the data
- If data is missing, state it clearly
- Double-check calculations before presenting results
- Before giving the final answer, briefly outline how you analyzed the data
- Present the final output in a clean, structured report format suitable for business use.
```

---

## 📊 Example Output

```
Here’s how I approached the analysis before generating the report:

* Loaded the dataset and checked columns and structure
* Used **Amount** as revenue (no alternative revenue field provided)
* Aggregated totals and averages using groupby functions
* Identified top-performing products by summing revenue per **Sub-Category**
* Broke down results by **Region** for deeper insights
* Double-checked calculations for consistency

---

# 📊 STRUCTURED REPORT

## 1. SUMMARY

* **Total Revenue:** 431,502
* **Average Revenue:** 287.67
* **Top-performing Product:** Printers

### Total Revenue by Region

* Greater Accra: 108,604
* Ashanti: 105,140
* Bono East: 25,649
* Northern: 22,531
* Savannah: 22,359
* Upper East: 21,149
* Western North: 21,058
* Western: 17,179
* Eastern: 15,058
* Volta: 14,086
* North East: 13,459
* Oti: 12,943
* Central: 10,829
* Bono: 8,666
* Ahafo: 6,087
* Upper West: 6,705

### Average Revenue by Region

* Savannah: 328.81
* Greater Accra: 327.12
* Ashanti: 309.24
* Northern: 304.47
* North East: 299.09
* Bono: 298.83
* Bono East: 298.24
* Upper East: 285.80
* Eastern: 278.85
* Western: 248.97
* Western North: 242.05
* Ahafo: 243.48
* Volta: 223.59
* Central: 221.00
* Oti: 208.76
* Upper West: 155.93

### Top-performing Product by Region

* Ahafo: Tables
* Ashanti: Printers
* Bono: Phones
* Bono East: Saree
* Central: Saree
* Eastern: Accessories
* Greater Accra: Bookcases
* North East: Trousers
* Northern: Tables
* Oti: Printers
* Savannah: Printers
* Upper East: Electronic Games
* Upper West: Tables
* Volta: Saree
* Western: Chairs
* Western North: Bookcases

---

## 2. KEY INSIGHTS

* Revenue is heavily concentrated in **Greater Accra and Ashanti**, which together contribute nearly half of total sales
* **Printers** dominate overall, appearing as the top product in multiple regions
* Higher average transaction values are seen in:

  * Savannah
  * Greater Accra
  * Ashanti
* Some regions (e.g., Upper West, Oti) show significantly lower average revenue, indicating smaller transaction sizes
* Product preferences vary strongly by region, suggesting localized demand patterns

---

## 3. PROBLEMS

* **Underperforming Regions:**

  * Upper West
  * Ahafo
  * Bono
* **Low average revenue** in regions like Upper West and Oti suggests weaker purchasing power or smaller order sizes
* **Revenue imbalance:** Over-reliance on a few regions (Greater Accra, Ashanti) increases business risk
* Some regions show **limited product dominance**, which may indicate weak product-market fit

---

## 4. RECOMMENDATIONS

* **Expand high-performing products** (e.g., Printers) into more regions where they are not yet dominant
* **Target underperforming regions** with promotions or pricing strategies to increase transaction volume
* **Diversify regional revenue streams** to reduce dependence on Greater Accra and Ashanti
* **Leverage regional preferences** by tailoring product offerings (e.g., Saree in Bono East, Bookcases in Greater Accra)
* **Increase average order value** through bundling or upselling in low-performing regions

```

---

## 🔍 Before vs After

| Stage  | Description                                         |
| ------ | --------------------------------------------------- |
| Before | Raw dataset requiring manual interpretation         |
| After  | Structured report with insights and recommendations |

---

## 💡 Key Features

* Structured AI-driven analysis
* Consistent output formatting
* Reduced manual workload
* Business-focused recommendations

---

## 🚀 Use Cases

* Sales data analysis
* Business reporting automation
* Market trend identification
* Operational performance review

---

## 📂 Project Structure

```
ai-data-analysis-assistant/
│
├── README.md
├── sample-data/
│   └── sales_data.csv
├── prompts/
│   └── analysis_prompt.txt
└── outputs/
    └── sample_report.md
```

---

## 🔧 Future Improvements

* Integration with Python for automated pipelines
* Dashboard visualization (e.g., Power BI / Tableau)
* API-based deployment
* Multi-dataset comparison

---

## 📎 Getting Started

1. Clone the repository
2. Open the prompt file in `/prompts`
3. Insert your dataset
4. Run using your preferred LLM interface
5. Review generated output

---

## 🧠 Key Insight

This project highlights that prompt engineering is not just about writing instructions, but about designing structured systems that produce reliable and repeatable results.

---

## 🤝 Contribution

Contributions are welcome. Feel free to improve prompts, add datasets, or enhance output formats.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👤 Author

**Daniel Mensah Danso**
Geological Engineering Graduate | Data Analyst | Prompt Engineering Enthusiast

---
