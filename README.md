# Energy Data Commons (Service-Oriented System)
This project was a part of the course Service Oriented Architecture and the goal was to tackle Energy Data Commons as a challenge provided by [Waag Future Lab](https://waag.org/en/).  This project tries to build a system fostering energy independence in local communities through knowledge sharing, electricity trading, consumption analysis, supporting communities & reducing reliance on the national grid. I particularly contributed focusing on the **Business Service: Statistical Data Repository System** to provide anonymized datasets to the researchers to understand the energy usage and trading patterns of the community. They can develop important data-driven insights that can be useful also to the government in encouraging or supporting other local communities to practice similar models to contribute to the sustainable ecosystem. 

## Activity Diagram
The activity diagram talks about the flow of how each activity happens in a flow and what data is provided for each activity by relevant stakeholders.

<img src = "https://raw.githubusercontent.com/Ichchhie/Energy-Data-Commons/main/Activity%20diagram.png" width="700"/>

## Component Diagram
The component diagram visually illustrates the architectural components and highlights the stakeholders with the color-coded components responsible for providing them. There are
five different stakeholders are involved in this business service, so the components have been organized according to each stakeholder to provide clearer context and relevance.

<img src = "https://raw.githubusercontent.com/Ichchhie/Energy-Data-Commons/main/Component%20Diagram.jpg" width="800"/>

## Data Model Diagram
<img src = "https://raw.githubusercontent.com/Ichchhie/Energy-Data-Commons/main/Data%20model.png" width="800"/>
The Data model diagram shows all the data components and their associated attributes. It also shows the relationship between components.


## Wrapping this service as a RESTful APIs
The business service is however handled under ElecticityTrendService which plays a crucial role in giving anonymized data to the researchers in the form of trends which is the functional requirement of this business service. It analyzes and forms trends in electricity usage, consumption, and trading over time. It provides the complete API documentation that can be found [here](https://github.com/Ichchhie/Energy-Data-Commons/blob/main/api-documentation.pdf). It details the essential endpoints, request and response data formats, and parameters wherever needed to interact with the API effectively.




