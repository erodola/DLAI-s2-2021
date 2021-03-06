## Deep Learning & Applied AI @Sapienza

Course material, 2nd semester a.y. 2020/2021, Dept. of Computer Science

### News

- **13/07/2021:** The scores for the written exam (July 08) are now published; please refer to [this issue](https://github.com/erodola/DLAI-s2-2021/issues/24) for details.
- **28/04/2021:** The list of projects has been published. Please refer to [this issue](https://github.com/erodola/DLAI-s2-2021/issues/19) for further details.
- **21/04/2021:** Please fill out the OPIS questionnaire (instructions [here](https://www.uniroma1.it/sites/default/files/field_file_allegati/guided_path_to_access_students_opinions_questionnaire_2020_2021.pdf)). The code for this course is KIW0A907.

### Logistics

**Lecturer:** Prof. Emanuele Rodolà

**Assistants:** Dr. Luca Moschella, Dr. Antonio Norelli

**When:** Wednesdays 09:00--12:00 and Thursdays 17:00--19:00 ([official schedule](https://www.studiareinformatica.uniroma1.it/laurea-magistrale/orario-lezioni))

**Where:**

- Physically: Aula 1 - Aule L Via del Castro Laurenziano 7a

*Important*: Please use **Infostud Lab** (not Prodigit!) for booking a seat in the classroom. This should be done **no later than 48h** from the start of the lecture.

- Virtually: Zoom ([link to the virtual classroom](https://zoom.us/j/4752349941?pwd=U0doeGFLWFFDSWlzWWxvd0JGMDRndz09)), Meeting ID: 475 234 9941, Passcode: 3K7xrM.

**Q & A:** Please use the issue system of Github. [Here](https://github.com/erodola/DLAI-s2-2021) is the link to the course repository, you'll need to create a free account to access it.

### Pre-requisites

Programming fundamentals in **Python**; calculus; linear algebra.

### Textbook and reading material

Due to the continuously evolving nature of the topic, there is no fixed textbook as a reference. Specific material in the form of scientific articles and book chapters will be given throughout the lectures.

### Grading

Evaluation proceeds according to the following steps:

- A midterm self-evaluation test (optional, does not concur to the final grade)
- A final written exam (**mandatory**, accounts for 60% of the final grade)
- A project (**mandatory**, accounts for 40% of the final grade)
- An oral exam (optional, attributes at most 3 points, added to or subtracted from the final grade)

The _cum laude_ can be obtained only by taking the oral exam. For students who already have a very high score with written exam + project, the oral exam is meant to confirm the high score.

The list of **projects** is now published (details [here](https://github.com/erodola/DLAI-s2-2021/issues/19)). Each project must be accompanied with code to a github repository, and with a 2 page report using [this](https://github.com/erodola/DLAI-s2-2021/files/6393267/template.zip) fixed template. Projects can be made in groups of at most 2 students.

### Lectures

All the lectures (video, audio and chat script) will be recorded and stored in this [Google Drive folder](https://drive.google.com/drive/folders/1ByxH8071EwBJkkRpb1NpkyIG7MM3psHl?usp=sharing).

Please note that the audio quality will not be very good in general, due to technical issues.

**Date** | **Topic** | **Reading** | **Code & Data**
------------ | ------------- | ------------ | ------------
Wed 24 Feb | Introduction | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/01_intro/01-intro.pdf) |
Thu 25 Feb | Data, features, and embeddings | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/02_data/02-data.pdf) |
Wed 03 Mar | Tensor manipulation |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/01/01_Tensor_basics_2021.ipynb)
Thu 04 Mar | Linear algebra revisited | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/03_linalg/03-linalg.pdf) |
Wed 10 Mar | Tensor operations   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/02/02_Tensor_operations_2021.ipynb)
Thu 11 Mar | Linear regression, convexity, and gradients | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/04_linear/04-linear.pdf); [notes on matrix meta-mechanics](https://github.com/erodola/DLAI-s2-2021/raw/main/04_linear/04b-matrix.pdf) |
Wed 17 Mar | Linear models and Pytorch Datasets   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/03/03_Linear_models_and_Pytorch_Datasets_2021.ipynb) |
Thu 18 Mar | Going nonlinear, overfitting, and regularization | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/05_nonlinear/05-nonlinear.pdf) |
Wed 24 Mar | Logistic Regression and Optimization   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/04/4_Logistic_Regression_and_Optimization.ipynb) |
Thu 25 Mar | Stochastic gradient descent | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/06_sgd/06-sgd.pdf) |
Wed 31 Mar | Multi-layer perceptron and back-propagation | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/07_mlp/07-mlp.pdf) |
~~Thu 01 Apr~~ | ~~**No lecture due to Easter Holidays**~~ |  |
Wed 07 Apr | Autograd and Modules | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/05/5_Autograd_and_Modules_2021.ipynb) |
Thu 08 Apr | **Midterm self-evaluation test** | [midterm](https://github.com/erodola/DLAI-s2-2021/raw/main/midterm/sheet.pdf); [evaluations](https://github.com/erodola/DLAI-s2-2021/raw/main/midterm/evaluations.pdf) |
Wed 14 Apr | Convolutional Neural Networks   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/06/6_Convolutional_Neural_Networks_2021.ipynb) |
Thu 15 Apr | Convolutional Neural Networks | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/08_cnn/08-cnn.pdf) |
Wed 21 Apr | Uncertainty, regularization and the deep learning toolset  |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/07/7_Uncertainty,_regularization_and_the_deep_learning_toolset.ipynb) [![](https://shields.io/badge/-Coding_tutorial-9cf?style=flat&logo=github&labelColor=gray)](https://github.com/lucmos/DLAI2021-tutorial) |
Thu 22 Apr | **Invited lecture by Giambattista Parascandolo** Memorization and Invariances in Neural networks & Learning abstract models | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/09_invited/slides.pdf) | [Learning explanations that are hard to vary](https://github.com/gibipara92/learning-explanations-hard-to-vary); [Adaptive skip intervals](https://github.com/neitzal/adaptive-skip-intervals); [Teacher-student framework](https://openreview.net/forum?id=ECuvULjFQia)
Wed 28 Apr | Variational AutoEncoders   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/08/8_Variational_Autoencoders_(VAEs).ipynb) |
Thu 29 Apr | Regularization | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/09_regular/09-regular.pdf) |
Wed 05 May | Deep generative models | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/10_generative/10-generative.pdf) |
Thu 06 May | Adversarial training | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/11_adversarial/11-adversarial.pdf) |
Wed 12 May | CycleGAN and Adversarial Attacks  |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/09/CycleGAN_and_Adversarial_Attacks.ipynb) |
Thu 13 May | Geometric deep learning | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/12_gdl/12-gdl.pdf); [video by Michael Bronstein](https://drive.google.com/file/d/1-8oatGaKSiR0XFzprBktAIA9P5qDTco5/view) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/10/Geometric_deep_learning.ipynb) |
Wed 19 May | Self-attention and transformers | [slides](https://github.com/erodola/DLAI-s2-2021/raw/main/13_trans/13-trans.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2021/blob/main/labs/11/Transformers_2021.ipynb) |

**End**
