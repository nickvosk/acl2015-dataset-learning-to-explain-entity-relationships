# ACL 2015 paper dataset

This repository contains the ataset for the ACL 2015 paper "Learning to Explain Entity Relationships in Knowledge Graphs" by Nikos Voskarides, Edgar Meij, Manos Tsagkias, Maarten de Rijke and Wouter Weerkamp.

In this paper, we present a method for automatically explaining relationships between entities.

The file `ACL2015-dataset.csv` contains the annotated sentences and it has the following format :

- `QueryID` the query id

- `Entity1URL` the url of entity1

- `Entity2URL` the url of entity2

- `Relationship` The automatically produced relatioship between the two entities, with the form <Entity1Type, Relationship, Entity2Type>.

- `Relevance` The relevance judgement for the sentence with respect to the two entities and the relationship. We use a five-level graded relevance scale (perfect, excellent, good, fair, bad). The annotators also marked sentences that did not fit in that scale because of different issues (Wrong entities, Same Entities/different relationship, Wrong relationship, Other). In our experiments we treated all the sentences with such issues as bad sentences.

- `Description` The automatically extracted wikipedia candidate sentence.

For more details about the dataset, please refer to the paper.

If you have any questions, please contact n.voskarides AT uva.nl