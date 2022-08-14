# Generative-Adversarial-Networks

# Background
Generative Adversarial Networks are a Machine Learning approach that try to learn the underlying distribution by creating fake samples using generative modelling. GANs consist of a generator and a discriminator that form a two player game. The generator tries to create fake samples that seem to come from the required domain, while the discriminator tries to distinguish between real and generated samples. In doing so, the generator and discriminator compete against each other in a two player minimax game. 

# Project Overview
The adversarial training between the generator and discriminator can be formulated as a min-max optimization problem. However, proving the stability of GANs is not trivial. In this project, we will first understand the architecture of GANs and analyse the stability of traditional GANs.We will then extend this analysis to other variations of GANs and incorporate it into the architecture to improve the stability.

# Project Structure
## Week 1, 2 
Understanding the architecture of Generative Adversarial Networks, and viewing the adversarial training as a two-player game.

Implementing GANs for a simple regression or generative task to develop a clear understanding of GANs

## Week 3, 4
Analyzing the stability of traditional GANs and Wasserstein GANs.

## Week 5, 6
Introducing a skip-GAN which adds another model to process the data prior to the GAN via a skip connection with the GAN. Analyzing the stability of the skip-GAN and running experiments to compare the stability performance of the skip GAN with the traditional GAN

## Week 7 - 12
Studying the model dynamics with different prior models and variations in the architecture.

Improving the stability of the architecture by incorporating these findings. 

# Prerequisites
Basic understanding of Machine Learning

Familiarity with differential equations

# Mentor Contact
[Rajvi Sampat](https://github.com/rajvi-git) ([2018B4A70820G](mailto:f20180820@goa.bits-pilani.ac.in))

[Pronoma Banerjee](https://github.com/pronoma) ([2019B4A70690G](mailto:f20190690@goa.bits-pilani.ac.in))

# Faculty Supervisor
[Dr. Snehanshu Saha](https://www.bits-pilani.ac.in/goa/snehanshus/profile)
