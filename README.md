A very helpful course list provided by 10-601 TAs Bhargav Hadya and Nichelle Phillips. Since the Piazza class is no longer active, I’m pasting it here for backup:

# What-ML-Course-Should-I-Take-Next

Here are some recommendations for future machine learning courses at CMU from current and previous staff. I’ve taken the liberty of organizing them roughly by subject, but many of these fit into multiple such categories.

## General

- **05-434/834, 11-344/663 Machine Learning in Practice**  
  A gentle introduction to machine learning in a hands-on way. This class has no coding, and shows you all about the practical side of machine learning, from train-test splits to data preprocessing to building simple models, and running error analysis and parameter tuning, all from a single user interface!  

  At the end of the class, you will be expected to deliver a project which is a great way to get hands-on experience with ML Models.

- **10-701 Introduction to Machine Learning (PhD)**  
  A more rigorous version of 301, with a more detailed emphasis on the math behind these algorithms. Similar structure with the homework, and also has a project where you dive deep into one specific area of ML. This class relies on a lot more probability and linear algebra knowledge at the start of the class, so if you decide to take it, prepare accordingly (No HW1 refresher in this class).

- **15-281 Artificial Intelligence: Representation and Problem Solving**  
  This course is about the theory and practice of Artificial Intelligence. You’ll learn about the algorithmic foundations of AI, how probability and AI are related, and how automated agents make decisions. You may see some 301/601 content again (HMMs, Bayes Nets, RL) but the instructors do a good job of making sure there isn’t significant overlap.

- **36-462/662 Special Topics: Methods of Statistical Learning**  
  Statistical learning is the process of making predictions on and discovering structure in datasets. Since this is a statistics course, it involves a little more probability and linear algebra and less coding (which is done in R), and the focus is on probabilistic models. Homework contains both theoretical problems/proofs and applications of the methods discussed to provided datasets.

## Theory

