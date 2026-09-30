# Covid-19 Data Exploration with SQL

An analysis of global Covid-19 data using SQL Server. I explored infections, deaths, and vaccinations across countries and continents, and built reusable queries for later visualizations.

## Questions I answered
- **How likely was someone to die after getting Covid?** Total cases vs total deaths (death percentage).
- **How much of the population got infected?** Total cases vs population.
- **Which countries had the highest infection rate** compared to their population?
- **Which countries and continents had the highest death counts?**
- **What do the global numbers look like?** Total cases, total deaths, and overall death percentage.
- **How fast did vaccination grow?** A rolling count of people vaccinated in each country, and the percentage of the population vaccinated.

## SQL skills shown
- Filtering, sorting, and grouping with `WHERE`, `GROUP BY`, `ORDER BY`
- Aggregate functions: `SUM`, `MAX`
- Joins across two tables (`CovidDeaths` and `CovidVaccinations`)
- Window functions: `SUM() OVER (PARTITION BY ...)` for rolling totals
- **CTEs** (Common Table Expressions)
- **Temp tables**
- **Views**, created to feed dashboards and visualizations
- Data type conversion with `CONVERT`

## Tools
- SQL Server (T-SQL)

## How to use this project
1. Load the data into two tables named `CovidDeaths` and `CovidVaccinations` in SQL Server.
2. Open the `.sql` file and run the queries one section at a time.

## Next step
Build a dashboard in Power BI or Tableau using the `PercentPopulationVaccinated` view.
