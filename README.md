# data-viz


## About the project

No-frills DataBricks batch ETL pipeline to .... 

### Data Ingestion
CSV data from [owid/covid-19-data](https://github.com/owid/covid-19-data).


### Data Transformation
Pandas transformatios to cleanse and filter data to contain metrics from only the United States and display a plot.


### Data Load
Save data on a Delta Live table.


## Pipeline has
- Unit testing of the shared module.
- CI/CD with GitHub Actions workflow.

## To-Dos
- Expand to handle large amount of data from multiple types of data sources and formats.
- Add data streaming.
- Add orchestration.
