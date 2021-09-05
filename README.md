# Lecture Design Object Detection

![Example Image1](https://anonymous.4open.science/r/lecture_design_detection-5134/video5_0_2_shot20.jpg)

![Example Image2](https://anonymous.4open.science/r/lecture_design_detection-5134/video54_3_1_shot58.jpg)

Tensorflow lecture design object detection implementation proposed in the following paper:

```
"FitVid: Responsive and Flexible Video Content Adaptation",
Anonymous Author(s)
```

# Overview
Object detection task for lecture design elements (e.g., text boxes, diagrams, and talkin-head instructors) is challenging since video lectures involve diverse componenets ranged from titles to tables and instructors. Furthoermore, some of the elements such as titles and footers requires a high degree of localization. We compared four widely-used object detection models that include faster-RCNN, SSD based on ResNet, EfficientDet, and CenterNet, training them from scratch on [lecture design dataset](https://anonymous.4open.science/r/lecture-design-dataset-6270/README.md). After the comparison, we pretrained the model with the highest performance using DocBank ~\cite{docBank} and fine-tuned them on lecture design dataset. We fine-tuned the hyperparameters using brute force search for each model. The result demonstrated a positive transfer learning effect of pretraining a model on document layout dataset for lecture design detection task.

# Results
TBD
