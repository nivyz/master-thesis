Medium voltage circuit breakers are sophisticated electrical protection devices designed to safeguard electrical circuits from damage caused by overloads or short circuits. Unlike fuses, which operate once and must be replaced, circuit breakers can be reset after interrupting fault currents, allowing for continued operation of the protected circuit. Their primary function is to detect fault conditions and rapidly interrupt the flow of electricity, preventing potential equipment damage or system failure. The evolution from older technologies to modern vacuum interrupters has significantly improved reliability, performance, and service life.
Key Ratings and Specifications
Medium voltage circuit breakers operate within specific voltage ranges, typically 5, 8, 15, 27, and 38 kV1. Their current-carrying capacity (primary current rating) generally ranges from 1,200 to 4,000 amps, with some specialized models capable of handling up to 5,000 amps when equipped with forced air cooling.
The fault-breaking capability, which represents the breaker's ability to safely interrupt short circuit currents, ranges from 16,000 to 75,000 amps depending on the design1. This critical specification determines the maximum fault current the breaker can safely interrupt without damage to itself or surrounding equipment.
Arcing Technologies and Interruption Mechanisms
Throughout the evolution of medium voltage circuit breakers, several technologies have been employed to extinguish the electric arc that forms when contacts separate under load:
1.	Vacuum interrupters - Currently the dominant technology in the market
2.	SF6 (sulfur hexafluoride) interrupters - Similar to vacuum but using SF6 gas
3.	Oil and air magnetic interrupters - Older technologies largely phased out of modern applications1
The mechanism that physically separates the contacts also varies between designs, with two primary approaches:
1.	Spring-charged mechanisms - The traditional and most common design
2.	Magnetic actuator mechanisms - A newer technology offering certain advantages
Construction and Components
Modern medium voltage circuit breakers consist of several critical components working together to provide safe and reliable interruption of fault currents. The key elements include:
Main Components

Vacuum Interrupter Technology
+++++++++++++++++++++++
SICAM A8000
Automation and remote terminal units – SICAM A8000 Series - Siemens Global

