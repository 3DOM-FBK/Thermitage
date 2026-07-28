# Geometric Camera Calibration - GATE

This document describes the geometric camera calibration carried out for all sensors in Chesterton Windmill (WIND) dataset, including interior- and relative orientation parameters, calibration methodology, equipment and an index of the supporting documents contained in this folder.

## Method:

Geometric camera calibration method(s) used (delete as necessary):

- **3D Calibration Field**

**Description:** RGB calibration undertaken using 3D calibration field and a self-calibrating bundle adjustment. For M3T, thermal-specific survey markers were measured with TST and included as known coordinates for a standard 3D calibration. IO and RO values obtained for the DJI M3T and included.

## Associated Documents:

This sections lists descriptions of ANY and ALL documents provided in this Geometric Camera Calibration folder as part of the geometric control for the project:

| File: | Type: | Description: |
|---|---|---|
|**GeoCamCal.md** | Summary | Descriptive summary of folder contents and useful information |
|**WIND-GeoCamCal-SENSOR.xml**| Camera Intrinsics | Interior orientation parameters for each sensor, in Agisoft-ready .xml format. |
|**WIND-GeoCamCal-M3T.xml**| Relative Orientation | Relative orientation parameters for the DJI M3T, mapping the TIR sensor onto the VIS sensor. Translation and rotation values (and accompnaying errors) included in .json format. |
|**docs/Sutherland et al. - Geometric Calibration of Thermal Infrared Cameras- A Comparative Analysis for Photogrammetric Data Fusion.pdf**| Journal Article | Associated paper with methodology, derived camera calibration parameters and applications. |

---

*See `docs/dictionary.md` for full definitions used across all site surveys.*