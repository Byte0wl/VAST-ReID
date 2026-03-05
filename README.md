# Dataset Access Instructions

Thank you for your interest in this dataset.  
Because this dataset contains visual material, access is provided **upon request**.

---

## 📌 1. How to Request Access

To obtain the dataset:

1. Download the **Dataset Access Request Form** from this repository (`dataset_access_form.pdf`).
2. Fill in all required fields
3. Ask your **supervisor/PI** to review and sign (if applicable).
4. Send the completed and signed form to:

    **Email:** dpdogra@iitbbs.ac.in, a24cs08005@iitbbs.ac.in, 24ai06011@iitbbs.ac.in  
    **Subject:** Dataset Access Request – VAST-ReID


You will receive a download link once your request is approved.

---

## 📦 2. Dataset Description

- **Name:** VAST-ReID
- **Size:** ~19 GB  
- **Type:** Person Re-Identification (Low-light / Night-time) 
---

## 📁 3. Folder Structure

```text
VAST-ReID/
│
├── VAST-ReID/
│   ├── C1/
│   │   ├── P_001/
│   │   │   ├── P_001_V_01.csv
│   │   │   ├── P_001_V_01.json
│   │   │   ├── P_001_V_01.mp4
│   │   │   ├── P_001_V_01_attributes.csv
│   │   │   ├── ...
│   │   ├── P_002/
│   │   ├── ...
│   ├── C2/
│   ├── ...
│   ├── C12/
│
├── BoxTrack-ReID/
│   ├── bounding_box_train/
│   ├── bounding_box_test/
│   ├── query/
```



---

## 📜 4. License

This dataset is released under the  
**Creative Commons Attribution–NonCommercial 4.0 (CC BY-NC 4.0)** license.
---

## 🧾 5. Citation (BibTeX)

If you use this dataset in your research, please cite:

```bibtex
@InProceedings{Khan_2026_WACV,
    author    = {Khan, Hammad and Giri, Rakesh Kumar and Thakare, Kamalakar Vijay and Choi, Heeseung and Jung, Hyungjoo and Dogra, Debi Prosad and Kim, Ig-Jae},
    title     = {VAST-ReID: A Low-Light Benchmark Dataset for Person Re-Identification with Visual and Attribute-Rich Semantic Tracking},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
    month     = {March},
    year      = {2026},
    pages     = {5833-5841}
}

