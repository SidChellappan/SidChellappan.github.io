LSTM Venture Success Forecaster

This project is an interactive venture intelligence tool that uses a stacked Long Short-Term Memory (LSTM) neural network to evaluate startup trajectories across funding stages and estimate exit probability.

The system models a company’s evolution from Seed through Series D by analyzing four key signals at each stage: funding amount, headcount growth, burn rate, and revenue multiple. Rather than treating companies as static snapshots, the model captures temporal momentum, how these signals change over time to identify patterns associated with successful outcomes.

Users input stage-by-stage metrics through an interactive interface, and the model processes the sequential data to generate:

A predicted exit probability
An investment confidence tier (Avoid → Strong Buy)
Stage-level signal scores
Key strengths and risk factors
A concise investment recommendation

The frontend provides real-time visualization of results, including trajectory charts, feature profiles, and portfolio positioning, making the model’s reasoning interpretable and actionable.

This project demonstrates how sequence modeling can be applied to venture capital decision-making, emphasizing that trajectory dynamics, not just point-in-time metrics, drive investment outcomes.
