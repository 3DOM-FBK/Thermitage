
# README — Chesterton Windmill (WIND)

This document describes the datasets available for Chesterton Windmill (WIND), including camera calibration parameters, geometric and radiometric control, and an index of the supporting documents contained in this folder.

## Site:

- **Site Name:** Chesterton Windmill, 
- **Project Code:** WIND
- **Location:**
  - Name: Chesteton Windmill
  - Address: Windmill Hill Lane, Leamington Spa, Warwickshire, CV33 9LB, UK 
  - Coordinates: 52.23126° N, 1.49118° W

- **Survey Date(s) & Time(s):** 
    - RGB: 25/08/25 08:00
    - TIR: 09/08/2025 08:30
    - VIS: 09/08/2025 08:30
    - SBs: 09/08/2025 10:00    
- **Site Conditions:**
  - Weather: Clear day, surveys undertaken during sunrise.
  - Visibility: No visibility issues. Clear, bright day

## Personnel:

| Name | Email | Role |
|---|---|---|
|Neil Sutherland|sutherland.neil@gmail.com|PhD Researcher|
Steve Sutherland | ---|Drone Spotter
|   |   |   |

## Datasets:

| Parameters: | TIR | VIS | RGB |
|---|---|---|---|
| Camera |DJI Mavic 3T | DJI Mavic 3T | Sony A7RII |
| No. Images (Int. / Ext)| 203 (43/160) | 203 (43/160) | 84 (50/34) |
| Avg. GSD (Int./Ext.) |5.3/10.6 | 1.5/3.0 | 0.5/1.3 |

**Zenodo link:** [Thermitage: Chesterton Windmill (WIND)](LINK TO ZENODO DATA COLLECTION)

**Description:** Concurrent TIR-VIS image pairs captured with the DJI Mavic 3T. These images are a fixed baseline, provided in the GeoCamCal folder. RGB images were captured both landscape and portrait the day after the DJI surveys..

## Sensors:

| Parameters: | TIR | VIS | RGB |  
|---|---|---|---|
| Camera | DJI Mavic 3T | DJI Mavic 3T | Sony ⍺7RII |
| Sensor | VOx FPA | CMOS | CMOS |
| Resolution (pix) | 640x512 | 4000x3000 | 7952x5304 |
| Sensor Size (mm) | 7.7x6.1 | 6.3x4.8 | 35.9x24.0 |
| Pixel Pitch (µm) | 12.0 | 1.6 | 4.5 |
| Focal Length (mm) | 9.1 | 4.4 | 35.0 |

## Associated Folders & Documents:

This includes descriptions of all documents provided in the associated folders as part of the WIND project:

| Folder: | Description: |
|---|---|
|**Camera Calibration**| Geometric and radiometric camera calibration information, including: camera intrinsics and relative orientation parameters, radiometric calibration, correction and validation tests.|
|**Documentation**| Project documentation including helpful resoucres, historic significance, building surveys etc.|
|**Geometric Control**| Geometric survey control for the project, including: defined geometric control (scale bars), 2D image coordinates of control points in each image modality, witness diagrams, equipment certificates and reports.|
|**Radiometric Control**| Radiometric control for the project, including: documented radiometric control, equipment specifications and survey conditions.|
| **docs/Sutherland et al. - Multi-Modal and Multi-Sensor Photogrammetric Data Fusion Exploiting a New Repository for Infrared Thermography Datasets.pdf** | Associated conference paper for Chesterton Windmill and the Thermitage repository. |

---

*See `docs/dictionary.md` for full definitions used across all site surveys.*

*For more detail on each dataset, other file formats or clarification, please contact Neil Sutherland throughout this GitHub Repository*