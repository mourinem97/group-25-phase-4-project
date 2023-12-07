Overview
(source: Wikipedia)

Pneumonia is an inflammatory condition of the lung primariy affecting the small air sacs known as alveoli in one or both lungs. It can be caused by infection with viruses or bacteria; and identifying the pathogen responsible for Pneumonia could be highly challenging.

Diagnosis of Pneumonia often starts with medical history and self reported symptoms, followed by a physical exam that usually includes chest auscultation. A chest radiograph would then be recommended if the doctors think the person might have Pneumonia. In adults with normal vital signs and a normal lung examination, the diagnosis is unlikely.

Business Problem
Pneumonia remains a common condition associated with considerable morbidity and mortality - each year it affects approximately 450 million people, and results in about 4 million deaths. Outcome is often improved by early diagnosis, yet the traditional radiograph assessment usually introduces a delay to the diagnosis and treatment. Therefore, fast and reliable computer-aided diagnosis of the disease based on chest X-ray could be a critical step in improving the outcomes for Pneumonia patients.

For this project, I have developed and evaluated various Convolutional Neural Networks that can quickly classify Normal vs. Pneumonia frontal chest radiographs. The implementation of these models could help alert doctors and radiologists of potential abnormal pulmonary patterns, and expedite the diagnosis.

Dataset
The dataset was collected from Guangzhou Women and Children’s Medical Center (Guangzhou, China) pediatric patients of one to five years old.

The dataset is available on:

Mendelay Data
or Kaggle
The diagnoses for the images were then graded by two expert physicians, and checked by a third expert before being cleared for training the AI system.

Dataset Structure
The dataset is divided into 2 directories:

train
test
Within each directory, there're 2 sub-directories:

NORMAL
PNEUMONIA