# Radiometric Control - GATE

This document describes the radiometric control for all TIR datasets included in the Lenton Lodge Gatehouse project, including radiometric control, survey conditions, equipment specifications and associated calibration documents contained in this folder.

## Terminology:

The terms below present the distinctions between different
component temperatures within this repository, demonstrating the transformation of real-world temperature values into 2D/3D digital temperature values. To distinguish between these different temperature values within thermal modelling methods, the following terms are adopted for all subsequent IRT-3DDF workflows:
- **T<sub>real</sub>:** The true (theoretical) temperature of a specimen.
- **T<sub>obs</sub>:** The observed temperature of the specimen, achieved using a blackbody, infrared thermometer or similar measuring device. This value is still dependent on the observation, with parameters affecting the accuracy of the reading against T<sub>real</sub>.
- **T<sub>2D</sub>:** The recorded temperature within the 2D thermal image. This is used to represent either an individual pixel value or the image in its entirety.
- **T<sub>3D</sub>:** The temperature encapsulated within the generated 3D thermal model. Similarly, this term is used to specify individual point or mesh values as well as the model in its entirety.

## Method:

Radiometric Control method(s) used:

- **Proximal InfraRed Thermometer**

**Description:** Measurements taken against thermal-specific survey markers using InfraRed Thermometer.

## Equipment:

The following equipment was used to record the site conditions and gain radiometric check points for temperature validation:

| Equipment: | Type: | Purpose:| Accuracy: | Sensitivity: |
|---|---|---|---|---|
|**RS PRO RS-8876**|InfraRed Thermometer|Radiometric Control, Reflected Temperature|±1% of reading (20°C to 300°C range)|0.1°C |
|**RS PRO RS-91**|Hygrometer|Relative Humidity, Air Temperature|±0.5°C / ±3%RH |0.1°C / 0.1%RH |
|**Protmex PT6252A**|Anemometer|Wind Speed, Wind Direction|±2.0% of reading + 0.5 digits | 0.01 m/s|

**Additional Equipment:**

- **Testo Emission Tape:** Adhesive tape with fixed emissivity (ε = 0.95)
- **SunCalc:** an online sunlight-phase tracker (https://www.suncalc.org)

**Description:** TESTO emission tape was used to determine the emissivity of the Mansfield Sandstone (ε = 0.70, σ = 0.03), whilst SunCalc was used to determine the timing of solar radiation hitting the building facade. 

## Emissivity Values:

Listed emissivity values for predominant materials in the scene:

| Material: | ε: | σ: | ∆ε: |
|---|---|---|---|
|**TESTO Emission Tape**|0.95|–|0.25|
|**Mansfield Sandstone**|0.70|0.03|–|
|**Wood**|0.90|0.14|0.20|
|**Cast-Iron**|0.83|0.08|0.15|
|**Survey Marker (Rubber)**|0.91|0.03|0.21|
|**Survey Marker (Aluminium)**|0.37|0.04|0.53|

**Description:** The following values were gained using the ASTM E1933-14 emissivity method.

## Associated Documents:

Include descriptions of ANY and ALL documents provided in this Geometric Camera Calibration folder as part of the geometric control for the project:

| File: | Type: | Description: |
|---|---|---|
|**RadiometricControl.md** | Summary | Descriptive summary of folder contents and useful information |
|**GATE-RadiomControl.csv**| Radiometric Control |Radiometric control network for the GATE TIR dataset|
|**GATE-RadiomWitnessDiagram.pdf**| Radiometric Control Witness Diagram | Documentation of site conditions and photos showing radiometric check points |

---

*See `docs/dictionary.md` for full definitions used across all site surveys.*