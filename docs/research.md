# Research

There are three main research pathways currently being investigated.

```mermaid
%%{init: {"theme":"default"} }%%
flowchart TB

subgraph TOP[" "]
  direction LR

  subgraph P1["Context Aware Learning"]
    A1["Utilize existing clinical<br>knowledge from taxonomies and<br/>ontologies for clinical prediction"]
  end

  subgraph P2["Distributed Learning"]
    A2["Decentralized training of<br/>foundational representations;<br/>parameter sharing and updating"]
  end

  subgraph P3["Temporal Learning"]
    A3["Survival analysis, sequence<br/>modeling, time-to-event prediction,<br/>and risk stratification"]
  end
end

subgraph BOTTOM["Foundational Methods"]
  B["Foundational research on data, metrics, etc."]
end

%% force BOTTOM below the pillars (hide the lines)
A1 --- B
A2 --- B
A3 --- B

linkStyle 0 stroke:transparent,stroke-width:0;
linkStyle 1 stroke:transparent,stroke-width:0;
linkStyle 2 stroke:transparent,stroke-width:0;

%% hide only the TOP container border/background (keep BOTTOM visible)
style TOP fill:transparent,stroke:transparent;
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
