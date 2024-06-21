## Selected Projects In Data Science, Machine Learning, NLP, LLM's, and Computer Vision

<style>
  figure {
    margin: 1em 0;
  }
  figure img {
    max-width: 100%;
    height: auto;
  }
  figcaption {
    color: #555;
    margin-top: 0.5em;
  }
</style>


---

### Robo-CSK-Organizer: Enhancing Robotic Intelligence with Commonsense Knowledge

---

#### The Problem

Domestic robots often struggle with nuanced decision-making in dynamic environments. Traditional AI systems lack the ability to understand commonsense knowledge (CSK) like humans, leading to inefficiencies and incorrect object placements. For instance, deciding whether a pear should be placed in the kitchen or the garden can be ambiguous, impacting the robot's usability and reliability in household tasks. Also, alothough models such as chat GPT exists that can emulate common sense to a degree, it's opaque box nature lacks the ability to explain its decisions. 


#### The Solution


<figure>
  <img src="/assets/images/robo_csk_imgs/system_diagram.png" alt="System Diagram">
  <figcaption>The Robo-CSK-Organizer addresses this challenge by integrating CSK from the ConceptNet knowledge base into the robot's decision-making process. This system leverages advanced AI technologies, including PyTorch for neural network models, DETIC for object detection, and BLIP for generating contextual understanding. By utilizing these technologies, the Robo-CSK-Organizer enhances the robot's ability to classify and organize objects accurately and explain its decisions to users.</figcaption>
</figure>


#### Results and Insights

<figure>
  <img src="/assets/images/robo_csk_imgs/consistency.png" alt="Consistency in Classification">
  <figcaption>The implementation of the Robo-CSK-Organizer resulted in significantly improved accuracy and consistency in object classification compared to traditional systems. It achieved a 90% accuracy rate in object placement and provided transparent decision-making processes, which increased user trust and satisfaction. </figcaption>
</figure>

<figure>
  <img src="/assets/images/robo_csk_imgs/Step_Diagram_RoboCSK.png" alt="Arm with Objects">
  <figcaption>The system's adaptability to various household tasks demonstrated its potential for widespread application in domestic robotics, making it a valuable advancement in the field of AI and robotics.</figcaption>
</figure>


[![](https://img.shields.io/badge/PyTorch-white?logo=PyTorch)](#) [![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter_Notebooks-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Google_Colab-white?logo=Google-Colab)](#) [![](https://img.shields.io/badge/Docker-white?logo=Docker)](#) [![](https://img.shields.io/badge/ConceptNet-white?logo=ConceptNet)](#) [![](https://img.shields.io/badge/DETIC-white?logo=DETIC)](#) [![](https://img.shields.io/badge/BLIP-white?logo=BLIP)](#) [![](https://img.shields.io/badge/ROS-white?)](#) [![](https://img.shields.io/badge/GitHub-white?)](#)

#### See Links Below For More Details Regarding this Project

[View code on Github](https://github.com/omnidox/ConceptNet)

[View Thesis](/pdf/Rafael_Hidalgo_RoboCSK_Thesis_final_submission_AV_signed_.pdf)

[View Relevant Conference Paper](/pdf/IEMTRONICS_2024_HidalgoEtAl.pdf)

[View Thesis](/pdf/Rafael_Hidalgo_RoboCSK_Thesis_final_submission_AV_signed_.pdf)

View Demonstration Below
<iframe width="560" height="315" src="https://www.youtube.com/embed/zJRYibVJDAM?si=Uoecs9cZA-viEe20" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


---

### Personalizing Text-to-Image Diffusion Models by Fine-Tuning Classification for AI Applications

---

#### The Problem
Traditional text-to-image models, like Stable Diffusion, are limited by their pre-trained datasets, which restrict their ability to generate diverse images beyond the provided data. This limitation hinders applications such as personalized art creation, advanced human-robot interaction, and specific AI-driven tasks.

#### The Solution


<figure>
  <img src="/assets/images/stbl_dif_imgs/train_rafael.png" alt="System Diagram">
  <figcaption>To overcome these limitations, we integrated two advanced neural network models, Hypernetworks and DreamBooth, with Stable Diffusion. Hypernetworks allow us to predict and adjust weights dynamically using our own images for better image generation. </figcaption>
</figure>

<figure>
  <img src="/assets/images/stbl_dif_imgs/train_nesreen.png" alt="System Diagram">
  <figcaption> DreamBooth facilitates fine-tuning with minimal data, enabling personalized and realistic image outputs. This approach enhances the versatility of Stable Diffusion by incorporating personalized and diverse real-life perspectives.</figcaption>
</figure>

#### Results and Insights

<figure>
  <img src="/assets/images/stbl_dif_imgs/new_images.png" alt="System Diagram">
  <figcaption>The enhanced model demonstrated significant improvements in image generation quality and diversity with minimal training data. Hypernetworks produced adaptable, high-quality images with efficient resource usage, while DreamBooth achieved high-fidelity personalization but required more computational power. User satisfaction increased notably, with DreamBooth reaching 95% accuracy in generating desired images. This project showcases the potential for applications in personalized photo shoots, movie animations, and intelligent tutoring systems, making substantial impacts on AI's role in smart cities and various real-world scenarios. </figcaption>
</figure>

[![](https://img.shields.io/badge/PyTorch-white?logo=PyTorch)](#) [![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter_Notebooks-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Google_Colab-white?logo=Google-Colab)](#) [![](https://img.shields.io/badge/Stable_Diffusion-white?logo=Stable-Diffusion)](#) [![](https://img.shields.io/badge/Hypernetworks-white?logo=Hypernetworks)](#) [![](https://img.shields.io/badge/DreamBooth-white?logo=DreamBooth)](#) [![](https://img.shields.io/badge/BLIP-white?logo=BLIP)](#) [![](https://img.shields.io/badge/Gradio-white?logo=Gradio)](#) [![](https://img.shields.io/badge/GitHub-white?logo=GitHub)](#)

#### See Links Below For More Details Regarding this Project

[View Colab Code](https://github.com/omnidox/Stable-Diffusion-Fine-Tuning-Conference-Paper/blob/main/examples/dreambooth/DreamBooth_Stable_Diffusion.ipynb)

[View Conference Paper](pdf/StableDiffusionIntelliSys2023.pdf)

---


