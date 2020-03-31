# SKIN LESION CLASSIFICATION

Final project for [Machine Learning](https://sites.google.com/site/roma3ml/) course held at the "Roma Tre" University of Rome.

## Authors

- Alessio Ligios - [alessioligios@gmail.com](mailto:alessioligios@gmail.com)
- Gianluca Visentin - [gia.visentin@stud.uniroma3.it](mailto:gia.visentin@stud.uniroma3.it)

## Goal of The Project
Skin cancer has affected the lives of many people and it is my hope that we can utilize modern machine learning techniques to facilitate early diagnosis and affordably inform individuals who may be at risk. This tool is not always accurate and is not intended to be a replacement for professional care.

## Dataset
The HAM10000 (“Human Against Machine with 10000 training images”) dataset which contains 10,015 dermatoscopic images was made publicly available by the Harvard database on June 2018. A metadata file with demographic information of each lesion is additionally provided.

The original dataset is available for download at the following url: [https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000).

## Label Descriptions
The dataset contains 7 cell types. Of the three malignant types, melanoma is most dangerous, basal cell carcinoma rarely spreads throughout the body but should be removed promptly and actinic keratoses is slow growing and can often be treated without surgery.

Below are the cell type descriptions from the original paper: [The HAM10000 Dataset: A Large Collection of Multi-Source Dermatoscopic Images of Common Pigmented Skin Lesions](https://arxiv.org/abs/1803.10417).

### Melanocytic Nevi (nv)
Melanocytic nevi are benign neoplasms of melanocytes and appear in a myriad of variants, which all are included in our series. The variants may differ significantly from a dermatoscopic point of view. [6705 images]

### Melanoma (mel)
Melanoma is a malignant neoplasm derived from melanocytes that may appear in different variants. If excised in an early stage it can be cured by simple surgical excision. Melanomas can be invasive or non-invasive (in situ). We included all variants of melanoma including melanoma in situ, but did exclude non-pigmented, subungual, ocular or mucosal melanoma. [1113 images]

### Benign Keratoses (bkl)
"Benign keratosis" is a generic class that includes seborrheic ker- atoses ("senile wart"), solar lentigo - which can be regarded a flat variant of seborrheic keratosis - and lichen-planus like keratoses (LPLK), which corresponds to a seborrheic keratosis or a solar lentigo with inflammation and regression. The three subgroups may look different dermatoscopically, but we grouped them together because they are similar biologically and often reported under the same generic term histopathologically. From a dermatoscopic view, lichen planus-like keratoses are especially challenging because they can show morphologic features mimicking melanoma and are often biopsied or excised for diagnostic reasons. [1099 images]

### Basal Cell Carcinoma (bcc)
Basal cell carcinoma is a common variant of epithelial skin cancer that rarely metastasizes but grows destructively if untreated. It appears in different morphologic variants (flat, nodular, pigmented, cystic, etc), which are all included in this set. [514 images]

### Actinic Keratoses (akiec)
Actinic Keratoses (Solar Keratoses) and intraepithelial Carcinoma (Bowen’s disease) are common non-invasive, variants of squamous cell carcinoma that can be treated locally without surgery. Some authors regard them as precursors of squamous cell carcinomas and not as actual carcinomas. There is, however, agreement that these lesions may progress to invasive squamous cell carcinoma - which is usually not pigmented. Both neoplasms commonly show surface scaling and commonly are devoid of pigment. Actinic keratoses are more common on the face and Bowen’s disease is more common on other body sites. Because both types are induced by UV-light the surrounding skin is usually typified by severe sun damaged except in cases of Bowen’s disease that are caused by human papilloma virus infection and not by UV. Pigmented variants exists for Bowen’s disease and for actinic keratoses. Both are included in this set. [327 images]

### Vascular Lesion (vasc)
Vascular skin lesions in the dataset range from cherry angiomas to angiokeratomas and pyogenic granulomas. Hemorrhage is also included in this category. [142 images]

### Dermatofibroma (df)
Dermatofibroma is a benign skin lesion regarded as either a benign proliferation or an inflammatory reaction to minimal trauma. It is brown often showing a central zone of fibrosis dermatoscopically. [115 images]
