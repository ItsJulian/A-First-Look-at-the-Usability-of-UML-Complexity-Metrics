# Practical Validation of UML Complexity Metrics

In this repository, you can find the dataset used in the research titled 'Practical Validation of UML Complexity Metrics'.

*This research is executed by Julian Meurer, Sjoerd Plat en Joep Overmars and supervised by Tannaz Zameni. Contact information of the researchers and supervisor can be found at the end of this file.*

# Research
In this research, the usability of different UML diagram complexity metrics is analyzed using well-researched and widely used software complexity metrics. 

In order to conduct this analysis, the two open-source codebases called [Java Websockets](https://github.com/TooTallNate/Java-WebSocket) and [Mobile Media](https://github.com/julioserafim/MobileMedia) are used.

# Workflow
The first step in the research was to create class and state diagrams for all versions of the selected codebases. Then the selected diagram complexity metrics were used to determine the complexity of each diagram. Besides these diagram metrics, the selected software metrics were used to determine the software complexity of the same codebases. The last step of generating the dataset was then to calculate the correlation between the different diagrams and software complexity metrics.

# Content
This dataset consists of the following (type of) files:

## Class Diagrams
This dataset contains the created class diagram  (as an XML file) for each version of the [Java Websockets](https://github.com/TooTallNate/Java-WebSocket) and [Mobile Media](https://github.com/julioserafim/MobileMedia) codebase. The tool [Visual Paradigm](https://www.visual-paradigm.com/) was used to create these diagrams.

To help determine the correctness of these diagrams, a custom-developed tool was used to convert a UML diagram into a structured text file. This file could then be used, in combination with a difference report between the current and previous software versions, to help determine the correctness of the diagrams. The log file itself can also be found in this dataset.

[Click Here](./dataset/class-diagrams/) to go to the class diagrams.

## State Diagrams
This dataset also contains the created state diagram (as an XML file) for each version of the [Mobile Media](https://github.com/julioserafim/MobileMedia) codebase. The tool [Visual Paradigm](https://www.visual-paradigm.com/) was used to create these diagrams.

The same tool, as used for determining the correctness of the class diagrams, is used for the state diagrams.

[Click Here](./dataset/state-diagrams/) to go to the state diagrams.

## Diagram Metrics
This dataset also contains the calculated diagram metrics (as a CSV file) for each version of the [Java Websockets](https://github.com/TooTallNate/Java-WebSocket) and [Mobile Media](https://github.com/julioserafim/MobileMedia) codebase. 

The metrics are calculated based on the formulas provided by the paper the metrics are presented in. More information about these metrics and references to their original paper can be found in our conference paper.

[Click Here](./dataset/diagram-metrics/) to go to the diagram metrics.

# Contact
Below you will find the contact information of the researchers and supervisor.

| Julian Meurer | Sjoerd Plat | Joep Overmars | Tannaz Zameni |
| --- | --- | --- | --- | 
| julian@meurer.email <br> https://github.com/ItsJulian |  | https://github.com/Ilomiswir |  | 
