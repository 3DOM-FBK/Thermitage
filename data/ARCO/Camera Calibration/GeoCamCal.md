# Geometric Camera Calibration - ARCO

This document describes the geometric camera calibration carried out for all sensors at Arco Castle (ARCO), including interior- and relative orientation parameters for both VIS-TIR and RGB2-TIR baselines, methodologies, equipment and an index of the supporting documents contained in this folder.

## Method:

Geometric camera calibration method(s) used (delete as necessary):

- **3D Calibration Field**

**Description:** 3D test field using thermal-specific survey markers configured to calibrate all sensors simultaneously. All results were processed in Australis.

## Associated Documents:

Include descriptions of ANY and ALL documents provided in this Geometric Camera Calibration folder as part of the geometric control for the project:

| File: | Type: | Description: |
|---|---|---|
|**GeoCamCal.md** | Summary | Descriptive summary of folder contents and useful information |
|**ARCO-GeoCamCal-SENSOR.xml**| Camera Intrinsics | Interior orientation parameters for each sensor, in Agisoft-ready .xml format. |
|**ARCO-GeoCamCal-BASELINE.json**| Relative Orientation | Relative orientation parameters for each baseline, here the baseline between the WWP's integrated VIS and TIR senors, and the configured baseline between the Nikon RGB2 and WWP_TIR sensor. |
|**docs/Sutherland et al. - Geometric Calibration of Thermal Infrared Cameras- A Comparative Analysis for Photogrammetric Data Fusion.pdf**| Journal Article | Associated paper with methodology, derived camera calibration parameters and applications. |

---

*See `docs/dictionary.md` for full definitions used across all site surveys.*