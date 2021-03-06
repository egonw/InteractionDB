Interaction Bridge Database
==========================

This is a java application to create a BridgeDb derby database to map identifiers of interactions from 
different databases to each other. It has been created using the interaction mapping from Rhea 
(http://www.ebi.ac.uk/rhea/). The identifier from Rhea is mapped to identifiers from Enzyme Code, 
EcoCyc, MetaCyc, Macie, Reactome, Kegg Reaction, Unipathway, and Uniprot. This database can be used to 
annotate interactions in PathVisio(http://www.pathvisio.org/) and Wikipathways
(http://wikipathways.org/index.php/WikiPathways).

You can build the program by checking out the source code and running the build file using ant.

Or, alternatively you can use the program directly without having to first build it, by downloading the pre-built 
InteractionDB.jar file from the dist folder and run the jar providing the absolute path of the interaction database 
to be created as an argument.

For example: 

java -jar InteractionDB.jar "/home/anwesha/PathVisio-Data/gene databases/Interactions.bridge"
