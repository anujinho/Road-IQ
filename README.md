# 🚦 Road-IQ: Data-Driven Road Accident Risk Prediction

> A hybrid ML + CNN + satellite imagery pipeline to predict road accident risk across urban road networks.

![Road-IQ Ensemble Architecture](assets/road_iq_ensemble.png)
<!-- Replace the path above with your actual image path, e.g. docs/img/ensemble_arch.png -->

---

## 📌 Overview

**Road-IQ** is a research project that models **road accident risk** using:

- Historical accident records (Great Britain)
- Road / junction / speed-limit metadata
- AADF traffic counts (per vehicle type)
- Population density from census data
- **Satellite imagery** of road segments

The system predicts whether a location is **Safe / Slight / Severe** and outputs a **continuous risk score** that can be used for:

- Real-time user alerts
- Urban road-safety planning
- Future multi-agent traffic control systems

The full technical details are in the report:  
`Road_IQ.pdf`
