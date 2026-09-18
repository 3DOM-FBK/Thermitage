
# README — Castello di Arco (ARCO)

This document describes the datasets available for Castello di Arco (ARCO), including camera calibration parameters, surveys and an index of the supporting documents contained in this folder.

## Site:

- **Site Name:** Castello di Arco
- **Project Code:** ARCO
- **Location:**
  - Name: Castello di Arco, 
  - Address: Piazza III Novembre 3, 38062 Arco TN, Italy
  - Coordinates: 45.92162° N, 10.88866° E

- **Survey Date(s) & Time(s):** 
    - TIR: 30/10/2024
    - VIS: 30/10/2024
    - RGB: 30/10/2024
    - SLAM: 30/10/2024
- **Site Conditions:**
  - Weather: Dry, no rain in previous 24hrs (no rain for two weeks, critical for assessment of water ingress in frescoes)
  - Visibility: Clear, bright day. Surveys undertaken indoors with illumination from room lights and singular window

## Personnel:

| Name | Email | Role |
|---|---|---|
|Neil Sutherland|sutherland.neil@gmail.com|PhD Researcher|
|Fabio Remondino |---| Supervisor |
| Pawel Tybala  | --- | SLAM Surveyor |

## Datasets:

| Parameters: | TIR | VIS | RGB2 | SLAM |
|---|---|---|---|---|
| Camera | Workswell WIRIS Pro | Workswell WIRIS Pro | Nikon D750FX| ---|
| No. Images | 40 | 40 | 40 | --- |
| Avg. GSD (mm)| 3.3 | 2.0 | 0.3 | --- |
| File Format + Extension | -radiometric.tiff|-visible.jpg |-digital.jpg | |

**Zenodo link:** [Thermitage: Castello di Arco (ARCO)](https://zenodo.org/records/21672415?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6ImQzZmVmZjMyLWE5MzMtNDEwZi1iNmE5LTBjNjgzM2QxMGJmYSIsImRhdGEiOnt9LCJyYW5kb20iOiJkOThjZGVkNGVjM2YzZjRlMjI0M2I1MGE3MjllNjBkYSJ9.KuIQX4CrJbQoJjrxNuh-_nhZ5EIgqFjcFfAAK68mAVw5EY8rexTBQpvRVMAxMkjqC2cmmx5tszBWkOVo_RpjDQ)

**Description:** TIR-VIS-RGB2 datasets captured concurrently, with all file formats coordinated and named accordibly. Stereo rig configured with WWP (TIR & VIS) and NIKON RGB2 camera fixed in relative orientation. Additional SLAM dataset, using custom SLAM device, used to capture the space (please enquire for additional information).

## Sensors:

| Parameters: | TIR | VIS | RGB | SLAM |
|---|---|---|---|---|
| Camera | Workswell WIRIS Pro | Workswell WIRIS Pro | Nikon D750FX | ---|
| Sensor | VOx FPA| CMOS |CMOS | --- |
| Resolution (pix) |640x512 |1920x1080 |6016x4016 | --- |
| Sensor Size (mm) |10.88x8.71 | 5.23x2.94 |35.90x24.00 | --- |
| Pixel Pitch (µm) | 17.00 |2.72 |5.95 | --- |
| Focal Length (mm) | 13.00 | 3.50 |50.00 | --- |


## Associated Folders & Documents:

This section includes descriptions of all documents provided in the associated folders as part of the ARCO project:

| Folder: | Description: |
|---|---|
|**Camera Calibration**| Geometric and radiometric camera calibration information, including: camera intrinsics, relative orientation parameters and radiometric calibration, correction and validation tests.|
|**Documentation**| Project documentation including helpful resoucres, historic significance, building surveys etc.|
|**Geometric Control**| Geometric survey control for the project, including: defined geometric control, 2D image coordinates of control points, witness diagrams, equipment certificates and reports|
|**Radiometric Control**| Radiometric control for the project, including: documented radiometric control, equipment specifications and survey conditions.|
|**docs/Sutherland et al. - Geometric Calibration of Thermal Infrared Cameras- A Comparative Analysis for Photogrammetric Data Fusion.pdf**| Associated paper with methodology, derived camera calibration parameters and applications. |

---

*See `docs/dictionary.md` for full definitions used across all site surveys.*

*For more detail on each dataset, other file formats or clarification, please contact Neil Sutherland throughout this GitHub Repository*