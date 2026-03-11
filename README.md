# FashionNet: A Large-Scale Fine-Grained Clothing Classification Dataset

This repository contains the official code and dataset information for the paper:

**Fine-Grained Clothing Classification with Adaptive Group Interaction and Attention-Guided Feature Fusion**

---

## Overview

Fine-grained clothing classification (FGCC) is a challenging task due to large intra-class variations and complex backgrounds. 

To facilitate research in this area, we construct **FashionNet**, a large-scale clothing image dataset designed for fine-grained classification tasks.

---

## Dataset Statistics

FashionNet contains:

- **892,841 images**
- **162 fine-grained categories**
- **8 attribute groups**

| Attribute Group | Subcategories | Images |
|---|---|---|
Accessories | 22 | 83,019 |
Clothes Length | 6 | 30,000 |
Collar | 22 | 95,117 |
Contour | 11 | 55,000 |
Fabric | 26 | 117,520 |
Gender | 2 | 10,000 |
Season | 2 | 10,000 |
Sleeve Type | 20 | 192,807 |

Additionally, the **category-level dataset** contains:

- **51 clothing categories**
- **299,378 images**

---

## Dataset Characteristics

Compared with existing FGCC datasets, FashionNet has several advantages:

1. **Large intra-class variation**

The dataset includes a wide variety of clothing styles reflecting modern fashion trends.

2. **Complex real-world backgrounds**

Images contain diverse backgrounds including indoor scenes, streets, and studios.

3. **High-quality annotations**

All images are manually curated to remove low-quality or irrelevant samples.

---

## Dataset Download

The full dataset (~100GB) is available at:

- HuggingFace:  
https://huggingface.co/datasets/yourname/FashionNet

- Mendeley Data (DOI):  
https://data.mendeley.com/...

---

## Code

The training code for the proposed FGVC model is provided in:
