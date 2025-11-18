# ForestSplat Dataset

This repository contains the dataset accompanying the paper:

**ForestSplat: Proof-of-Concept for a Scalable and High-Fidelity Forestry Mapping Tool Using 3D Gaussian Splatting**

*Published in Remote Sensing (MDPI), Volume 17, Issue 6, Article 993*  
**DOI:** [10.3390/rs17060993](https://doi.org/10.3390/rs17060993)  
**Paper URL:** [https://www.mdpi.com/2072-4292/17/6/993](https://www.mdpi.com/2072-4292/17/6/993)

---

## Dataset Description

The ForestSplat dataset provides high-resolution forestry mapping data generated using 3D Gaussian Splatting techniques. This dataset enables researchers and practitioners to:

- Develop and validate forestry mapping algorithms
- Conduct comparative studies on remote sensing techniques
- Evaluate 3D Gaussian Splatting performance in forestry applications

### Dataset Contents

The dataset includes:

<!-- - **3D Gaussian Splatting Models**: Optimized point cloud representations in PLY format -->
- **Point Cloud Data**: High-resolution LiDAR-derived point clouds
- **RGB Imagery**: High-resolution images corresponding to the point cloud data
- **Camera Poses**: Structure-from-Motion (SFM) camera calibration and pose information
- **Metadata**: Comprehensive information about data collection, sensor specifications, and processing parameters

---

## Data Collection Methodology

Data was collected using advanced remote sensing technologies, including:

- **LiDAR Systems**: High-resolution point cloud acquisition
- **RGB Cameras**: High-resolution imaging sensors
- **Structure-from-Motion (SFM)**: Multi-view stereo reconstruction

The collection process involved:
1. **Site Selection**: Diverse forested regions selected to ensure comprehensive coverage
2. **Data Acquisition**: Simultaneous capture of LiDAR point clouds and high-resolution imagery
3. **SFM Processing**: Multi-view stereo reconstruction to generate camera poses
4. **Gaussian Splatting**: Optimization of 3D Gaussian parameters for high-fidelity rendering (will be added later)

For detailed methodology, please refer to the associated [publication](https://www.mdpi.com/2072-4292/17/6/993).

---

## Data Structure

The dataset is organized as follows:

```
ForestSplat_Dataset/
├── sfmdata/
│   ├── metadata
│   ├── raw_images
│   └── sparse
├── lidardata/
│   ├── DJI_202401111520_C1_Zenmuse-L1-mission
│   ├── DJI_202401111556_C2_Zenmuse-L1-mission
│   ├── ...
│   └── ReconstructedPointClouds
```

### Download URL

- **`sfmdata/`**: [Dropbox URL](https://www.dropbox.com/scl/fo/pdjc873671bltpyr1f9yl/AGDCtMfOkfnZpwQ2KCxD-yw?rlkey=slk1lngefeliz5q8mzje9a4n5&st=f7pxhuga&dl=0)
- **`lidardata/`**: [Dropbox URL](https://www.dropbox.com/scl/fo/br0ai4q9des35phya7mtn/AF5EG1iEHZv7rMY5gwKuw1c?rlkey=4siis9n06m7x0ls6m6temz8c7&st=nw8fc25m&dl=0)

---

## Citation

If you use this dataset in your research, please cite the following paper:

```bibtex
@article{ForestSplat2025,
  author = {[Author Names]},
  title = {ForestSplat: Proof-of-Concept for a Scalable and High-Fidelity Forestry Mapping Tool Using 3D Gaussian Splatting},
  journal = {Remote Sensing},
  volume = {17},
  number = {6},
  pages = {993},
  year = {2025},
  publisher = {MDPI},
  doi = {10.3390/rs17060993},
  url = {https://www.mdpi.com/2072-4292/17/6/993}
}
```

---

## Updates and Version History

- **v1.0** (2025-11-18): Initial dataset release

---

## TODO

- [ ] Upload PLY files for splatting model
- [ ] Upload visualization results and data to visualize them

---

## Contact

For questions, issues, or collaboration inquiries regarding this dataset, please contact:

- **Dataset Maintainer**: [Thuan] ([thuan@coolant.earth](mailto:thuan@coolant.earh))
- **Corresponding Author**: [Michael] ([email@example.com](mailto:michael@coolant.earth))

---
