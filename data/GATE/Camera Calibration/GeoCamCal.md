# Geometric Camera Calibration - GATE

This document describes the geometric camera calibration carried out for all sensors in The Lenton Lodge Gatehouse (GATE) project, including interior- and relative orientation parameters, methodology, equipment and an index of the supporting documents contained in this folder.

## Method:

Geometric camera calibration method(s) used:

- **3D Calibration Field**

**Description:** 3D calibration field using thermal-specific survey markers used. IO for RGB, TIR and VIS determined using this field, as well as RO for WWP's dual sensors. Please refere to associated documents for reference paper.

## Associated Documents:

| File: | Type: | Description: |
|---|---|---|
|**GeoCamCal.md** | Summary | Descriptive summary of folder contents and useful information |
|**GATE-GeoCamCal-SENSOR.xml**| Camera Intrinsics | Interior orientation parameters for each sensor, in Agisoft-ready .xml format. |
|**GATE-GeoCamCal-RO.json**| RO Parameters | Relative orientation parameters for the WWP, determined using Australis and the IO parameters included above. |
|**docs/Sutherland et al. - Geometric Calibration of Thermal Infrared Cameras- A Comparative Analysis for Photogrammetric Data Fusion.pdf**| Journal Article | Associated paper with methodology, derived camera calibration parameters and applications. |
---

*See `docs/dictionary.md` for full definitions used across all site surveys.*