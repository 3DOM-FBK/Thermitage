
# README — DUNR

This document describes the datasets available for Dunrobin House (DUNR), including a breakdown of the site, datasets, sensors and supporting documents contained in this folder.

## Site:

- **Site Name:** Dunrobin House
- **Project Code:** DUNR
- **Location:**
  - Name: Dunrobin House
  - Address: Loxley, Warwickshire, CV35 9HQ, United Kingdom
  - Coordinates: 52.18071° N, 1.63822° W

- **Survey Date(s) & Time(s):** 
    - RGB: 03/11/2023 15:00
    - TIR: 15/10/2023 23:00
    - M3T: --- (TBC)
    - TST: 23/11/2023
- **Site Conditions:**
  - Weather: Clear, dry for both TIR and RGB surveys. TIR undertaken at night to mimic conditions of energy audit and minimise solar radiation effects.
  - Visibility: No visibility issues for RGB. As TIR was captured at night, no accompanying VIS is available for this dataset as the survey was conducted at night.

## Personnel:

| Name | Email | Role |
|---|---|---|
|Neil Sutherland|sutherland.neil@gmail.com|Lead Surveyor|
|   |   |   |

## Datsets:

| Parameters: | TIR | RGB |
|---|---|---|
| Camera | Workswell WIRIS Pro |Sony A7RII |
| No. Images | 45 | 50 |
| Min. GSD (mm) | 9.8 | 5.8 | 1.0 |
| Max. GSD (mm)  | 9.8 | 14 | 1.3 |
| File Format | .tiff | .jpg

**Zenodo link:** [Thermitage: Dunrobin House (DUNR)](https://zenodo.org/records/21649356?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6Ijc3NGIxYWQwLTJmZjYtNGU5ZS1iN2FjLWIzZjc1Y2Q4NDA4YSIsImRhdGEiOnt9LCJyYW5kb20iOiI3ZmVhYWUxZWFmNjdjZWU3ODA2OGNiY2QyOGQ4MjA0ZSJ9.pUXR93fqFauFcUj717ef4TNQADaCslAAhdnunu8ZBcDBBF-jeTs5XyN0BVsbG1iRy8yrYES2YvTRY6u4m2YlDg)

**Description:** No accompnaying VIS with TIR due to night-time image capture. M3T dataset features both TIR and VIS in fixed RO. Please contact Neil Sutherland if this dataset is required. TIR features temperature value encoded within each pixel, convertible using Workswell's formula (included in Utils/RadCamCalCorrVal).

## Sensors:

| Parameter | WWP (TIR) | Sony α7R II (RGB) |
|---|---|---|
| Camera | Workswell WIRIS Pro | Sony |
| Sensor | VOx FPA | CMOS |
| Resolution (pix) | 640x512 | 7952x5304 |
| Sensor Size (mm) | 10.88x8.71 | 35.90x24.00 |
| Pixel Pitch (µm) | 17.00 | 4.50 |
| Focal Length (mm) | 13.00 | 35.00 |
 
### DJI Mavic 3T (M3T)
 
| Parameter | M3T (TIR) | M3T (VIS) |
|---|---|---|
| Camera | DJI Mavic 3T | DJI Mavic 3T |
| Sensor | VOx FPA | CMOS |
| Resolution (pix) | 640x512 | 4000x3000 |
| Sensor Size (mm) | 7.7x6.1 | 6.3x4.8 |
| Pixel Pitch (µm) | 12.0 | 1.6 |
| Focal Length (mm) | 9.1 | 4.4 |


## Associated Folders & Documents:

This includes descriptions of ANY and ALL documents provided in this associated folders as part of the DUNR project:

| Folder: | Description: |
|---|---|
|**Camera Calibration**| Geometric and radiometric camera calibration information, including: camera intrinsics, relative orientation parameters and radiometric calibration, correction and validation tests.|
|**Documentation**| Project documentation including helpful resoucres, historic significance, building surveys etc.|
|**Geometric Control**| Geometric survey control for the project, including: defined geometric control, 2D image coordinates of control points, witness diagrams, equipment certificates and reports|
|**Radiometric Control**| Radiometric control for the project, including: documented radiometric control, equipment specifications and survey conditions.|

---

*See `docs/dictionary.md` for full definitions used across all site surveys.*