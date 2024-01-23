# Thoughts on data pipelines

Assuming a pipeline being modeled as a series of transformations. Think of it as a unidirectional graph.

* I'd like to be able to inject data at every individual box rather than just at the first one. Also have at least a referrence output for a referrence input.
