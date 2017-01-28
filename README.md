The aim of the project is to utilise machine learning in order to predict the consistency of SPO (Subject-Predicate-Object) triples that are extracted in an automated manner. We used a subset Freebase data to train our models. The subset data included 10M triples.
The key idea is to learn the correct sequence of SPOs based on the type of entities and predicates defined by Freebase schema.
For example, we re-interpret the triple below:
(Albert Einstein) (Born_In) (Ulm)
As:
(Person) (Born_In) (Location).
For the majority of similar true triples (facts), that sequence will remain the same. This can translate into the consistency of a triple.
