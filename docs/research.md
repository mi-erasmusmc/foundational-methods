# Research

There are three main research pathways currently being investigated.

```mermaid
%%{init: {"theme":"default"} }%%
flowchart LR

subgraph P1["Context Aware Learning"]
  direction TB
  A1["Utilize existing clinical<br/>knowledge from taxonomies and<br>ontologies for clinical prediction"]
end

subgraph P2["Distributed Learning"]
  direction TB
  A2["Decentralized training of<br/>foundational representations;<br/>parameter sharing and updating"]
end

subgraph P3["Temporal Learning"]
  direction TB
  A3["Survival analysis, sequence<br/>modeling, time-to-event prediction,<br/>and risk stratification"]
end

%% force the three containers to sit left-to-right (hide the links)
A1 --- A2 --- A3
linkStyle 0 stroke:transparent,stroke-width:0;
linkStyle 1 stroke:transparent,stroke-width:0;
```
## Context Aware Learning

Utilize existing clinical knowledge from taxonomies and ontologies for clinical prediction.
- Knowledge graphs
- Graph neural networks
- Causality and counterfactuals
- Human-in-the-loop

## Distributed Learning

Decentralized training of foundational representations; parameter sharing and updating.
- Rare disease prediction
- Foundation models
- Federated learning
- Transfer learning

## Temporal Learning

Survival analysis, sequence modeling, time-to-event prediction, and risk stratification.
- Deep survival model
- Prescriptive modeling
- Generative transformer
