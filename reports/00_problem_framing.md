# Explainable Digital Twin for Predictive Maintenance  

## Problem Statement: 

Industrial engines generate large volumes of sensor data, but maintenance teams often struggle to detect early degradation before it becomes costly downtime or failure. This project addresses that gap by building an explainable predictive-maintenance system that predicts Remaining Useful Life and translates model outputs into clear risk levels and maintenance actions.  

## What is RUL? 

Remaining Useful Life (RUL) is the estimated time for an asset, component, or machine to continue to perform its functions before it requires repair or replacement. RUL is a fundamental metric in predictive maintenance and asset management.  

## Types of Maintenance  

- Preventive maintenance and corrective maintenance. Preventive maintenance is time based, failure based, risk based, condition based, and predictive while corrective maintenance includes deferred and emergency. Time-based maintenance is done at a regular interval while equipment is still functioning. Failure Finding Maintenance	detects hidden failures typically associated with protective functions. Think pressure safety valves, trips transmitters etc. This type of equipment won’t be required to function until something else has failed. Condition Based maintenance looks for physical evidence to detect possibility of failure. Predictive maintenance is the extension of condition-based maintenance. Where expected life of a machine or component is predicted using machine learning or Artificial Intelligence.  

- Corrective maintenance or a run-to-failure strategy is letting the machine run for as long as possible and repair or replace it after it fails. This works in an environment where downtime is affordable, and delays can be expected. There are two types of CM; deferred and emergency. Deferred involves intentionally postponing non-critical repairs to a more suitable time, often due to budget limits or a lack of staff. In contrast, emergency maintenance is unscheduled, reactive work required instantly upon a critical asset failure to restore operations and avoid safety hazards. 

## Why RUL? 

Predicting Remaining Useful Life (RUL) saves companies millions by preventing catastrophic failures, maximizing equipment uptime, and cutting maintenance costs. Unlike running-to-failure or fixed schedules, RUL drives a transition to true predictive maintenance. RUL eliminates the risk of catastrophic failures by providing the exact warning needed to intervene safely.  

Replacing parts on a set schedule often results in changing perfectly good components. RUL ensures parts are only replaced when they are truly worn out, maximizing component lifespan. Knowing the exact timeline of a machine’s health allows companies to schedule repairs during planned downtimes or off-shift hours. This completely eliminates expensive production delays. Predicting exact failure timelines prevents the need to stockpile replacement parts "just in case," freeing up valuable working capital and storage space.  

## Cost Tradeoff  

The cost trade-off is between unnecessary maintenance and unexpected failure. A false alarm means the model predicts failure too early, so the company may inspect or replace a part before it is truly needed. This costs money through extra labor, spare parts, planned downtime and possible wasted asset life. 

A missed failure is usually much more expensive because the model fails to warn before breakdown. This can cause unplanned downtime, production loss, emergency repairs, safety risks, service disruption, and reputational damage. So, companies usually prefer a model that gives some false alarms rather than one that misses serious failures, especially in safety-critical industries like aerospace, energy, rail or manufacturing. Companies can't blindly trust AI predictions without knowing why and where the prediction is coming from.  

 