1. Asset Management of Vacuum Circuit Breakers
1.1 General Definition of Asset Management
Asset management in electrical engineering refers to the systematic process of operating, maintaining, upgrading, and disposing of physical assets in a cost-effective manner. The goal is to maximize asset lifespan while ensuring safety, reliability, and performance. This is particularly critical in the power sector, where electrical infrastructure, including circuit breakers, must function optimally to prevent disruptions in power supply. Effective asset management integrates condition monitoring, predictive maintenance, and risk assessment to optimize performance and minimize downtime [1][2].
1.2 Asset Management in the Context of Vacuum Circuit Breakers
For Vacuum Circuit Breakers (VCBs), asset management focuses on ensuring operational reliability, reducing unplanned outages, and optimizing maintenance schedules. Since VCBs are key components in medium-voltage switchgear, their failure can lead to cascading effects in power distribution systems. The primary asset management strategies for VCBs include:
•	Lifecycle Assessment: Evaluating VCB aging mechanisms, including contact erosion and insulation degradation.
•	Performance Optimization: Monitoring operational efficiency through real-time condition monitoring (CM) data.
•	Failure Risk Mitigation: Using predictive analytics to detect early warning signs and prevent unexpected failures [3][4].
•	Health Index (HI) Framework: A diagnostic model that quantifies the overall health of a VCB, allowing for predictive maintenance scheduling [5].
1.3 Key Diagnostic Parameters for Asset Management
The Health Index (HI) framework helps quantify VCB degradation based on the following parameters:
•	Loss of Vacuum: Reduced dielectric strength increases partial discharge risk and arc instability [6].
•	Contact Erosion: The number of switching operations determines how quickly contacts degrade, affecting performance [7].
•	Mechanical Failures: Grease degradation in actuator mechanisms leads to reduced switching efficiency over time, which can be modeled using Arrhenius-based lifetime prediction [8].
•	Electrical Failures: Leakage currents due to surface contamination and condensation, assessed using IEC TS 60815-1 pollution severity standards [9].
1.4 Maintenance Strategies for VCBs
Effective maintenance is central to asset management, and VCBs typically follow one of the following strategies:
•	Reactive Maintenance: Performing repairs only after failure occurs, leading to higher operational risks.
•	Preventive Maintenance: Conducting scheduled inspections based on manufacturer guidelines to reduce failure risks [10].
•	Condition-Based Maintenance (CBM): Utilizing sensor-based monitoring (coil current, vibration, partial discharge) to schedule maintenance when degradation is detected [11].
•	Predictive Maintenance: Leveraging AI-based models to analyze trends in coil current, vibration patterns, and operational anomalies to forecast failures before they happen [12].
1.5 HI-Based Predictive Maintenance Framework
An HI-based scoring system quantifies the impact of different degradation mechanisms (vacuum loss, contact wear, etc.) to predict VCB lifespan. The HI model can be implemented across edge, fog, and cloud computing layers to optimize maintenance scheduling and reduce downtime [13].
2. Condition Monitoring of Vacuum Circuit Breakers
2.1 General Definition of Condition Monitoring
Condition Monitoring (CM) is the process of continuously or periodically assessing the health of electrical assets to detect early signs of wear, degradation, or failure. CM helps in:
•	Reducing downtime by identifying issues before failure occurs.
•	Enhancing safety by preventing hazardous electrical faults.
•	Optimizing maintenance costs by allowing for targeted interventions rather than broad replacements [14].
2.2 Condition Monitoring in the Context of VCBs
For VCBs, condition monitoring is critical to ensuring their functionality in medium-voltage grids. The key objectives of CM in VCBs include:
•	Ensuring proper contact performance by tracking contact resistance and erosion.
•	Monitoring insulation integrity to prevent dielectric breakdown.
•	Detecting mechanical wear in actuators, springs, and linkage components.
•	Analyzing switching behavior to identify abnormal current and voltage fluctuations [15][16].
2.3 Key Condition Monitoring Techniques for VCBs
Effective CM of VCBs relies on various techniques, including:
•	Trip Coil Current Analysis: Monitors deviations in trip coil current waveforms to detect operating failures in VCB actuators [17].
•	Vibration Monitoring: Uses wavelet packet analysis and artificial neural networks (ANNs) to detect faults in VCB actuators and mechanisms [18].
•	Dynamic Contact Resistance Measurement (DRM): Injects direct current (DC) to assess contact wear and degradation trends in VCBs [19].
•	Model-Aided Diagnosis: Uses computer simulations to predict faults by comparing real-time data with modeled failure conditions [20].
•	Contact Temperature and Resistance Analysis: Evaluates thermal stress and degradation of VCB contacts over time [21].
•	Contact Erosion Analysis: Uses acoustic emissions to assess arc-induced wear on contacts [22].
•	Dissolved Gas Analysis (DGA): Identifies insulation breakdown in oil-based CBs (less relevant to VCBs but useful for comparison) [23].
2.4 Implementing CM Across Cloud, Fog, and Edge Layers
With the rise of Industrial IoT (IIoT) and AI, CM can be implemented at various computational levels:
•	Edge Computing: Processes real-time sensor data locally to enable fast fault detection [24].
•	Fog Computing: Aggregates data from multiple VCBs, optimizing bandwidth usage while enabling localized AI inference.
•	Cloud Computing: Utilizes high-performance AI models for fleet-wide predictive maintenance and failure analysis [25].
2.5 Benchmarking Computational Trade-offs
A key research objective is to evaluate the feasibility of different computing architectures in VCB monitoring by benchmarking:
•	Latency (real-time vs. cloud processing delay).
•	Privacy (local processing vs. data centralization risks).
•	Bandwidth Consumption (continuous transmission vs. local aggregation).
•	AI Performance (on-device inference vs. centralized cloud AI) [26].
Suggested Figures
1.	VCB Lifetime vs. Vacuum Level: Shows how vacuum degradation correlates with failure risk [6].
2.	Contact Erosion vs. Lifetime Graph: A plot modeling expected VCB lifespan based on contact wear rates [7].
3.	Trip Coil Current and Vibration Analysis: Graphs illustrating how trip coil current deviations and vibration signatures indicate faults [17][18].
4.	HI Calculation Model for VCBs: Graphs displaying how HI changes with different degradation parameters (mechanical wear, electrical faults, etc.) [13].
5.	Computational Framework for VCB Monitoring: A diagram illustrating edge, fog, and cloud data flow [24].

******+++++++++

