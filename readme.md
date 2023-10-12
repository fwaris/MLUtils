# MLUtils

A set of utility functions that support working with Microsoft.ML from F#:

- Manipulation of the ColumnInformation data structure to re-bin columns into the desired types after the Microsoft.ML.AutoML type inference step
- Print out the nested transforms learned by AutoML during an experiment run
- Schema and column information utility functions
- Operator to join transformations into a composite pipeline
- Generate an F# record type from IDataView schema
- Make F# CLIMutable records work with ML.Net API when loading/creating IDataView from enumberables. This deals with the fields with '@' in their names by creating a clean schema
