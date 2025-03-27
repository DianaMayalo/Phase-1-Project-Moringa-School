# Aviation Accident Analysis

![Aviation](C:\Users\ADMIN\Documents\MoringaSchool\Phase1\Phase1Project\Images\Aircraft.jpg)


**Author:** [Diana Mayalo](https://github.com/DianaMayalo)
# Overview
This project analyzes aviation accident data to identify risk factors affecting severity, aircraft damage, and injuries. The insights derived from this analysis help aviation authorities and manufacturers improve safety protocols, training, and maintenance practices.
# Business Understanding
Aviation accidents pose significant risks to passengers, crew, and aircraft manufacturers. By analyzing historical accident data, we aim to answer key business questions:
## Key Business Questions
1.	How do weather conditions influence the severity of injuries?
2.	Which aircraft manufacturers have a high proportion of serious but non-fatal accidents?
3.	What impact do different flight phases have on aircraft damage?
## Stakeholders
- Aviation regulatory authorities
- Aircraft manufacturers
- Airline operators
- Safety investigators
# Data Understanding and Analysis
## Source of data
From: [The NTSB aviation accident dataset up to Feb 2021](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)
The dataset consists of historical aviation accident records sourced from aviation safety databases and official reports. The aviation dataset contains accident records with details on injury severity, aircraft type, weather conditions, flight phase etc.
## Description of data
The dataset includes key attributes such as:
- `Event Date`: Date of the accident.
- `Aircraft Manufacturer`: Company that produced the aircraft.
- `Injury Severity`: Classification of accident severity (e.g., minor, serious, fatal).
- `Flight Phase`: Phase of flight during which the accident occurred.
- `Weather Conditions`: Atmospheric conditions at the time of the accident.
- `Aircraft Damage`: Extent of damage sustained by the aircraft.

# Visualizations

# Conclusion
1. Weather plays a major role in the severity of aviation accidents.
    - Fatal injuries are worse in visual meteorological conditions (VMC) and instrument meteorological conditions (IMC)
    - Last-minute maneuvers and poor visibility lead to high-speed crashes, causing more fatal injuries

    **Recommendation**: Improve pilot training for decision-making in poor weather conditions.

2. Some aircraft types may have higher accident rates due to operational or maintenance factors.
    - This suggests maintenance issues that require attention to reduce injuries.

    **Recommendation**: Conduct targeted safety inspections and maintenance improvements for Cessna and Piper aircraft.

3.  Different flight phases pose unique risks that impact aircraft damage severity.
    - Maneuvering and Cruise phases have the most destroyed aircraft due to mid-air crashes and loss of control.
    - Landing and Takeoff cause more substantial damage from gear failures or runway overruns.

 **Recommendation**: Enhance safety measures during Maneuvering and Cruise phases to prevent complete aircraft destruction.
# Next Steps
Further analyses could yield additional insights to further improve operations:
- Investigate why Cessna and Piper have higher non-fatal accident rates
- Explore pilot decision-making and training in VMC and IMC conditions
- Assess potential safety improvements in Maneuvering and Cruise phases
  
# For More Information

