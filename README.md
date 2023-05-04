# data-viz


## About the project

### Data Ingestion
CSV file from the [owid/covid-19-data ](https://github.com/owid/covid-19-data) GitHub repository.


### Data Transformation
Simple pandas transformatios to cleanse and filter data to contain metrics from only the United States and display a plot.


### Data Load
Save data on a Delta Live table.


## Best Practices
- Creating a shareable module.
- Unit testing the shared code.
- Apply GitHub Actions workflow CI/CD platform to execute and test Databricks jobs whenever changes are merged into the GitHub repository. 
