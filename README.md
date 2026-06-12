# L-HAF Studio

An interactive, single-file research companion and exploratory workbench that implements the **Labeled Hashtagged Argumentation Framework (L-HAF)**.

## About the Tool
L-HAF Studio guides users through the entire lifecycle of labeled hashtagged argumentation frameworks, transforming a multi-topic debate into a stable, context-sensitive consensus posture. 

The application visualizes the step-by-step unfolding pipeline, executing:
1. **Base Construction:** Instantiating arguments, attacks, and rendering the underlying semantic hashcloud graph.
2. **Distance Analysis:** Computing geometric separation using six alternative distance functions (including Hausdorff and Geodesic variants) and mapping localized neighborhood boundaries.
3. **The L-HAF Pipeline:** Binding arguments to formal conclusion literals ($\mu$), executing sub-argument extraction ($\mathcal{A}^+$), and calculating centrality-based valuation functions ($v$).
4. **Dynamic Labeling Registry:** Running the distance-aware attack weakening procedure ($\alpha, \delta$) to categorize nodes into Unchallenged (U), Weakened (W), or Neutralized (N) statuses.

## How to Run
L-HAF Studio is built as a portable, fully generic single-file deployment:
1. Download or clone this repository.
2. Open the `.html` file directly in any modern web browser. *No installations or local servers are required*.

The tool includes preloaded illustrative scenarios (such as an Advanced Persistent Threat Ransomware Defense scenario) and allows users to dynamically import custom JSON instances.
