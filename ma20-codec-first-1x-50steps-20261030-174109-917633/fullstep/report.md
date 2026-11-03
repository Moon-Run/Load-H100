# MA20 vs MA11

Candidate: `Q0`; complete optimizer steps: 800.

| Trial | MA11 ms | MA20 ms | Paired speedup %, 95% CI |
| --- | ---: | ---: | --- |
| compare1 | 611.206 | 594.822 | 2.548 [-0.614, 6.795] |

Performance increment validated: False.

| Arm | Mean loss | Final loss | Final gradient norm |
| --- | ---: | ---: | ---: |
| MA11 | 3.7933638 | 0.0003057346 | 0.018002459 |
| Q0 | 3.0710555 | 0.0095061827 | 0.2984279 |

| Paired trajectory drift across all blocks | Maximum absolute difference | Maximum relative L2 |
| --- | ---: | ---: |
| loss | 5.5870824 | 0.26603284 |
| grad_norm | 13.648115 | 0.79058829 |

Accuracy equivalence validated: False. No short-run drift threshold is inferred.

Codec gates and finite short synthetic training do not establish accuracy equivalence or long-term convergence.
