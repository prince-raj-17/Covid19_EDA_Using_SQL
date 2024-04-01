# SQL : COVID-19 Exploratory Data Analysis

This project involves exploring COVID-19 data sourced from [Our World in Data](https://ourworldindata.org/covid-deaths) covering the period from February 20, 2020, to July 6, 2022. The data is analyzed using Microsoft SQL Server Management Studio to derive insights into the global impact of the pandemic.

## Contents
1. [Introduction](#introduction)
2. [Data Exploration](#data-exploration)
3. [Queries and Analysis](#queries-and-analysis)
4. [Views](#views)
5. [Conclusion](#conclusion)

## Introduction
The COVID-19 pandemic has significantly impacted global health, economies, and societies. This portfolio project aims to showcase the skills of a data analyst by exploring and analyzing COVID-19 data using SQL queries. The project utilizes data from Our World in Data, focusing on cases, deaths, vaccinations, and population statistics.

## Data Exploration
The dataset comprises two main tables:
- `covid_deaths`: Contains information on COVID-19 deaths, including location, date, total cases, new cases, total deaths, etc.
- `covid_vaccinations`: Provides data on COVID-19 vaccinations, including location, date, total vaccinations, new vaccinations, etc.

## Queries and Analysis
The SQL queries conducted for data analysis include:
1. Overall world view: Summarizes global population, total cases, and total deaths.
2. Continent-based analysis: Analyzes total cases and total deaths by continent.
3. Countries with the highest death count: Identifies countries with the highest death count.
4. Countries with a higher infection rate: Lists countries with the highest percentage of population infected.
5. Cases and deaths by date and country: Provides a detailed overview of cases and deaths by date and country.
6. Total cases vs. total deaths in India: Analyzes the total cases, total deaths, and death percentage in India.
7. COVID-19 overview of India: Provides an overview of COVID-19 cases, deaths, and vaccination status in India for June 2022.
8. New cases and deaths globally: Presents global trends of new cases and deaths over time.
9. Vaccinations vs. new cases globally: Compares vaccinations with new cases globally.
  
## Views
A view named `Percent_Population_Vaccinated` is created to store data for future analysis. It includes information on location, date, population, new vaccinations, and a rolling count of vaccinated individuals.

## Conclusion
This portfolio project demonstrates the ability to analyze COVID-19 data using SQL queries. It provides insights into the global impact of the pandemic, including trends in cases, deaths, vaccinations, and population infection rates. The analysis contributes to understanding the dynamics of the COVID-19 pandemic and can be used for further research and decision-making processes.

## Credit
This EDA is performed by [Prince Raj.](https://www.linkedin.com/in/princeraj17/)