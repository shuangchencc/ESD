# 🌐 Embedded Seamless Data (ESD, 2000-2024)
## Democratizing planetary-scale analysis: An ultra-lightweight Earth embedding database for accurate and flexible global land monitoring

<img width="1193" height="607" alt="ESD_main" src="https://github.com/user-attachments/assets/dc14240a-e499-4803-a4a8-50c0695170bb" /> 

The Embedded Seamless Data (ESD) is a first-of-its-kind, global-scale 30-m Earth embedding database designed to overcome the computational and storage barriers of planetary-scale Earth System Science. By transforming high-dimensional, multi-sensor satellite observations into information-dense, quantized latent vectors, ESD achieves a transformative ~340-fold reduction in data volume. This allows researchers to store and process a full year of global land surface data—originally nearly 1 PB—within approximately 2.4 TB, enabling decadal-scale analysis on standard local workstations.

# 🚀 Key Features
-	**Longitudinal Consistency:** A continuous 25-year record (2000–2024) harmonized from Landsat series (5, 7, 8, and 9) and MODIS Terra observations.
-	**High Reconstructive Fidelity:** Achieves a Mean Absolute Error (MAE) of 0.0130 across six spectral bands, ensuring embeddings serve as a physically meaningful proxy for raw reflectance.
-	**Semantic Intelligence:** Outperforms raw sensor fusion data in land-cover classification, achieving a global overall accuracy of 79.74% (without other auxiliary data).
-	**Implicit Denoising:** The ESDNet architecture effectively filters transient noise, mitigating residual cloud artifacts and shadows to provide a cleaner signal for surface processes.
-	**Few-Shot Proficiency:** Demonstrates robust learning capabilities with limited labeled data, making it ideal for monitoring regions where ground-truth samples are scarce.

# 🛠 How to Use ESD
- **Fixed Feature Extraction:** Use embeddings directly for training downstream models such as Random Forests, CNNs, or Transformers.
- **Change Detection:** Track decadal shifts in forest cover, urban expansion, and water dynamics with longitudinal stability across different Landsat generations.
- **Multi-Modal Integration:** Effortlessly coregister ESD tiles with SAR, thermal, or climate variables for comprehensive environmental characterization.

# 🤖 Demo scripts and sample data
You can download the demo scripts and sample data from Google Drive (https://drive.google.com/file/d/13C4B9RCbA07pEwH9d5nC7baaKq4qkQNz/view?usp=drive_link).

# 📂 Data Access
The ESD product is organized by year and adheres to the UTM-based Military Grid Reference System (MGRS) tiling convention (3600 × 3600 pixels per tile).
- **Data Portal:** iEarth platform - https://data-starcloud.pcl.ac.cn/iearthdata/64
- **DOI:** [10.12436/iEarth.0000.20251229.000064.v1](https://doi.org/10.12436/iEarth.0000.20251229.000064.v1)
- **Credentials:** shuangchen / SDC@2024test

* P.S. 如果下载不够快或需要数据量大，可以联系我提供硬盘寄送

# 📝 Citation
If you use this dataset or code in your research, please cite:
```latex
@article{chen2026esd,
  title={Democratizing planetary-scale analysis: An ultra-lightweight Earth embedding database for accurate and flexible global land monitoring},
  author={Chen, Shuang and Wang, Jie and Yuan, Shuai and Li, Jiayang and Xia, Yu and Liao, Yuanhong and Wei, Junbo and Yuan, Jincheng and Xu, Xiaoqing and Zhu, Xiaolin and others},
  journal={arXiv preprint arXiv:2601.11183},
  year={2026},
  url={https://arxiv.org/abs/2601.11183}
}
```
