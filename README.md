# Matching-of-Hand-Dorsal-Veins-through-Explainable-AI
Applied deep learning and computer vision with tools like YOLOv8 Nano, VoTT, and GradCAM to achieve explainable AI for matching hand dorsal veins.

1. Analyzed a dataset of over **11,043 RGB-colored dorsal palm images** using explainable AI techniques to build a biometric
authentication system with interpretable outputs.
2. Employed **VoTT (Visual Object Tagging Tool)** for manual bounding box annotation, enhancing feature detection accuracy
and model interpretability in the biometric system.
3. Leveraged the **YOLOv8 nano model** to achieve precise localization of dorsal palm images, attaining high accuracy **(99.9%
training, 95.3% validation)** through semantic and pixel-level segmentation technique.

**Publication**: https://link.springer.com/chapter/10.1007/978-981-97-6352-8_32 

**Abstract**: Palm-dorsal images can be used as a biometric trait to identify the human subjects. The veins present in the palm dorsal regions possess unique patterns which can be employed for the identification purposes. This paper works toward effective localization of the palm-vein regions from the hand dorsal images, especially under the colored image acquisition setups. The experimentation is completed with the benchmark public hand dorsal dataset, known as PolyU HD Dataset. The proposed approach commences with preparation of a viable ground truth from the images employed dataset. The proposed approach works with the you-only-look-once (YOLO) model to detect the bounding boxes comprising the palm-dorsal-vein regions with high accuracy. The performance analysis is furnished through popular metrics like intersection over union (IoU), accuracy, and mean average precision (mAP). The values acquired for mean Average Precision at 50% intersection over union threshold (mAP 50) were 99.5% and the mAP 50-95 was determined to be 67.2%. The interpretability of the trained YOLO model is also demonstrated through Eigen-CAM generated heatmaps. The proposed approach yields an accuracy of 99.7%, and it seems to be working well in the large orientation variations and cross-dataset evaluations.


