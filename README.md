# Diabetic Foot Ulcer (DFU) Risk Screening Prototype

Early-detection mobile tool for diabetic patients and clinicians.  
Combines three evidence-based modalities into a single risk score (0–100):

- Doppler waveform classification from phone microphone (triphasic → normal, monophasic → urgent)  
- Thermal asymmetry detection from foot photos (OpenCV)  
- Pressure hotspot simulation (Orpyx-style insole proxy)

**Status**: Working prototype – successfully classifies waveforms and thermal images.  
Idea during clinical work in DFU at Aseer Central Hospital (2020).  
Intended for pilot integration with teleradiology workflow.

→ Try it live on Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Boogieman237/diabetic-foot-risk-screening-prototype/main)

Technologies: Python • OpenCV • Librosa • Jupyter • Medical signal & image processing
