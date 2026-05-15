## Course description
This hands-on graduate-level course introduces students to the application of machine learning techniques in the field of environmental sciences. It covers the main classes of supervised and unsupervised machine learning algorithms and provides practical experience in training and validating real-world models. Students will gain the skills necessary to analyze environmental data, make predictions, and uncover hidden patterns.

## Prerequisites
Prior knowledge of machine learning fundamentals, including linear algebra, gradient descent and backpropagation. Basic programming skills (e.g., Python) are required.

## Course Objectives
By the end of the course, students should be able to:
1. Understand the principles of machine learning and its applications in environmental sciences.
2. Apply supervised and unsupervised machine learning techniques to environmental data.
3. Evaluate and validate machine learning models using appropriate metrics.
4. Interpret and communicate results effectively.
5. Develop proficiency in using machine learning libraries and tools in Python.

## Resources

 - Office hours: TBD
 - Online [JupyterBook](https://climate-analytics-lab.github.io/deep-learning-book/intro.html) with course notes, updated as we go along.
 - Github [repository](https://github.com/climate-analytics-lab/sioc209-2026-sp) with notes and slides. If you find any mistakes or have suggestions for improvements you can always make a pull request!
 - Remote Jupyter Notebook instances on [Google Colab](http://colab.research.google.com/)
 - Google Drive link with required example [data](https://drive.google.com/drive/folders/1G7PfsNedS9S-L4h7xM8IlYr0OZDOLm25?usp=sharing).

**Textbooks:**
* [Understanding Deep Learning](https://udlbook.github.io/udlbook)
* Deep Learning with Python (2nd Edition) by François Chollet
* Supplementary readings and research papers

**Other resources:**
* For an introduction to working with environmental data in Python this is an excellent resource: [An Introduction to Earth and Environmental Data Science](https://earth-env-data-science.github.io/intro.html)
* This course provides useful introductory material on machine learning: [Machine Learning for Earth and Environmental Sciences](https://tbeucler.github.io/2023_MLEES_Published_Book)

## Course Schedule

🎥 = Remote / recorded &nbsp;&nbsp; 👥 = Guest lecture

| Week | Date | Lecture | Deadlines | Notes |
|------|------|---------|-----------|-------|
| 1 | Tue 31 Mar | [**Introduction**](00_setup/01_introductory_slides.ipynb)<br>*Course overview; what ML can do for environmental science; Python setup* | | |
| | Thu 2 Apr | [**What is deep learning?**](01_intro/02_course_overview.ipynb)<br>*Neural network intuition; supervised vs. unsupervised; key terminology* | | |
| 2 | Tue 7 Apr | [**Data collection and preparation**](01_intro/03_data_collection_and_prep.ipynb)<br>*Pandas; handling missing data; train/test splits* | | |
| | Thu 9 Apr | [**Feature engineering**](01_intro/04_feature_engineering.ipynb)<br>*xarray for multi-dimensional data; spatial and temporal features; convolutions* | | |
| 3 | Tue 14 Apr | [**Regression: ANNs**](02_regression/06_neural_networks.ipynb)<br>*Activation functions; gradient descent; backpropagation; MLP regression* | | |
| | Thu 16 Apr | **No Lecture** | | 🎥 Remote |
| 4 | Tue 21 Apr | [**Regression: Deep NNs**](02_regression/07_deep_neural_networks.ipynb)<br>*RNNs, LSTMs, Transformers; CNNs for spatial data* | | |
| | Thu 23 Apr | [**ClimateBench**](applications/ClimateBench/assignment_1.ipynb)<br>*Climate model emulation; applying regression models to real-world emissions data* | Assignment 1 set | |
| 5 | Tue 28 Apr | [**Classification**](03_classification/08_cnn_classification.ipynb)<br>*CNNs for images; softmax and cross-entropy; confusion matrices; transfer learning* | | 🎥 Remote |
| | Thu 30 Apr | **No Lecture** | Assignment 1 due<br>Assignment 2 set | |
| 6 | Tue 5 May | [**Object detection and segmentation**](04_detection/09_object_detection.ipynb)<br>*YOLO, Faster R-CNN; U-Net; bounding boxes; IoU; semantic segmentation* | | |
| | Thu 7 May | **Acoustic detection**<br>*Detecting marine mammals from hydrophone recordings; spectrograms and CNNs* | Assignment 2 due Mon 11 May | 👥 Michaela |
| 7 | Tue 12 May | **Physics-informed neural networks**<br>*Encoding physical constraints in the loss function; solving PDEs with neural networks* | | 👥 Peter Gerstoft |
| | Thu 14 May | [**PINN example**](05_physical/10_physics_informed_NNs.ipynb)<br>*Worked PINN examples* | Assignment 3 set | |
| 8 | Tue 19 May | [**Clustering**](06_unsupervised_learning/11_clustering.ipynb)<br>*K-means; hierarchical clustering; self-organizing maps; elbow method; silhouette scores* | | |
| | Thu 21 May | [**Dimensionality reduction: AE, Tile2Vec**](06_unsupervised_learning/12_dimensionality_reduction.ipynb)<br>*PCA; t-SNE; autoencoders; contrastive learning for spatial embeddings* | Assignment 3 due | |
| 9 | Tue 26 May | [**Learning satellite images**](06_unsupervised_learning/13_contrastive_learning_example.ipynb)<br>*SimCLR; Tile2Vec; unsupervised cloud morphology classification* | Project set | |
| | Thu 28 May | [**Generative models: GANs, VAEs**](07_generative_models/14_generative_models.ipynb)<br>*VAE latent spaces; adversarial training; diffusion models; climate applications* | | |
| 10 | Tue 2 Jun | [**Large language models**](07_generative_models/15_llms.ipynb)<br>*Transformer architecture; pre-training and fine-tuning; tool use; scientific applications* | | |
| | Thu 4 Jun | [**Project presentations**](08_project/project.ipynb) | Project due Fri 5 Jun | |

*This schedule is subject to change as the course progresses.*

## Grading
* Three assignments worth 20% each
* One final project worth 40%:
    * 30% for report and 10% for 5-minute presentation
* Coursework and final project can be completed collaboratively, but must be submitted individually. Co-authors should be explicitly declared.

## Academic Integrity
Make the best use of the expertise of the staff to learn what you need to know to really do well in the course. Act with integrity, and don't cheat.
If you do cheat, we will enforce the UCSD Policy on Integrity of Scholarship. This means: You will fail the course, no matter how small the affected assignment, and the Dean of your college will put you on probation or suspend or dismiss you from UCSD.

**Why is academic integrity important?**
Academic integrity is an issue that should be important to all students on campus. When students act unethically by copying someone's work, taking an exam for someone else, plagiarizing, etc., these students are misrepresenting their academic abilities. This makes it impossible for instructors to give grades and for the University to give degrees that reflect student knowledge. This devalues the worth of a UCSD degree for all students, making it important for the entire campus to band together and enforce that all members of this community are honest and ethical. We want your degree to be meaningful and we want you to be proud to call yourself a graduate of UCSD!

The [UCSD Policy on Integrity of Scholarship](http://academicintegrity.ucsd.edu/process/policy.html) and this syllabus list some of the standards by which you are expected to complete your academic work, but your good ethical judgment (or asking us for advice) is also expected as we cannot list every behavior that is unethical or not in the spirit of academic integrity. Ignorance of the rules will not excuse you from any violations.

**What counts as cheating?**
In SIO209 you can read books, surf the web, talk to your friends and the SIO209 staff to get help understanding the concepts you need to know to complete your assignments. However, all code must be written by you, together with your partner if you choose to have one and if allowed.
The following activities are considered cheating and **ARE NOT ALLOWED** in SIO209:
* Using or submitting code acquired from other students (except your partner, where allowed), the web, or any other resource not officially sanctioned by this course
* Having any other student complete any part of your assignment on your behalf
* Acquiring exam questions or answers prior to taking an exam
* Completing an assignment on behalf of someone else
* Using someone else's clicker for them to earn them credit or giving your clicker to someone else so that they can participate for you to earn credit
* Providing code, exam questions, or solutions to any other student in the course
* Using any external resource on closed-book exams

The following activities are examples of appropriate collaboration and **ARE ALLOWED** in SIO209:
* Discussing the general approach to solving homework problems or a final project (what is the best data structure, what function might be helpful).
* Getting help and guidance from LLMs such as ChatGPT on model structure and coding.
* Talking about debugging strategies or debugging issues you ran into and how you solved them
* Discussing the answers to exams with other students who have already taken the exam after the exam is complete
* Using code provided in class, by the textbook or any other assigned reading or video, with attribution
* Google searching for documentation on Python

**How can I be sure that my actions are NOT considered cheating?**
To ensure that you don't encounter any problems, here are some suggestions for completing your work.
* Don't look at or discuss the details of another student's code for an assignment you are working on, and don't let another student look at your code.
* In general, do not ask "How?" questions.
* Don't start with someone else's code and make changes to it, or in any way share code with other students.
* If you are talking to another student about an assignment, don't take notes, and wait an hour afterward before you write any code.
