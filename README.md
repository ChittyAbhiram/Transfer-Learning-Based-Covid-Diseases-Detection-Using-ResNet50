# Transfer-Learning-Based-Covid-Diseases-Detection-Using-ResNet50

# 1. INTRODUCTION
A coronavirus (SARS-CoV-2) outbreak began on December 31, 2019, in Wuhan, the capital of Hubei Province in central China. The World Health Organization (WHO) announced a global health emergency on January 30, 2020, and the World Health Organization (WHO) declared a pandemic on March 11, 2020, after some hesitation. By 14 April 2020, there have been a total of 1,985,135 confirmed cases and 125,344 deaths. The United States has taken on a new role as a global hotspot of 605,354 cases and 25,394 deaths have been registered as of April 14, 2020. COVID-19 pathogenesis is being studied by researchers from several disciplines, as well as public health professionals, and develop measures for control. Imaging patterns on chest radiography and computed tomography (CT) for individuals diagnosed with COVID-19 have recently been discovered. Infected patients in Wuhan had bilateral lung opacities on 40 out of 41 (98 %) chest CTs, with lobular and subsegmental regions of consolidation being the most common findings. Other researchers discovered significant rates of ground-glass opacities and consolidation, with a rounded shape and peripheral lung distribution in some cases. Patients suspected of COVID-19 infection generally require a thoracic radiology examination. Early detection and diagnosis of the condition are critical in ensuring prompt treatment.

# Convolutional Neural Network
The Convolutional Neural Network is one of the most widely used deep neural networks (CNN). Convolution is a mathematical linear action between matrices that gives it its name. The convolutional layer, non-linearity layer, pooling layer, and fully-connected layer are some of the layers of CNN. Pooling and non-linearity layers do not have parameters, whereas convolutional and fully-connected layers have. In machine learning issues, CNN performs admirably. Particularly impressive were the applications that deal with picture data, such as the world's largest image classification data collection (Image Net), computer vision, and natural language processing (NLP), with the results obtained.

Due to the availability of large-scale annotated datasets and deep convolutional neural networks, significant progress has been made in picture recognition (CNNs). From a significant amount of training data, CNNs may learn data-driven, highly representative, hierarchical image characteristics. In the medical imaging area, however, acquiring datasets with as much detail as ImageNet is a difficulty. There are currently three basic strategies for successfully using CNNs for medical image classification: training the CNN from scratch, using pre-trained CNN features off the shelf, and undertaking unsupervised CNN pre-training with supervised fine-tuning. Transfer learning, or fine-tuning CNN models trained on natural image datasets for medical imaging tasks, is another effective strategy.

# Residual network (ResNet)
In transfer learning, AlexNet, AlexNetOWTBn, GooLeNet, Overfeat, and VGG models are more frequent. Many convolutional layers were stacked. Deep CNN networks have several challenges, including network optimization, the vanishing gradient problem, and degradation issues. The residual network (ResNet) is useful for solving difficult problems and improving detection accuracy. ResNet aims to address the challenges of deep CNN training, like saturation and accuracy loss. Because it is relatively easy to improve and provides higher accuracy, ResNet is a superior deep learning architecture. There's also the issue of declining gradient, which can be avoided by using the network's skip connections. The network's temporal complexity increases as the number of layers in the deep network architecture increases. A bottleneck design can help to simplify things. As a result, we decided to build our framework using the ResNet50 pre-trained model rather than other pre-trained networks with additional layers. Further down, the architecture is fully defined.


# 2. RELATED
