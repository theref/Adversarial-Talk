# Adversarial Attacks Against Medical Deep Learning Systems

# Deep Learning in Medicine

The U.S. Food and Drug Administration announced the approval of the first computer vision algorithm that can be utilized for medical diagnosis without the input of a human clinician


Collage of some medical imaging applications in which deep learning has achieved state-of-the-art results. From top-left to bottom-right:

- mammographic mass classification
- segmentation of lesions in the brain 
- leak detection in airway tree segmentation 
- diabetic retinopathy classification (Kaggle)
- prostate segmentation
- nodule classification
- breast cancer metastases detection in lymph nodes
- human expert performance in skin lesion classification
- and state-of-the-art bone suppression in x-rays



# Adversarial Attacks

Stop signs - Witha perturbation in the form of only black and white stickers,we attack a real stop sign, causing targeted misclassification in 100% of the images obtained in lab settings, and in 84.8%of the captured video frames obtained on a moving vehicle(field test) for the target classifier.

Google Inception - We apply our algorithm to complex three-dimensional objects, using 3D-printing to manufacture the first physical adversarial objects.


# Why is Medicine important?

- Either sent for unnecessary treatment, or miss required treatment.
- Total global spend on healthcare is more than $7 trillion each year. Corruption takes many forms, depending on the country’s level of development and health financing system. The United States, for example, lost between $82bn and $272bn in 2011 to medical embezzlement, mostly related to its health insurance system
- Increasing use in clinical trials...individual cancer drug worth $1.67billion only four years after approval.



# Why is Medicine particularly susceptible?

- Ground truth is ambiguous, experts (radiologists) often disagree on well defined tasks.
- Images are highly standardized. Very different to the real word attacks we saw earlier which have varying angles and lighting
- Popular architecture are often used; quite possible that they will be public for transparancy...often pretrained ImageNet or Inception
- Many adversaries, at every step of a patient pathway there is someone who could profit


# Current Research



# Our plan
- Break the