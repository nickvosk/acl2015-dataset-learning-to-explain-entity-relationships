# acl2015-dataset-learning-to-explain-entity-relationships

Dataset for the ACL 2015 paper "Learning to Explain Entity Relationships in Knowledge Graphs" by Nikos Voskarides, Edgar Meij, Manos Tsagkias, Maarten de Rijke and Wouter Weerkamp. In this paper, we present a method for automatically explaining relationships between entities.

The file ACL2015-dataset.csv has the following format :

- QueryID
- Entity1URL
- Entity2URL
- Relevance
	- Perfect
	- Excellent
	- Good
	- Fair
	- Bad
		- Wrong entities
		- Same Entities/different relationship
		- Wrong relationship
- Relationship
- Description

If you have any questions, please contact n.voskarides AT uva.nl