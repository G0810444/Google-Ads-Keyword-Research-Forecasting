# 📊 Keyword Research & Forecasting for Google Ads

## 🧠 About This Project

This is a very important subject for me — **Google Ads** is what got me interested in data science in the first place. Over the past four years, my keyword research and forecasting process has been praised and refined through hands-on experience in managing ad accounts.

This project walks you through my exact workflow for conducting keyword research and forecasting campaign performance — using **only free tools**. My goal is to help others understand how to create strategic ad projections rooted in **real business KPIs** and **high-intent search behavior**.

---

## 🔍 Why Not Just Use Paid Tools?

Many paid tools are great, but they often **lack the granular data** that Google itself provides — which is readily accessible through **Google Keyword Planner**. In fact, Google Ads is all about **high-intent keywords that match the way customers search for your specific business offering.**

---

## ✅ What This Project Covers

- Keyword research using Google Keyword Planner
- Understanding keyword intent
- Cleaning and refining keyword lists
- Creating a custom Google Ads forecast using actual sales KPIs
- Incorporating remarketing spend and sales performance
- Building a practical projection model in Google Sheets

---

## 🔧 Tools Used

- Google Keyword Planner (free)
- Google Sheets (custom projection template)
- Optional: Ed Leake's forecasting sheet (credited below)

---

## 🗂 Step-by-Step Guide

### 1. Start with Business Context

Before jumping into keywords, make sure you have clarity on:

- What your business offers
- Who your target audience is
- What region(s) you’re targeting

### 2. Begin Keyword Research

We’ll use the example of a real furniture company called **Sofa Mania**, which is exploring selling **dog beds** as a new product.

### Using Google Keyword Planner:

![Group 22.jpg](attachment:44abbaea-e336-4068-bd9b-77fe12bc19fc:Group_22.jpg)

- Go to **Discover New Keywords**
- Input a base term, e.g., `"dog bed"`
- Set your **location targeting** (make sure it matches your actual business goals)
- Filter for **Google Search Network** only
    
    ![Group 23.jpg](attachment:4c653ad9-15cc-4160-8711-601d68e3d491:Group_23.jpg)
    
- Use filters to show only keywords with **100+ monthly searches**
- Use the **Refine Keywords** panel to remove:
    - Services you don’t offer
    - Brand names
    - Other irrelevant terms

### Save High-Intent Keywords Only

We’re interested in **transactional** intent, not navigational or informational.

| Type | Example | Use it? |
| --- | --- | --- |
| Navigational | `petco dog beds` | ❌ |
| Informational | `how to choose a dog bed` | ❌ |
| Transactional | `dog bed for sale` | ✅ |

💡 **Tip**: Add irrelevant or misleading keywords to your **negative keyword list** (e.g., anything with `<50 impressions`).

---

### 3. Forecasting Performance

Now that you've built your keyword list:

### Go to:

> Get Search Volume and Forecasts in Keyword Planner
> 
> 
> ![lo34.jpg](attachment:ac165524-527c-4e59-8fb7-061f52a4933a:lo34.jpg)
> 

Why not use Google's native forecast? Because it **doesn’t account for**:

- Sales close rate
- Revenue per sale
- Profit margins
- Remarketing performance
- Your actual ad KPIs

That’s why I use a custom **Google Ads projection sheet** that gives a more accurate view.

---

### 4. Building the Forecast Sheet

1. **Paste your keyword list** into Keyword Planner’s forecast section to get:
    - Avg. monthly searches
    - Competition
    - Competition index
    - Top of page bid ranges (low and high)
2. Transfer that data into the **Input Page** of your forecasting sheet.
3. Head to the **Projections Page** and fill in your known or estimated KPIs, such as:
    - CTR (Click-Through Rate)
    - CVR (Conversion Rate)
    - Revenue per sale
    - Close rate
    - Remarketing %

---

## 📊 The Forecasting Sheet

![image.png](attachment:f60e649c-8c56-440a-97c9-60e89b804935:image.png)

The projection sheet I use is inspired by Ed Leake’s well-known model. Credit to him for building the foundation. let me know if you would like to see me create my own sheet and add:

- Include remarketing spend
- Focus on real business KPIs
- Separate performance by intent and funnel stage

---

## 🧾 Future Plans

- Add an automated Google Ads API version
- Integrate keyword clustering by intent and category
- Visualize ROI projections using interactive dashboards

---

---

## 📎 Credits

- **Forecast Sheet Model**: Ed Leake
- **Example Company**: Sofa Mania (used for demonstration purposes)
