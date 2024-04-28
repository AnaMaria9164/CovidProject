#  CovidProject

This project involves exploring COVID-19 data using SQL queries. 
Various skills are utilised in the process, including Joins, CTEs (Common Table Expressions), Temp Tables, Window Functions, Aggregate Functions, Creating Views, and Converting Data Types.

## Data

The initial exploration begins with selecting data from the CovidDeaths table in the CovidProject database, filtering out records where the continent is not null and ordering the results by location and date.

###### Total Cases vs Total Deaths
This query calculates the death percentage based on total cases and total deaths in a specific location (here, locations containing 'King'), displaying the likelihood of dying if one contracts COVID-19 in that country.

###### Total Cases vs Population
This query showcases what percentage of the population is infected with COVID-19 in various locations.

###### Countries with Highest Infection Rate
This query identifies countries with the highest infection rate compared to their population.

###### Countries with Highest Death Count
This query lists countries with the highest death count per population.

###### Continents with the Highest Death Count
This query displays continents with the highest death count per population.

###### Global Numbers
This query provides global COVID-19 statistics, including total cases, total deaths, and the death percentage.

###### Total Population vs Vaccinations
This query illustrates the percentage of the population that has received at least one COVID-19 vaccine dose.

###### View and Temp Table
These sections involve creating a view and a temporary table to store data for later visualisations.



