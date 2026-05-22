# Building an AI-Driven Investor Matching Model for VC-Backed Startups

Master's thesis, International School of Management Munich, October 2025.
Advisor: [name].

## Summary

This thesis develops and evaluates a hybrid AI model for matching
VC-backed startups with the investors most likely to fund them.
The model combines collaborative filtering, content-based filtering,
and network centrality signals across a dataset of 12,793 startups
and 17,912 investors compiled from Crunchbase, LinkedIn, and PitchBook.

## Result

The hybrid model improved average investor-startup compatibility by
2.11% over the baseline. Network centrality was identified as the
key differentiating feature. On strict ranking metrics (MAP and
NDCG@10), the baseline retained a narrow edge, surfacing a real
trade-off between average compatibility lift and strict top-K
ranking accuracy. This trade-off, and what it means for production
use in a VC sourcing workflow, is the core contribution.

## Method

- Mixed-methods design: qualitative interviews with VC operators
  plus quantitative AI modeling and baseline comparison.
- Data: Crunchbase, LinkedIn, PitchBook (12,793 startups, 17,912
  investors).
- Models: collaborative filtering, content-based filtering,
  graph-based network centrality, hybrid ensemble.
- Evaluation: average compatibility lift, MAP, NDCG@10, ablation
  by feature class.

## Read the full thesis

[Investor_Matching_Thesis_Alvaro_Ibarra.pdf](./Building_an_AI-Driven_Investor_Matching_Model_for_VC-backed_Startups.pdf)

## Author

Alvaro Ibarra Martin del Campo
Chief of Staff & GTM Operations, Korial
[[LinkedIn](https://www.linkedin.com/in/alvaro-ibarra-mdc/)]
