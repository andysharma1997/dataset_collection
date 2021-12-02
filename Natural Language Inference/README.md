## Definition
Natural language inference (NLI) is the task of determining whether a "hypothesis" is true (entailment), false (contradiction), or undetermined (neutral) given a "premise".

## Example:

```
Premise	|| Label ||Hypothesis
A man inspects the uniform of a figure in some East Asian country. || contradiction || The man is sleeping.
An older and younger man smiling. || neutral || Two men are smiling and laughing at the cats playing on the floor.
A soccer game with multiple males playing. || entailment ||Some men are playing a sport.
```

An NLI pre-trained model can be used for wide varity of downstream NLP tasks where the inference btween two calsses is required.

# Datasets
1. RTE[https://deepai.org/dataset/rte] 