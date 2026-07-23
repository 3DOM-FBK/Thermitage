
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
    - Geometric Control: 23/11/2023
- **Site Conditions:**
  - Weather: Clear, dry for both TIR and RGB surveys. TIR undertaken at night to mimic conditions of energy audit and minimise solar radiation effects.
  - Visibility: No visibility issues for RGB. As TIR was captured at night, no accompanying VIS is available for this dataset as the survey was conducted at night.

## Personnel:

| Name | Email | Role |
|---|---|---|
|Neil Sutherland|sutherland.neil@gmail.com|Lead Surveyor|
|   |   |   |

## Datsets:

- **TIR**
- **RGB**
- **M3T** (TBC)

**Description:** No accompnaying VIS with TIR due to night-time image capture. M3T features both TIR and VIS in fixed RO. File formats (RadTIFF vs. RadJPG)

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
|**Datasets**| Folders seperating each dataset by its modality. Each dataset comes with a .md to explain the dataset and it's contents / context.|
|**Documentation**| Project documentation including helpful resoucres, historic significance, building surveys etc.|
|**Geometric Control**| Geometric survey control for the project, including: defined geometric control, 2D image coordinates of control points, witness diagrams, equipment certificates and reports|
|**Radiometric Control**| Radiometric control for the project, including: documented radiometric control, equipment specifications and survey conditions.|

---

*See `docs/dictionary.md` for full definitions used across all site surveys.*