# Clarifications to the published paper

This file adds detail to three passages of the published paper so that readers can interpret them precisely. The main findings are unchanged: AAVE and NP are associated with more negative housing-relevant adjectives than SAE, each through a distinct stereotype cluster, and the contrast between NP and NSE separates prestige from identity. All numbers below are from the results reported in `SUPPLEMENTARY.md`.

## 1. NSE results in the neighbor and roommate scenarios

Section 4.3 reports an overall mean q for NSE in each scenario (+0.024 tenant, −0.156 neighbor, −0.088 roommate). These overall values average positive and negative adjectives together, weighted by the number of adjectives of each valence in the lexicon. Because a negative q means different things for the two valences, the overall value is best read alongside the valence-specific results.

- For a negative adjective, q < 0 means the model attaches that trait to NSE less readily than to SAE, which is favorable treatment.
- For a positive adjective, q < 0 means the model attaches that trait to NSE less readily than to SAE, which is unfavorable treatment.

| Scenario | Negative adjectives | Positive adjectives | Overall value in the paper |
|---|---|---|---|
| Tenant | q = −0.071 (d = −0.085) | q = +0.159 (d = +0.197) | +0.024 |
| Neighbor | q = −0.236 (d = −0.275) | q = −0.018 (d = −0.021) | −0.156 |
| Roommate | q = −0.180 (d = −0.246) | q = +0.024 (d = +0.034) | −0.088 |

Read by valence, NSE is associated with fewer negative adjectives than SAE in all three scenarios, consistent with Figures 4 and 5. The negative overall values in the neighbor and roommate scenarios reflect this suppression of negative adjectives, so they should not be read as a penalty against NSE.

The context-dependence that the paper describes appears in the positive adjectives. NSE's advantage on positive traits is clear in the formal tenant context and close to zero in the neighbor and roommate contexts. The accurate summary is therefore that models favor NSE most in tenant evaluation and that this favorability narrows, rather than reverses, as social proximity increases. This reading applies to the related sentences in the abstract, Section 1, Section 5 and the Conclusion. NP and NSE, which share national and racial identity, move in opposite directions on negative adjectives in every scenario, so the paper's conclusion that prestige operates independently of identity holds.

## 2. Wording in the abstract on NP

The abstract describes NP as "receiving the most severe penalization overall." This refers to the tenant scenario, where NP has the largest negative-adjective elevation of any dialect, and to the null-attribute comparison, where NP shows the largest excess in every cell. Pooled across all scenarios, AAVE and NP do not differ on negative adjectives (Dunn's test, Bonferroni p = 1.00), as Section 4.1 reports. The per-model counts in Section 4.5 give the precise extent of the consistency described as "across all ten models."

## 3. Perplexity and negative q-scores

The correlation of r = +0.923 in Section 5 is computed across the four dialect means (two-sided p = 0.077), so it describes the pattern across the four varieties rather than testing an association. The per-model perplexity values behind it are in Section 7 of `SUPPLEMENTARY.md`.
