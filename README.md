# SBEO : Smart Building Evacuation Ontology

The Smart Buildings Evacuation Ontology (SBEO) is proposed to acquire knowledge of emergency evacuation (or egress) and to provide safe evacuation paths to the occupants of buildings during hazardous circumstances in a building. The goal of this ontology is not only to provide safe paths to the people, but also the paths will be feasible for people with respect to their physical characteristics and preferences. In this regard, we propose a knowledge base system for emergency evacuation in which we use the concept of a smart building. First, we define the concepts that are necessary to develop the proposed systems. Second, we develop the hierarchy to use these concepts. Third, we define the properties and characteristics of these concepts. Fourth, we introduce role restrictions, and at last, we introduce instances for particular scenarios to validate our foundation knowledge base. We use three different concepts in our ontology and integrate them with respect to our requirements. The first concept is knowledge about the building geometry, the second concept is the knowledge about the momentary situation of the building, and the third concept is the knowledge about the occupants of the building. We reuse seas:BuildingOntology to get geometry of the buildings. Also, it may limit the overlap with the following existing specialized ontologies such as FIEMSER ontology, gbXML ontology and ifcOWL ontology.


We have used SBEO as a base model to create Assertion Boxes for different scenarios. These can be found in the Examples directory. 

![](Figures/SBEO_Class_Property_Diagram_Minimal.png)
