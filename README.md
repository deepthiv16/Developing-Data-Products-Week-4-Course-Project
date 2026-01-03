# Developing Data Products – Week 4 Course Project

## Project Overview
This repository contains the Week 4 peer-graded project for the **Developing Data Products** course on Coursera.  
The project consists of:

1. A **Shiny web application** deployed on RStudio’s Shiny server  
2. A **reproducible pitch presentation** created using **RStudio Presenter (ioslides)**

---

## Shiny Application: MPG Analysis

### Description
The **MPG Analysis Shiny Application** allows users to explore the relationship between automobile characteristics and **miles per gallon (MPG)** using the built-in `mtcars` dataset in R.

The application is designed to be simple and interactive so that even novice users can easily understand and use it.

---

### How to Use the Application
1. Select a car variable (such as cylinders, weight, horsepower, or transmission) from the dropdown menu.
2. Optionally enable or disable boxplot outliers using the checkbox.
3. View:
   - A **boxplot** showing the MPG distribution
   - A **regression plot** and **model summary**
4. The outputs update automatically based on user input.

---

### Application Features
- Dropdown input for selecting automobile variables
- Checkbox input to control boxplot outliers
- Reactive boxplots and regression models
- Multiple tabs providing dataset explanation and documentation

All documentation required to use the application is included **within the Shiny app interface itself**, as required by the assignment.

---

### Live Shiny Application
**Shiny App URL:**  
https://deepthiv-16.shinyapps.io/MPG_Analysis_Shiny_Application/

---

## Source Code
The Shiny application source code is available in this repository:

- `ui.R` – User interface definition  
- `server.R` – Server logic and reactive computations  

**GitHub Repository:**  
https://github.com/deepthiv16/Developing-Data-Products-Week-4-Course-Project

---

## Reproducible Pitch Presentation
A **5-slide HTML presentation** was created using **RStudio Presenter (ioslides)** to pitch the Shiny application.

The presentation includes:
- Project overview and motivation
- Dataset introduction
- Embedded R code evaluated during rendering
- Application features and conclusion

**RPubs Presentation Link:**  
http://rpubs.com/deepthi_16/mpg-analysis-shiny-app

---

## Requirements Checklist

### Shiny Application
- ✔ Input widgets included  
- ✔ Server performs calculations based on input  
- ✔ Reactive output displayed  
- ✔ Documentation included within the app  
- ✔ Application deployed on Shiny server  

### Reproducible Pitch
- ✔ Created using RStudio Presenter  
- ✔ Exactly 5 slides  
- ✔ Embedded R code evaluated and displayed  
- ✔ Hosted on RPubs  
- ✔ No errors during rendering  

---

## Author
**Name:** Deepthi V  
**Course:** Developing Data Products  
**Platform:** Coursera
