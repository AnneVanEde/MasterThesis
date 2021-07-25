# ENCODE: Master Thesis

DOD and its substrategy ECS are promising and more performant alternatives to OOD, especially for the game industry However, converting an existing project from OOD to ECS is challenging. Additionally, little scientific research is available on DOD and ECS.

This thesis catalogues information on ECS itself and its design strategies. The results show that an ECS design should be created around how the data is used and to what domain it belongs. We also formulate basic requirements for the visualization of those designs. Showing the connection within an ECS design and between the original OOD and the generated ECS design is essential.
    
This thesis proposes a technique to convert a design from OOD to DOD. This conversion technique uses \textit{static program analysis} to extract the source design structure, which is then stored in an intermediate data model. From this intermediate model, a design is created. This design can be tailored to the project requirements with the use of planning profiles.
    
We demonstrate the effectiveness of this conversion technique by creating an OOD to ECS conversion tool named ENCODE. The created designs are compared to manually created designs. The results show that ENCODE is capable of creating designs with entities, components, and systems that correspond with the original OODs and the manual designs. 


## Quick Shortcuts
* [ENCODE Tool](https://github.com/AnneVanEde/encode)
* [ENCODE Master Thesis PDF](https://github.com/AnneVanEde/MasterThesis/blob/main/ENCODE%20-%20Thesis%20-%20A.E.%20van%20Ede.pdf)
* [All Interview Transcriptions](https://github.com/AnneVanEde/MasterThesis/tree/main/Transcriptions)
* [All Created ECS Designs](https://github.com/AnneVanEde/MasterThesis/tree/main/Created%20ECS%20Designs)


![Alt text](https://github.com/AnneVanEde/MasterThesis/blob/56c3dbf8f7da85c343a6f625cb4b63204f51e22e/_img/View_Tab.png)
