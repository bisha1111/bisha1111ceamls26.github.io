---
layout: project
title: "About My Project"
permalink: /about-my-project.html

subtitle: "Trustworthy Multimodal AI for Skin Lesion Screening"

project_title: "DermaBridge: A Trustworthy Multimodal AI App for Skin Lesion Screening, Explainable Risk Assessment, and Smart Clinical Referral"

problem: |
  Skin cancer can become life-threatening when suspicious lesions are not recognized
  and examined early. Although artificial intelligence has shown promise in analyzing
  skin lesion images, many existing systems focus only on producing a classification.
  They may not explain how the result was reached, include important patient information,
  or guide the user toward appropriate medical care.

  Another major concern is fairness. Medical image datasets do not always represent
  every skin tone equally, which can cause an AI model to perform better for some
  patients than for others. This especially affects people with darker skin, who are
  often underrepresented in dermatology datasets. A model may have high overall
  accuracy while still producing less reliable results for certain skin-tone or
  demographic groups.

  DermaBridge addresses these limitations by combining skin lesion images with patient
  information such as age, sex, lesion location, and other available clinical metadata.
  The goal is to develop a system that screens suspicious lesions, provides understandable
  risk feedback, explains its predictions, and helps users locate appropriate medical
  care. DermaBridge is intended to support screening and referral decisions rather than
  replace a dermatologist or provide a final medical diagnosis.

approach: |
  My work covers the complete machine-learning research process, from preparing the
  data to communicating the final results:

  - Review research on skin lesion classification, multimodal medical AI, model
    explainability, algorithmic fairness, EfficientNet, ResNet, and other deep-learning
    architectures used in medical imaging.

  - Prepare and analyze skin lesion data from HAM10000 and PAD-UFES-20, with
    MRA-MIDAS also included in the broader project plan. These datasets contain
    skin lesion images, diagnosis labels, and available patient metadata.

  - Clean and standardize the datasets by mapping diagnosis classes, handling missing
    values, resizing images to 224 by 224 pixels, converting images from BGR to RGB,
    normalizing pixel values, and applying augmentation methods such as horizontal and
    vertical flipping, rotation, and Gaussian blur.

  - Examine class imbalance, diagnosis distributions, demographic information, and
    skin-tone representation. PAD-UFES-20 contains skin-tone information that can
    support subgroup analysis, while HAM10000 does not provide the same Fitzpatrick
    skin-type labels.

  - Train and compare baseline and advanced models, including traditional
    machine-learning models, EfficientNet-B0, ResNet50, and EfficientNetV2.

  - Monitor training and validation accuracy, loss, AUC, F1 score, and other evaluation
    measures to determine how well each model learns and performs on unseen data.

  - Develop a multimodal model that combines features learned from skin lesion images
    with patient metadata. This will allow the system to consider more than the image
    alone when producing a screening result.

  - Evaluate fairness by comparing model performance across available skin-tone and
    demographic groups. Differences in accuracy, error rates, or other performance
    measures will be documented and used to guide model refinement and bias-mitigation
    strategies.

  - Apply Grad-CAM to identify the image regions that influenced a prediction and use
    SHAP to explain how patient metadata contributed to the model's output.

  - Explore confidence-aware output methods so that uncertain predictions are presented
    carefully instead of being communicated as definite conclusions.

  - Build a functional DermaBridge prototype where a user can upload or scan a skin
    lesion image, enter relevant patient information, receive an AI-supported risk
    assessment, view an explanation of the result, and obtain location-aware referral
    information for a dermatologist, clinic, or hospital.

  - Use Python, Google Colab, TensorFlow, Keras, OpenCV, scikit-learn, pandas, NumPy,
    Matplotlib, and Gradio for data preparation, model development, visualization,
    evaluation, and prototype creation.

  - Communicate the research through weekly progress updates, model comparisons,
    a mid-summer presentation, a research paper, a poster, and a final symposium
    presentation.

outcome: |
  By the end of the Summer AI Research Institute, I expect to contribute to a refined
  multimodal artificial intelligence model that combines skin lesion images with patient
  metadata. The final model comparison will document the performance, strengths, and
  limitations of EfficientNet-B0, ResNet50, EfficientNetV2, and any other architectures
  evaluated during the project.

  I also expect to contribute to a working DermaBridge prototype that supports skin
  lesion screening, confidence-aware risk feedback, interpretable visual explanations,
  and location-aware clinical referrals. The prototype will demonstrate how trustworthy
  AI methods can be included in a practical healthcare application while keeping users
  informed about the model's reasoning, limitations, and uncertainty.

  The final research materials will include a research paper or technical report, a
  research poster, model performance visualizations, a fairness and bias evaluation
  report, Grad-CAM and SHAP explainability examples, and a final presentation of our
  findings. I hope the project will help researchers and healthcare professionals better
  understand how multimodal AI can support earlier skin lesion screening while
  prioritizing transparency, fairness, reliability, and responsible clinical use.

final_report_url: ""

grad_mentor:
  name: "Blessing Isoyiza Adeika"
  title: "Doctoral Researcher in Computer Engineering and Graduate Research Mentor"
  linkedin: "https://www.linkedin.com/in/blessing-isoyiza-adeika/"
  researchgate: "https://www.researchgate.net/profile/Blessing-Adeika"

faculty_mentor:
  name: "Dr. Saroj K. Pramanik"
  title: "Associate Professor of Biology and Faculty Research Mentor"
  website: "https://www.morgan.edu/biology/faculty-and-staff/saroj-pramanik"
---
