![waggle](https://drive.google.com/uc?export=view&id=1r8fGBc5VMQfrP7vshWxfeyCPrhrXAuwb)
# Waggle Pet Tracker Analytics Project (Simulated Data)

## Project Overview

This project is a **scenario-based simulation** analyzing customer and pet data for **Waggle**, a hypothetical company producing smart electronic collars for cats and dogs. These collars track pets’ location, heart rate, activity, and health metrics, providing the data to customers through a mobile app.

The purpose of this simulated project is to **demonstrate how visual analytics and Star Schema modeling in Power BI** can provide actionable insights for business decisions.

---

## Data Tables

The simulated dataset includes the following tables:

**Date Table**  
- Contains day, month, and year values for time-based analysis.

**Family Table**  
- Fields: Family_ID, Family_Name, City, State, Zip, Country, Email, Household_Size, Household_Income, Annual_Pet_Expenses, Total_Pets, Years_of_Pet_Ownership

**Tracker Table**  
- Fields: Tracker_ID, Activity_Date, Family_ID, Pet_ID, Daily_Steps, Activity_Minutes, Heartrate_BPM

**Pet Table**  
- Fields: Pet_ID, Name, Dog/Cat, Breed, Age, Gender, Rescue?, Weight

**Rating Data Table**  
- Fields: Tracker_ID, Review_Date, Device_Type, Rating, Would You Recommend this Product?, Where Did You Buy This Product?, Comments

---

## Power BI Dashboards

The project contains the following dashboards, all built in **Power BI Desktop** using a Star Schema for clean data analysis:

**Home**  
- Main landing page that serves as a navigation interface to access the other dashboards.

**Huisdiergegevens**  
- Displays general pet information such as species, breed, and gender distributions.

**Vergelijking**  
- Compares the two products (**LapDog vs LapCat**) and pets’ activity metrics, including average steps, heart rate, and gender comparisons.

**Beoordeling**  
- Analyzes customer reviews and ratings, including product feedback and purchase locations.  
- Shows comparisons between stores and identifies which store has the highest sales.

**Familie**  
- Visualizes household demographics, including income distributions and spending on the product.  
- Shows patterns based on household size (e.g., 1, 4, 5-person households purchase most).  
- Maps family locations and provides aggregated metrics like average income, total income, and household size distributions using the *Doelgroep* chart.

---

## Project Purpose and Insights

This scenario demonstrates how **interactive dashboards** can help a company:

- Measure **customer satisfaction** and product recommendations.  
- Compare **products and pet behavior metrics** to support product development.  
- Analyze **customer demographics and household patterns** to inform pricing and marketing.  
- Identify **regions with high sales concentration** for targeted marketing or potential store openings.  
- Provide a **data-driven foundation** for strategic decisions, even though this is simulated data.

Overall, the dashboards offer clear visual insights into customer behavior, pet activity, and product performance, helping Waggle plan for **future business strategies**.
