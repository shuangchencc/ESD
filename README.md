# ESD: Embedded Seamless Data
## Democratizing planetary-scale analysis: An ultra-lightweight Earth embedding database for accurate and flexible global land monitoring
<img width="1193" height="607" alt="ESD_main" src="https://github.com/user-attachments/assets/dc14240a-e499-4803-a4a8-50c0695170bb" /> ***Figure 1. Schematic of the integrated ESD production pipeline.***

Embedded Seamless Data (ESD) is a global-scale, $30\text{ m}$ resolution Earth embedding dataset designed for efficient and accurate environmental monitoring2. By transforming high-dimensional satellite observations into information-dense latent vectors, ESD reduces storage requirements from petabytes to approximately 2.4 TB per global year, enabling decadal-scale analysis on standard local workstations.

<img width="1672" height="789" alt="ESDNet_overview" src="https://github.com/user-attachments/assets/d07b1116-d198-4599-b87f-67a55d1c367c" /> ***Figure 2. Detailed network architecture and computational process.***

## 🚀 Key Features
- **Massive Compression**: Encapsulates the entire global land surface for one year in ~2.4 TB (approx. 136.3 MB per tile);
- **High Resolution**: Provides a spatially consistent, 30m resolution record from 2000 to 2024;
- **Multi-Sensor Fusion**: Built upon the Global 30m Seamless Data Cube (SDC30), integrating Landsat 5/7/8/9 and MODIS Terra observations;
- **Temporal Fidelity**: Explicitly preserves intra-annual dynamics and phenological cycles, allowing for the reconstruction of near-daily observations with low error rates;
- **Terrain-Aware**: Incorporates static topographic covariates from NASADEM (elevation, slope, and aspect) to enhance biophysical characterization.
