The paper "A Review of Federated Learning in Renewable Energy Applications: Potential, Challenges, and Future Directions" by Albin Grataloup et al. presents a comprehensive overview of applying Federated Learning (FL) in the renewable energy sector.

Federated Learning (FL) is a decentralized machine learning method where data stays local, and only model updates are shared with a central server, preserving data privacy.
FL Algorithms discussed in this paper:

Requirement	Relevant in Thesis?	Implication
Non-IID Data Distribution	✅ Likely	Prefer FedProx or FedDyn
Limited Edge Compute	✅ Yes	Use FedAvg or FedProx
Small Number of Clients	✅ Yes	Avoid complex aggregation (FedAvg is good)
Low Communication Overhead	✅ Yes	MQTT-friendly algorithms preferred (FedAvg)
Fast Convergence Needed	⚠️ Possibly	May consider FedOpt if convergence is slow
Task is Classification	✅ Yes	Choose algorithms proven for classification

