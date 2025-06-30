# LaserMark-DR-Dataset

This repository hosts the annotated dataset of laser marks in fundus photographs from the publication:

**Yukang Jiang, Jianying Pan, Ming Yuan, et al.**  
*Segmentation of Laser Marks of Diabetic Retinopathy in the Fundus Photographs Using Lightweight U-Net*  
Journal of Diabetes Research, 2021.  
[https://doi.org/10.1155/2021/8766517](https://doi.org/10.1155/2021/8766517)

---

## 1. Dataset Description

This dataset contains:
- **84 images** with high-quality, pixel-level annotations of laser marks
- Annotations verified by at least two experienced graders at Zhongshan Ophthalmic Center

### Data Format
- Images: RGB, JPG/JPEG format
- Annotations: PNG or binary mask format (1 = laser mark, 0 = background)
- Metadata: Optional CSV (image ID, acquisition source, stage, etc.)

---

## 2. Usage

This dataset is intended for:
- Semantic segmentation research
- AI-assisted diabetic retinopathy analysis
- Benchmarking models on laser mark detection

Please cite the original publication if you use this dataset in your work.

---

## 3. Citation

```bibtex
@article{jiang2021segmentation,
  title={Segmentation of Laser Marks of Diabetic Retinopathy in the Fundus Photographs Using Lightweight U-Net},
  author={Jiang, Yukang and Pan, Jianying and Yuan, Ming and et al.},
  journal={Journal of Diabetes Research},
  volume={2021},
  pages={8766517},
  year={2021},
  publisher={Hindawi}
}