Asset Management and Condition Monitoring of Vacuum Circuit Breakers (VCBs)
1. Asset Management of Vacuum Circuit Breakers
Asset management for Vacuum Circuit Breakers (VCBs) is essential to ensure their long-term operational efficiency and reliability. VCBs are critical components in medium-voltage switchgear, and their failure can lead to severe power distribution issues. Effective asset management integrates lifecycle assessment, performance optimization, failure risk mitigation, and predictive maintenance frameworks.
1.1 Health Index-Based Asset Management Framework
A Health Index (HI)-based framework is widely used to assess the condition of VCBs by evaluating key degradation parameters such as vacuum integrity, contact erosion, mechanical wear, and electrical insulation performance. The HI model incorporates diagnostic data, historical operational records, and failure probabilities to optimize maintenance strategies.
Key parameters used in HI-based diagnostics include:
•	Vacuum loss: A decrease in dielectric strength increases partial discharge risks and arc instability.
•	Contact erosion: Progressive wear from switching operations degrades performance.
•	Mechanical wear: Grease degradation in actuator mechanisms reduces efficiency.
•	Electrical insulation failures: Surface contamination and condensation lead to leakage currents.
The HI framework enhances predictive maintenance by identifying potential failures before they occur. It utilizes condition-based and AI-driven predictive maintenance strategies to optimize VCB reliability and reduce operational costs.
1.2 Maintenance Strategies for VCBs
VCB maintenance strategies include:
•	Reactive Maintenance: Repairs are conducted after failure, leading to higher downtime.
•	Preventive Maintenance: Scheduled inspections and overhauls based on manufacturer guidelines.
•	Condition-Based Maintenance (CBM): Uses real-time sensor monitoring (coil current, vibration analysis, and partial discharge detection) to identify anomalies.
•	Predictive Maintenance: AI-based models analyze operational data trends to forecast failures, enabling proactive interventions.
The integration of HI-based scoring allows prioritization of maintenance tasks, preventing costly failures while extending VCB lifespan.
2. Condition Monitoring of Vacuum Circuit Breakers
Condition Monitoring (CM) is an essential tool for ensuring the health and reliability of VCBs. It enables early fault detection by tracking mechanical vibrations, electrical characteristics, and operational deviations.
2.1 Vibration Analysis for Condition Monitoring
Vibration analysis is one of the most effective non-invasive techniques for monitoring VCB health. This method identifies mechanical anomalies such as lubrication failures, misalignment, and component wear.
•	Wavelet Packet Analysis (WPA) has been applied to analyze vibration signals, extracting key frequency components associated with fault conditions.
•	Studies show that vibration patterns are highly reproducible in a faultless CB, allowing easy differentiation between normal and faulty conditions.
•	A continuous monitoring system records vibration patterns for every operation, comparing them with baseline references to identify deviations in timing and frequency.
2.2 Online Condition Monitoring for Failure Prediction
Online condition monitoring collects trip coil current, motor current, main contact movement, and vibration data in real time. This data is analyzed using machine learning models to detect subtle deviations that indicate emerging faults.
Findings from long-term studies of online monitoring include:
•	Temperature variations impact trip coil current and vibration signals, requiring temperature compensation in diagnostics.
•	Trip coil current analysis detects problems such as latch stiffness and auxiliary contact issues.
•	Vibration monitoring effectively identifies damping failures and misalignment.
2.3 Implementation of Condition Monitoring Across Computing Layers
To enhance predictive maintenance, condition monitoring is implemented across different computing layers:
•	Edge Computing: Real-time processing of sensor data enables instant fault detection.
•	Fog Computing: Aggregates data from multiple VCBs, optimizing bandwidth usage while enabling localized AI inference.
•	Cloud Computing: High-performance AI models analyze fleet-wide data for predictive maintenance scheduling.
*******************++++++++++++++++++++++++


Acoustic sensors that can detect and analyze the noise caused by switching vibrations 
[116, 117
Overview sensing technologies, based on [43]
in mechanical monitoring, especially when vibration signals are used as input, MLbased approaches also dominate, see [126–130] for recent examples It is worth noting that the research regarding ML is highly dynamic. Typically, each publication benchmarks its own approach against multiple others.
IEC, Electropedia: The World's Online Electrotechnical Vocabulary. [Online]. Available: https://
www.electropedia.org/ (accessed: Oct. 18 2023).
61850-90-3: Communication networks and systems for power utility automation –Part 90-
3: Using IEC 61850 for condition monitoring diagnosis and analysis, IEC, 2016.

Y. Alsumaidaee, C. Yaw, S. Koh, S. Tiong, C. Chen, and K. Ali, "Review of Medium-Voltage 
Switchgear Fault Detection in a Condition-Based Monitoring System by Using Deep Learning," 
Energies, vol. 15, no. 18, p. 6762, 2022, doi: 10.3390/en15186762

Development of switchgear condition monitoring using IoT technology for Condi-
tion Based Maintenance: 10645 A3 PS3

PROFITABILITY OF CONDITION MONITORING IN THE ELECTRIC DISTRIBUTION 
GRID: 10237
462: Obtaining Value from On-Line Substation Condition Monitoring
