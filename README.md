# Comparison of accuracy between the baseline and inference intervention augmentation on LLaMA2-7B.


| Number Length | 2      | 3      | 4       | 5       | 6        | 7       | 8       | 9       | 10      | 11    |
|--------------|--------|--------|---------|---------|----------|---------|---------|---------|---------|-------|
| Baseline (Llama2-7B)      | 0.955  | 0.933 | 0.853 | 0.693 | 0.363 | 0.132 | 0.044 | 0.006 | 0.0007  | 0  |
| Augmentation | 0.942  | 0.923 | 0.883 | 0.793 | 0.663 | 0.432 | 0.264 | 0.200 | 0.155  | 0.131  |

Details: The length stops at 11 instead of 20 because the inference intervention experiment has to be conducted under a basic accuracy since inference intervention doesn't improve the modular addition performance.
