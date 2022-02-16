# :mortar_board: Explainable-Custom-CNN-Architecture-for-Land-Use-Classification-Using-Satellite-Images
## :scroll: Abstract
Satellite images can be very challenging to work with which impedes their usage for numerous purposes. They are crucial for tracking the ever-changing human footprint around the world, including fast-growing cities, urban spread, and informal settlements. In this project, we propose a custom CNN model that classifies the EuroSAT Dataset (captured by Sentinel-2 satellite) consisting of 10 classes having 27,000 geo-referenced labeled images. Our custom model achieves average accuracy of 88.21%. Furthermore, we leverage a well known explainability approach (LIME) to help us understand the reasons for model predictions. We categorize the ten classes into four land type categories, namely, agricultural, build-up, under-developed, and water bodies. We perform a detailed comparative explainability study using Local Interpretable Model-Agnostic Explanations (LIME). For agricultural areas, the models select the correct regions for predictions. For build-up areas, man made structures like buildings are important factors for classification. For under-developed regions (forest cover), the model considers only a portion of green areas as important. For water bodies, LIME does not consider all parts of water as important for prediction.
## :busts_in_silhouette: Co-creators
* Nayan Gupta (nayangupta98@gmail.com)
* Bhavishya Tolani (bhavishyatolani@gmail.com)
