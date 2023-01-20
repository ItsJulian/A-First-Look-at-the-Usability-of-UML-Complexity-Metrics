# Metric Correlation
This folder contains the calculated correlation between the diagram and software metrics (as a CSV file) for both [Java Websockets](https://github.com/TooTallNate/Java-WebSocket) and [Mobile Media](https://github.com/julioserafim/MobileMedia) codebases. 

The metrics are calculated using the python package [Pandas](https://pandas.pydata.org/) and are based upon the [Software](../software-metrics/) and [Diagram Metrics](../diagram-metrics/).

# Content
Using the table below, it is possible to directly go to the correlation files for a specific repository and diagram type.

> *Note that the first row of each CSV file specifies the software metrics and the first column specifies the diagram metrics. All other columns will represent the correlation between the software (first row, same column) and the diagram metrics (first column, same row).*

| Repository        | Class Diagram Metric Correlation                                        | State Diagram Metric Correlation                                     |
| ---               | ---                                                                     | ---                                                                  |
| Java Websockets   | [Class Diagram Metric Correlation](./java-websockets/class-diagram.csv) | *Not Available*                                                      |
| Mobile Media      | [Class Diagram Metric Correlation](./mobile-media/class-diagram.csv)    | [State Diagram Metric Correlation](./mobile-media/state-diagram.csv) |