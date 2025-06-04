# SIUDIN - Machine Learning
Coding Camp Capstone Project 2025
## Description
Machine Learning models can be leveraged to enhance a content-based filtering approach in the recommendation system. This approach analyzes the similarity and relevance of Education Level (Jenjang), Subject (Mata Pelajaran), Material (Materi), and Sub Material (Sub Materi) in relation to the user's learning preferences and targeted education stage. As a result, it delivers personalized learning content tailored to the user’s interests.
## Method
Content-based Recommendation Systems with Neural Networks

## Tools
- Python
- Sklearn
- Math
- TensorFlow
- TensorFlow js
- NumPy
- Pandas
- Matplotlib
- Google Colab
## Dataset
We created the dataset from scratch by manually specifying the variables using Microsoft Excel. Our data sources are YouTube and Ruangguru. The variables in this dataset include **Jenjang**, **Mata Pelajaran**, **Materi**, **Sub Materi**, **Link**, and **Pertanyaan**. The explanation of each variable is as follows:

- **Jenjang**: The stage of education, covering secondary education, namely Junior High School (SMP) and Senior High School (SMA).
- **Mata Pelajaran**: The name of the subject taught at the respective education level.
- **Materi**: The main chapter or subject area within a given subject.
- **Sub Materi**: A more specific part or subsection of a topic that covers detailed aspects of the main topic.
- **Link**: A link to the learning video from YouTube and Ruangguru.
- **Pertanyaan**: Items or questions designed to assess students' understanding of the specific Subtopic being studied.

[Dataset Materi dan Kuis](https://docs.google.com/spreadsheets/d/1CapDuMNvtWG-Qnjn5O-e-Lun1x81o5knV9HNdCMUnjA/edit?gid=1323199543#gid=1323199543)

In addition, we also created a mission dataset containing daily tasks that students must complete to support the continuity of the learning process.

[Dataset Misi](https://docs.google.com/spreadsheets/d/1CapDuMNvtWG-Qnjn5O-e-Lun1x81o5knV9HNdCMUnjA/edit?gid=988267510#gid=988267510)
## How to Recommend
When a user inputs their Education Level (Jenjang), Subject (Mata Pelajaran), Material (Materi), and Sub Material (Sub Materi), the model will present relevant content tailored to the user’s preferences, delivering engaging learning videos.
## Setup Environment
This project uses the Google Colaboratory (Google Colab) IDE. Make sure to install the **requirements.txt** dependencies before running **notebook.ipynb**.

Alternatively, it can be run using a virtual environment with **conda**:
```
conda crate --name siudin python=3.9
conda activate siudin
pip install requirements.txt
jupyter-notebook
```

You can also use **pipenv**:

```
mkdir siudin
cd siudin
pipenv install
pipenv shell
pip install requirements.txt
jupyter-notebook
```
