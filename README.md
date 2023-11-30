# ChildRescueForce
Utilizes AI and drone capability to rescue children who have been illegaly trafficked and sold.

# Logo
<img width="254" alt="Screen Shot 2023-10-26 at 4 05 29 PM (1)" src="https://github.com/trich9/Company-Design/assets/143112521/9a73451e-8a18-4702-8194-c5f2bd0db50b">



# Data/Problem
According to the FBI, in 2022 there were 359,094 NCIC entries for missing children. The unfortunate part about this statistic is that many kids are not reported missing so this number, as bad as it is can be misleading. The NEMC which works with law enforecement to recover children who have been labeled as missing recovered 88% of those identified people. 


# Implementation and Strategy

Using drones to prevent child trafficking is a complex and multifaceted task that requires a combination of technology, collaboration, and strategic planning. Here's a strategy to effectively utilize drones in this important mission:

  Data and Intelligence Gathering:

- Collect and analyze relevant data to identify high-risk areas and potential trafficking routes.
Collaborate with intelligence agencies, NGOs, and local communities to gather actionable information on known or suspected traffickers.
Drone Technology Integration:

- Acquire and deploy drones equipped with advanced technology such as high-resolution cameras, thermal imaging, facial recognition, and GPS tracking.
Ensure that drones have the capability to operate in various weather conditions and remote areas.

Drone Surveillance and Monitoring:

- Conduct routine aerial surveillance in known or high-risk areas where child trafficking is prevalent.
Monitor border crossings, transportation hubs, and remote border regions using drones to identify suspicious activities.
Real-time Data Analysis:

- Implement a centralized command center where data from drone surveillance is analyzed in real-time.
Use AI and machine learning algorithms to detect unusual patterns or behaviors that may indicate child trafficking activities.
Rapid Response:

- Develop protocols for immediate response when suspicious activities are identified.
Train law enforcement and task force members to act swiftly and effectively in coordination with drone data.




# Data Deck
The data deck we have here is useful for many reasons but here are a few I would like to highlight 
- Training Machine Learning Models: Machine learning models learn patterns and make predictions based on the data they are trained on. A high-quality and diverse dataset is fundamental for training accurate and robust models

- Quality of Predictions: The quality and representativeness of the dataset directly impact the quality of predictions made by machine learning models. A comprehensive dataset helps the model generalize well to new, unseen data
  
- Iterative Improvement: Iterative model improvement often involves refining datasets. By collecting additional data, removing noisy or irrelevant samples, or augmenting the dataset, the model's performance can be enhanced
  
- In summary, a high-quality, well-curated dataset is essential for training accurate, unbiased, and reliable machine learning models. It serves as the foundation upon which models learn and make predictions, influencing their performance and real-world applicability
  
<img width="666" alt="Screen Shot 2023-11-14 at 1 17 56 PM" src="https://github.com/trich9/Company-Design/assets/143112521/531f0f1d-51a4-40fe-9e1c-d36ce7482769"> <img width="654" alt="Screen Shot 2023-11-14 at 1 17 35 PM" src="https://github.com/trich9/Company-Design/assets/143112521/6df2916c-91c7-4862-bff2-84d6275971ea"> <img width="357" alt="Screen Shot 2023-11-14 at 1 17 19 PM" src="https://github.com/trich9/Company-Design/assets/143112521/315e67e3-ca5a-43fa-90e3-9813f537102f">



