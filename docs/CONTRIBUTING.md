# Contributing

Thermitage is designed to be a benchmarking repository for members of the IRT and digital cultural heritage (DCH) communities to access, analyse and share datasets for the advancement of IRT. Therefore, we hope contributors will engage with fellow members to build a FAIR repository that can be continually improved and developed with new features.

## Types of Contributions:

You can contribute by:
- Adding new datasets (following the folder structure and metadata templates)
- Improving documentation (README, metadata, guides)
- Contributing code (e.g., data processing scripts, visualization tools)
- Submitting bug reports or feature requests
- Helping with translations or outreach

## Data Structure:

All data deposited into Thermitage must be deposited with a logical data structure, currently found in **utils\SampleProject**. We are happy to work with depositors to help you determine the best structure for your data set.

### Project: 

A project folder should be created to contain all datasets, metadata and results related to a single project. If repeated visits to the same project / location have been undertaken, please include these within the same project and specify the necessity / purpose for repeated surveys within the project documentation

1. **Project Code:** A logical 2-5 character abbreviation of the project / location. (e.g., GATE for Lenton Lodge Gatehouse, ARCO for Arco Castle)
2. **Project Name:** A more detailed name for the project / location (e.g., Lenton Lodge Gatehouse or Arco Castle)
3. **Project Location:** Subregion and country tags in accordance to ISO 3166-2 specifications (e.g., NG_UK for Nottinghamshire, UK; TN_ITA for Trentino, Italy)
4. **Date:** Project date, or specified date for entire project in YYYY_MM_DD format (e.g., 2025_05_10 for the 10th May 2025)

E.g., GATE_LentonLodgeGatehouse_NG_UK_2025_05_10, ARCO_ArcoCastle_TN_ITA_2024_10_28, DUNR_DunrobinHouse_CV_UK_2023_10_25

### Dataset:

Datasets will be stroed on Zenodo, an open repository database for open research data. Please contact **Neil Sutherland** to discuss upload and coordination.

#### Sub Folders:

Each SampleProject folder comes with a series of associated folders, files and templates. These are to be strictly followed to provide the necessary data for effective IRT-3DDF research.