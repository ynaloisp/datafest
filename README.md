# A Statistical Analysis of Manhattan’s Commercial Rent Market

**Authors:** Param Gogia, Theo Olsen, Ynalois Pangilinan, Caius Gordon-Bruno, Frankie Balla  
**Date:** April 2025

## 📌 Overview

This project investigates how commercial leasing patterns in Manhattan, NY have changed before and after the COVID-19 pandemic. We focus on analyzing data from the Savills database to understand shifts in lease size, location preferences, and potential economic factors influencing corporate real estate decisions.

This project was developed for the 2025 DataFest.

## 🧠 Motivation

The pandemic dramatically changed workplace norms, shifting many companies to hybrid or remote models. As a result, the demand for office space changed significantly. Our analysis explores:

- The relationship between lease size and proximity to public transportation
- Trends in leasing before and after the pandemic
- Spatial changes in leasing across Manhattan ZIP codes

## 🗺️ Dataset & Methods

- **Data Source:** Savills Commercial Lease Dataset (specifically in Manhattan, NY)
- **Geocoding:** Used external tools to generate geographic coordinates for lease locations and nearby subway stations
- **Distance Calculations:** Estimated Euclidean (Pythagorean) distances between each lease and its closest subway station
- **Pre/Post-Pandemic Split:** Focused on new leases signed annually to remove noise from long-standing leases

## 📊 Analysis Highlights

- **No correlation** was found between lease price or area and distance to the nearest subway station, suggesting good transport zoning across Manhattan.
- **Box plots** of lease sizes indicate that larger lease areas have become more common **post-pandemic**.
- **Heatmaps** of ZIP codes show a shift in leasing activity from Downtown to Midtown and more historic, high-foot-traffic regions.
- **Larger centralized office spaces** are becoming more attractive, particularly in industries like technology and finance.

## 🧩 Conclusions

- The market trend suggests companies may be consolidating into larger office spaces in central areas, rather than spreading across multiple smaller locations.
- Midtown Manhattan appears to be gaining popularity for new leases, likely due to tourism, accessibility, and appeal to younger talent.
- We recommend that Savills prioritize listings with larger areas in historic neighborhoods, targeting clients with rising disposable income and centralized office preferences.

## 📁 Project Deliverables

- [📊 Project Slides](#) *(https://docs.google.com/presentation/d/1yPdYiSZOybWGVkm2KX0ibRc1nKQ_yeXEQE3NDjOLehE/edit?usp=sharing)*

---

*Note: Due to limited sample size in certain industry sectors, some conclusions are preliminary and warrant further investigation.*