[Data_Deck](https://docs.google.com/presentation/d/1V7qAX-prGVKvm_ae6_dDfJEwgpFS4Ctx_0kMRUNZzBs/edit#slide=id.g278ff293417_0_0)

# Pose 

The Pose Machine is a deep learning-based architecture designed for human pose estimation in images. It operates by detecting and locating key points or joints on a person's body, creating an estimation of the body's pose.


- Deep Learning Architecture: Pose Machine typically employs a deep neural network, often a Convolutional Neural Network (CNN), for the task of pose estimation.

- Multi-Stage Architecture: The Pose Machine architecture typically consists of multiple stages or modules that progressively refine the estimation of human joint locations.

- Hierarchical Structure: Each stage in the Pose Machine model refines the predictions made by the previous stage. It gradually improves the accuracy of keypoint localization by refining the estimation iteratively.

- Heatmap Representation: Usually, Pose Machine models predict a heatmap representation for each key joint in the body. These heatmaps indicate the likelihood or confidence of the presence of a joint at various locations in the image.

- Iterative Refinement: The model iteratively improves the accuracy of joint localization by integrating context and information from previous stages, leading to more precise pose estimation.

- Application: Pose Machines are widely used in various applications such as action recognition, sports analytics, augmented reality, fitness tracking, human-computer interaction, and more, where understanding human poses is crucial.

- Overall, Pose Machine models are effective in estimating human poses from images, providing valuable information about the body's positioning and movement, which finds applications across several domains.
  
<img width="368" alt="Screen Shot 2023-11-30 at 4 10 01 PM" src="https://github.com/trich9/Company-Design/assets/143112521/1eaa7721-9a18-478e-a2f0-569bdb4e5fa9">

[Pose Images](https://colab.research.google.com/drive/11gPxH3PNabN13PETE8x3EM4neo9jTzf4#scrollTo=9B57XS0NZPIy)

# Alexnet Filters 
- AlexNet is a pioneering convolutional neural network (CNN) architecture that significantly advanced the field of computer vision. It consists of eight layers, including five convolutional layers followed by max-pooling layers and then three fully connected layers. AlexNet predominantly used the Rectified Linear Unit (ReLU) activation function, which helped alleviate the vanishing gradient problem and speed up training. AlexNet's successful implementation was greatly aided by the utilization of GPUs, specifically designed to handle the parallel computations required by neural networks, making training faster compared to traditional CPUs
  
<img width="1401" alt="Screen Shot 2023-11-14 at 3 40 21 PM" src="https://github.com/trich9/Company-Design/assets/143112521/e307d3d0-96bf-4e3f-9f3d-829446212bf8">

[Alexnet Filters](https://colab.research.google.com/drive/16yId_Y7fSr6D89m-uU-RbUlArJ8bUmRL?usp=sharing#scrollTo=WANJibeUNghZ)

# Feature Map

- A feature map is a 3-dimensional representation of learned features within a convolutional neural network (CNN). In the context of CNNs used in image processing, a feature map refers to the output obtained after applying a filter (also called a kernel) to an input image.

- When an image passes through a convolutional layer in a CNN, the filter scans across the image, performing a mathematical operation (convolution) between the filter and the portions of the image it covers. This operation extracts specific patterns or features, such as edges, textures, or shapes, from the input image.

- Each filter in a convolutional layer generates its own feature map. The feature map highlights areas in the input image where the filter detects relevant features based on its learned parameters. As a result, multiple filters create multiple feature maps, each capturing different aspects or representations of the input data.
  
[Feature map](https://colab.research.google.com/drive/11IJ27NHDdtqZASIkYMjCRH-39-Peaz3F?usp=sharing#scrollTo=mDMIqD-twIVd)

<img width="1191" alt="Screen Shot 2023-11-12 at 8 50 29 PM" src="https://github.com/trich9/Company-Design/assets/143112521/baaf59f8-a379-483e-bdd6-95d1d3c7f202">


# WANDB
- Weights and biases are fundamental components used in artificial neural networks, a core concept in machine learning.

- Weights: In a neural network, weights represent the strength of connections between neurons. Each connection between nodes in different layers of a neural network has a weight associated with it. These weights are adjusted during the training process to enable the network to learn and make accurate predictions.

- Biases: Biases are additional parameters in neural networks that allow the model to fit better to the given data. They provide flexibility to the model by allowing it to represent patterns that don't necessarily pass through the origin (0,0). Each neuron typically has its own bias term, which helps the model in learning and making predictions accurately.
  
<img width="903" alt="Screen Shot 2023-11-12 at 8 39 14 PM" src="https://github.com/trich9/Company-Design/assets/143112521/8f481160-59be-4075-9fdb-946e1edb4215">

# Contact me at 
trich2023@fau.edu


