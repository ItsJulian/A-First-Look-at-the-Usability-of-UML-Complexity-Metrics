# Practical Validation of UML Complexity Metrics

In this repository, you can find the dataset used in our research titled 'Practical Validation of UML Complexity Metrics'.

# Research
We analyzed the usability of different UML diagram complexity metrics using well-researched and widely used software complexity metrics. More specifically, UML state diagrams and class diagrams.

In order to conduct this analysis, we focused on two open-source codebases called [Java Websockets](https://github.com/TooTallNate/Java-WebSocket) and [Mobile Media](https://github.com/julioserafim/MobileMedia).

We first created class and state diagrams for all versions of the selected codebases. We then calculated the complexity metrics for these diagrams. Besides these diagram complexity metrics, we also used multiple tools to generate the software metrics of these codebases.

The last step of generating our dataset was then to calculate the correlation between the different diagrams and software complexity metrics.

# Content
This dataset consists of the following (type of) files:

## Class Diagrams
We created a class diagram for each version of the [Java Websockets](https://github.com/TooTallNate/Java-WebSocket) and [Mobile Media](https://github.com/julioserafim/MobileMedia) codebase. For this, we used the tool [Visual Paradigm](https://www.visual-paradigm.com/).

We used a tool we developed ourselves to help us determine the correctness of these diagrams. This tool analyzes a UML diagram and turns the diagram into a log file; this file could then be used, in combination with a difference report between the current and previous software versions, to help us determine the correctness of these diagrams.

[Click Here](./dataset/class-diagrams/) to go to the class diagrams.

## State Diagrams
We created a state diagram for each version of the [Mobile Media](https://github.com/julioserafim/MobileMedia) codebase. For this, we also used the tool [Visual Paradigm](https://www.visual-paradigm.com/).

We used the same tool as with the class diagrams to help us determine the correctness of these diagrams.

[Click Here](./dataset/state-diagrams/) to go to the state diagrams.
