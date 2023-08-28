# Analysis of biases in the T-REx benchmark

The [T-REx](https://aclanthology.org/L18-1544.pdf) benchmark is one of the tests used in the [LAMA](https://github.com/facebookresearch/LAMA) probe. Here, I am investigating the distributions of genders and locations represented in T-REx. Skewed distributions of genders and locations in benchmarks used for the evaluation of language models can lead to a validation of biases. 

## Findings so far
| Gender          | Count |
|-----------------|-------|
| male            | 7494  |
| female          | 1146  |
| NA              | 107   |
| non-binary      | 2     |
| trans woman     | 2     |
| female organism | 1     |

For 107 cases, no gender information is provided in Wikidata, e.g. if the entity is not a single person but a group.