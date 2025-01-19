---
layout: archive
title: "Class Imbalaned Active Learning"
permalink: /class_imbalaced_AL/
author_profile: true
---
# Class-Balanced Active Learning for Image Classification

## **Brief Details:**

Neural networks obtain state-of-the-art results on several computer vision tasks such as large-scale object detection, image classification etc. However, the training of these often very large networks requires large-scale labeled datasets, that are labor intensive and expensive to construct. Generally, in real-world the amount of data that could be labeled is literary unlimited (e.g. in autonomous driving, or robotics applications). Given an initial labeled data set, deciding what new data to label from the **unlabeled data pool is a relevant research question addressed by active learning**. It aims to minimize the labeling effort while maximizing the obtained performance of the machine learning algorithm. Active learning has successfully been shown to reduce the labeling effort for image classification, object detection, regression, and semantic segmentation.

Several query strategies have been proposed for sample selection. The most popular ones are those based on informativeness [1] and representativeness [2] which demonstrated to be efficient for the task of selecting the most valuable samples. The informativeness criteria is responsible for selecting those samples which are the most uncertain (usually characterized by high-entropy) because they affect the generalization capability of the model (they are the ones which are mostly confusing the classifier, especially at the start of the active learning process when the number of labeled samples is small), while representativeness guarantees a diversity of the samples, following the underlying data distribution of the unlabeled data pool.

Visual recognition datasets are often almost uniformly distributed (e.g. CIFAR and ILSVRC). However, for many real-world problems data follows a long tail distribution, meaning that a small number of head classes are much more common than a large number of tail classes. Classification on such imbalanced data set is an important research topic. However, active learning is mostly studied on curated close to uniform datasets. Given the predominance of long-tail distributions, especially for real-world applications in which active learning is a crucial capability, we here study active learning for imbalanced datasets. The aim is to minimize the labeling effort, while maximizing performance when measured on a balanced test set.

Active learning aims to reduce the labeling effort that is required to train algorithms by learning an acquisition function selecting the most relevant data for which a label should be requested from a large unlabeled data pool. Active learning is generally studied on balanced datasets where an equal amount of images per class is available. However, real-world datasets suffer from severe imbalanced classes, the so called long-tail distribution. We argue that this further complicates the active learning process, since the imbalanced data pool can result in sub-optimal classifiers. To address this problem in the context of active learning, we would like to work on a general optimization framework that explicitly takes class-balancing into account. The proposed method is general (it should be able to be combined with most existing active learning algorithms) and can be effectively applied to boost the performance of both informative and representative-based active learning methods.

## **References :**

1) Donggeun Yoo and In So Kweon. Learning loss for active learning. In CVPR, pages 93–102, 2019.
2) Ozan Sener and Silvio Savarese. Active learning for con- volutional neural networks: A core-set approach. In ICLR, 2018..
3) Bengar, J. Z., Van De Weijer, J., Fuentes, L. L., & Raducanu, B. (2022). Class-Balanced Active Learning for Image Classification. Proceedings - 2022 IEEE/CVF Winter Conference on Applications of Computer Vision, WACV 2022, 3707–3716.




## **Message:**

Hello, I am [Tanmoy Mondal, Associate Professor](https://mondal-tanmoy.github.io/) at the FOX team in the CRIStAL lab. I am looking for a motivated student who will be interested in working on the following topic. This is an interesting topic where we will work on active learning techniques. Here are the following advantages if you work with me and in my team :

1) **You will be co-author:** This work is almost done (80-85%) and was submitted to a **top-tier A\* conference** in the computer vision domain but was unfortunately rejected. There are some improvements to be made and with these improvements, we will resubmit this article to another **top-tier A\* conference**. Hence, if you participate in this work, you will be on the author list of the paper.  Here are the advantages of having a research article in your name :

   1. You can proudly add this achievement (publication of research article) to your resume
   2. You can easily refer to the research article at the time of the interview and to other colleagues to explain your work
2) **You will learn teamwork:** This research is collaborative work, hence you will never work alone. You will learn to work in a team of researchers where you will participate in :

   1. Technical discussions and meetings
   2. Collaborative writing of code in Python and working with Git as a team (you will have practical use of git commit, push, pull-request, co-pilot, etc.)
   3. You will learn to follow proper coding standards, used in the industry
   4. You will have your own GitHub repository which you can easily give reference to your employer or interviewer. In that manner, the interviewer can quickly see your coding standards and knowledge from the code, uploaded in your GitHub repository.
3) **Gain domain knowledge:** You will gain proper domain knowledge on this topic of research, where you will have exposure to **reading and understanding the top-tier research articles**. Then you will learn about how to implement the research papers and how to innovate and apply innovative ideas for the improvement of the state-of-the-art techniques. You will learn how to think about finding innovative ideas and try several of such ideas to improve the performance of a technique.
4) **National & International Collaboration:** You will be able to work in collaboration with other PhD students and faculties from other research labs in France and other countries.  Here are some of the national and international collaborations that you can be quickly part of:

   * **IMT Atlantique, Brest, France** : [Lucas DRUMETZ, Associate Professor](https://www.imt-atlantique.fr/fr/personne/lucas-drumetz), Département Mathematical and Electrical Engineering
   * **University of La-Rochelle, France:** [Musab Al-Ghadi, Post-doctorate](https://www.linkedin.com/in/musab-alghadi/) researcher at L3I laboratory
   * [L2TI](https://www-l2ti.univ-paris13.fr/) **of [Institut Galilée](https://galilee.univ-paris13.fr/) in [Université Sorbonne Paris Nord](https://www.univ-spn.fr/), France** : [Zuheng Ming](https://hengxyz.github.io/), Associate Professor
   * [BITS, Pillani, India](https://www.bits-pilani.ac.in/) **:** [Abhijit Das](https://sites.google.com/site/dasabhijit2048/home), Assistant Professor, India
5) **Recommendation Letter:** I will write a recommendation letter, detailing all the work done by 	you and your positive points, based on our experience of working together. This recommendation letter will help you in your professional career in academics and industries.

   * **Guide to find PhD:** This working experience will open the door for you to find PhD positions around the world. If we have PhD funding in our research group then you will get priority otherwise I will be happy to recommend you to other faculty members (whom I know) if they have PhD positions. Furthermore, I will **guide you regarding the techniques and strategies** to find PhD positions around the world.
6) **Personal web-page and project page:** For this research project, we will build a project page, where all the details (method, results, analysis, conclusion, references, etc.) will be mentioned. Some examples are [here](https://ayankumarbhunia.github.io/Sketch2Saliency/) and [here](https://ayankumarbhunia.github.io/Sketch2Saliency/). Your name will be mentioned on such page as the co-author and as a team member. Hence, you can refer this project page to anyone in your professional career.

Furthermore, I recommend and help every student to have a personal website. Some examples are [here ](https://mondal-tanmoy.github.io/)and [here](https://hengxyz.github.io/). I will guide and help you to make one of such your **personal free website**. Such a website can give reference to anyone in your professional network (e.g. can add in your email signature) which will help others to quickly & easily know about you.
7)  **List of students on my academic page:** I will add you to my personal academic website as one of my students who have worked under my guidance and performed a research project. This will definitely help you in your professional career.**
8)  **Participate in seminars and conferences:** I will guide you to participate in several technical seminars, technical & scientific discussions, and conferences (either free or paid). In the case of paid conferences and seminars (where registration fees are required), if we have a fund that allows us to pay, then we will try to help you to participate.

So, if you find all these benefits of working with me in this project will actually help you then don’t hesitate to contact me and we can discuss more in details. Following is the brief description of the research topic.