- **10-425/625 Introduction to Convex Optimization**  
  This is the undergrad / MS equivalent to 10-725. It is new as of Fall 2023. Course website [here](https://www.cs.cmu.edu/~mgormley/courses/10425/).

- **10-725 Convex Optimization**  
  The “spirit” of convex optimization AND non-convex optimization. Pretty heavy on the math side, but the class is structured super well in terms of assessments and is sort of the basis for basically all of ML. If you liked the GD/SGD stuff from earlier this course, you’ll probably enjoy this class. Mostly written math, with a few small coding assignments.  

  This class answers many theoretical questions you may have about optimizing ML models, such as:
  - “Why does SGD work?”
  - “How quickly do gradient descent algorithms converge?”
  - “What is that weird AdaGrad thing on HW5?”
  - “Why do we use convex optimization algorithms on non-convex functions like neural networks?”
  - “Why are neural networks designed the way they are?”
  - “Why does Zack keep talking about the edge of stability?”  

  The assignments mostly consist of written problem sets with minimal programming.  

  *Editor’s note: The S23 offering of the course is split into 2 minis with two different professors, and the above description may no longer be accurate for the first mini. Zack no longer talks about the edge of stability at CMU. AdaGrad is no longer on HW5. This course now has exams.*

- **10-732 Robustness and Adaptation in Shifting Environments**  
  This is a new course being offered in the fall by Zack Lipton, and while I can’t 100% say what the content is specifically, it will most likely be about the following sorts of questions: How do we build models when adversaries are trying to beat the system? How can we build models that can be deployed despite the underlying training distribution changing? Zack is an absolutely amazing professor and much of his lab’s current research is on this sort of robustness work, so I’m sure it’ll be amazing!  

  *Editor’s Note: The course was offered F22 and the course website can now be found online.*

## Deep Learning

- **10-417/617 Intermediate Deep Learning**  
  *Editor’s Note: This is regarded as a sort of middle ground between Introduction to Deep Learning and Advanced Deep Learning.*

- **10-707 Advanced Deep Learning**  
  This course is quite heavy on deep learning theory, though it has some pretty heavy practical implementation components as well. Do you want to learn about the math behind deep learning and get a better understanding of how and why it works? If so, this course is for you!  

  *Editor’s Note: Later offerings of the course are still heavy on theory, but are much lighter on practical implementation. Recent offerings of the course have had a midterm exam.*

- **11-485/685/785, 18-786 Introduction to Deep Learning**  
  This is probably one of the most time consuming classes I’ve taken at CMU. The content is mostly beginner friendly, and you get a LOT of hands-on experience building and training deep learning models in PyTorch. The majority of the emphasis is on doing homework assignments and training models, as opposed to complicated math/linear algebra. This class is what inspired a lot of the content in HWs 5 and 7, so if you enjoyed the coding portions of those homeworks, you will probably like this class. Just keep in mind that it is a very large time sink. But, you definitely come out of it way more confident in PyTorch and with a better understanding of what it’s like to train deep neural networks in practice.

- **10-423/623: Generative AI**  
  This is a (new as of S24) course on generative models and foundation models for text, images, code, music, videos, etc.  

  This is a very cool course where you’ll get to not only learn about, but also implement some of the most advanced models in the field of Gen AI right now. For example, for one of the assignments, we basically implemented a Llama-2 model, and for one of the other assignments, we generated images of cats using a stable diffusion model. At the end of the semester, you also get to work on a project of your choice where you could explore any state-of-the-art model that you are interested in. Even though it is a time consuming class, you will feel very rewarded and accomplished after having gone through the journey.

## Structured Data

- **10-418/618 Machine Learning for Structured Data**  
  This course is the undergrad/MS-level equivalent to 10-708. We focus on ML methods for structured prediction, this includes techniques from graphical models as well as deep learning and the (more modern) intersections of the two. Applications include NLP, computer vision, computational biology, etc. and anywhere that we want to make predictions about multiple interacting output variables. [http://418.mlcourse.org](http://418.mlcourse.org) was the first (and only) offering of the course.

- **10-708 Probabilistic Graphical Models**  
  This PhD level course focuses on the same topics as above, but is regarded as one of the most challenging courses offered by MLD. I’d recommend 10-418/618 unless you’re explicitly planning to do a fifth-year MSML or MSML in MLD.  

  This class takes a heavy emphasis on probabilistic learning, and the challenges with creating algorithms in that space. The class is based on graphical models, which use graphs (undirected and directed) to encode relationships in problems. I would say that this is really a statistics class, in that many of the algorithms use ideas from statistics, especially Bayesian statistics. The homeworks are challenging and long, and require knowledge of many different areas in math, such as linear algebra, probability, differential equations, multivariable calculus, and statistics. Overall, the course is taught very well, and you learn a lot, but you will have to put a lot of time into it.

## Reinforcement Learning

- **10-403/703 Deep Reinforcement Learning & Control**  
  If you’ve heard about how robots are going to take over the world, this class will tell you all about why that’s both true and false at the same time. Learn all about interesting work in reinforcement learning and implement some of it yourself. If you enjoyed the RL homework and want to learn about all the advances we’ve made since the Bellman equations, I would highly recommend this class.

## Application Domains

- **11-411/611 Natural Language Processing**  
  This is a standard introduction to NLP. It covers many different topics in NLP, and you will see many of the 10-301/601 topics again (e.g. HMMs, RNNs). However, it also covers enough NLP-specific information that you can expect to learn a lot of new material, so if you are interested in the subject, I would recommend taking it. If your interest is only in ML and not in NLP, I would recommend against taking the class.

- **11-755, 18-797 Machine Learning for Signal Processing**  
  If you are curious about non-neural net ways to do image recognition, voice recognition, image reconstruction, signal separation, etc.

- **11-777 Multimodal Machine Learning**  
  This is a graduate-level course that gives a general overview

 of current methods for incorporating multimodal data in machine learning models. There is a large focus on vision-language methods, but there is a lot of discussion on other modalities as well. The content is relatively high level, and most of the work revolves around reading papers and working on a final group project. The project involves exploring and modifying current state of the art (SOTA) models for common multimodal tasks, like robot navigation or visual question answering. Definitely a great class if you’re interested in learning more about multimodal ML and getting hands-on experience in fine-tuning/training a model for a task in this space.

- **16-385/720 Computer Vision**  
  Very good overview of the main areas in computer vision, and gives good hands-on projects where you can see the results of the algorithms. The class covers non-ML aspects of computer vision algorithms, such as geometry, physics, and motion. The class is very chill, as there are no exams and only 6 homework assignments. You may want to brush up on your linear algebra skills (Especially SVD 😈).  

  Content is honestly pretty engaging and the homework is generally long, but interesting. Realistically you probably wouldn’t need to be implementing any of the algorithms that you see in homework, but it does lay some good groundwork for general understanding of the field. The homework is largely focused on code (very coding heavy, watch out if this is not your forte), and you may need to write a handful of short proofs.

## Infrastructure

- **10-414/714 Deep Learning Systems: Algorithms and Implementation**  
  Extremely good class. You iteratively build your own deep learning library (somewhat similar to what you do in HW7) from the ground up, pretty comparable to PyTorch. You also build a backend array library (like numpy). This class mostly deals with practical issues of deep learning models. If you already have a grasp at the various deep learning architectures, and want to see how it is implemented, this is the class for you. The class also requires you to code in C++, and know a little bit about CUDA, so make sure that you have a solid background in those topics. The last part of the class asks you to build off your library and implement a new feature, and I found this to be extremely rewarding. Beware though, the homeworks take a while to do, and will require a greater time commitment than most classes you take. If you are interested in working on ML systems, or want to learn more about PyTorch, this is definitely the class to take.

## Scale

- **10-405/605/805 Machine Learning with Large Datasets**  
  Want to learn about how ML is applied at scale, when often we can’t even fit the data and/or the model on a single device? This class goes in pretty in-depth on the math behind doing both distributed ML in the first part, and then has a lot of applied assignments on distributed deep learning in the second. I think people have had mixed feelings about this course in the past, but I generally think it's a pretty informative course and will teach you how to use platforms like Databricks and AWS. Good mix of coding and written assignments.  

  *Editor’s Note: In addition to coding and written assignments, this course does currently have exams.*

- **10-745 Scalability in Machine Learning**  
  *Editor’s Note: The following is copied from the course description. “The course will have significant overlap with 10-405/605/805, but 10-745 will be faster-paced and go deeper into the theoretical investigations of the methods.”*

## Ethics and Philosophy

- **10-613/713 Machine Learning Ethics and Society**  
  We’ve all heard about ML models going wrong in real life, from the Instagram algorithm to criminal recidivism. How do we go about understanding bias in models? How do we make information about our models accessible to everyone? In this class, we explore (mathematically, and by case study) various approaches to analyzing fairness and interpretability in machine learning.  

- **10-721 Philosophical Foundations of Machine Intelligence**  
  What is intelligence? What is science? What is causality? If you’ve ever been interested in the high level issues in ML (like truly intelligent robots or predicting causal relationships), this class will pretty deeply go into how such questions could, and should be answered. There’s no coding, no math, just purely reading philosophical papers and discussing them in a small group. I had never taken a philosophy course before, but it’s a super interesting class and a nice change of pace from more quantitative ML courses.

## Biology

- **15-386/686 Neural Computation**  
  This is a really interesting (and hopefully pretty light) course that does a fantastic job of connecting ML concepts to what’s actually seen in neuroscience. For example, you’ll learn that the “activation functions” of some neurons look like the sigmoid function, and some look like ReLU. In fact, the “objective functions” of many neurons (based on our current models) appear to have regularization terms! I took the course this semester and if you’re looking for a class that isn’t too much work and covers interesting topics, I’d recommend this class.

- **15-387, 86-675 Computational Perception**  
  *Editor’s Note: This is the Neural Computation instructor’s offering on alternate semesters.*
