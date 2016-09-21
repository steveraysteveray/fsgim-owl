# fsgim-owl
This is an OWL implementation of the ANSI/ASHRAE/NEMA Standard 201-2016, commonly known as FSGIM (Facility Smart Grid Information Model).
It is compatible with TopBraid Composer Maestro, version 5.1 beta.
The file fsgim.ttl is an OWL file using the Turtle format, and contains all of the classes and properties specified in the UML model of the ASHRAE Standard, published in 2016.
While attempts have been made to be as consistent as possible with the UML specification, there are a few cases where there are differences, such as the UML "redefines" relation, which is inconsistent with the set theory underlying OWL. 
