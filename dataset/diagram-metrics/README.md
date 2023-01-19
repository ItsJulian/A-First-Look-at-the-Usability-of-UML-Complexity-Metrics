# Diagram Metrics
This folder contains the calculated diagram metrics (as a CSV file) for the [Java Websockets](https://github.com/TooTallNate/Java-WebSocket) and [Mobile Media](https://github.com/julioserafim/MobileMedia) codebase. The different versions of the same codebase are combined in one file. So that there is one `class-diagram.csv` file for each repository and a `state-diagram.csv` just for the Mobile Media repository.

The metrics are calculated based on the formulas provided by the paper the metrics are presented in. More information about these metrics and references to their original paper can be found in our conference paper.

# Content
Using the table below, it is possible to directly go to the class and state diagram metrics for a specific repository.

> *Note that the first line of each csv file specifies the metrics presented in each column. The first column in each csv file specifies the specific software version used for the diagram metrics in that specific row.*

| Repository        | Class Diagram Metrics                                             | State Diagram Metrics                                          |
| ---               | ---                                                               | ---                                                            |
| Java Websockets   | [Class Diagram Metrics](./java-websockets/class-diagram.csv)      | *Not Available*                                              |
| Mobile Media      | [Class Diagram Metrics](./mobile-media/class-diagram.csv)         | [State Diagram Metrics](./mobile-media/state-diagram.csv)      |