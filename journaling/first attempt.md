# AI Learning Journey - 22/03/2025

## Introduction

Before diving into my journaling, I want to set some background. My IT experience is entirely based on developing corporate systems. I started coding at 14 or 15 years old, went through multiple courses, earned a graduation and postgraduate degree, and gained a lot of work experience. Now, with 10 years of experience in coding and software development, I have 0% knowledge about AI.

I ventured into the AI world after coming up with an idea for my MBA final project. And now, here is my first attempt at exploring AI:

## Defining the Problem

### 22/03/2025

After reflecting on my project, I defined my MVP and designed some architectural sketches. Now, I have encountered my first problem: how can I generate a blueprint from user prompts and return the output effectively?

Initially, I thought about using an AI API and offloading the AI-related challenges to an external service while simply managing the results. However, I quickly faced my second problem: the costs. In Brazil, using AI APIs is nearly impossible just for experimentation or proof of concept due to their high pricing.

After some research into open-source AI, I discovered the OLLAMA project on GitHub. After further reading and testing, I was amazed by the ability to run a model locally on my machine. However, after multiple prompts, I realized that OLLAMA might not be the best option for my problem.

So, I decided to use OLLAMA to help me understand the topics I need to study to develop my MVP. After explaining more about my project, I received the following structured feedback:

## Key Steps for the AI-Driven Floor Plan Generator

To create an app that generates floor plans based on user input, we need to break the process down into several steps:

### Core Development Areas
1. **AI Model Development**: Building an AI model that understands natural language inputs and generates floor plan designs accordingly.
2. **Data Collection**: Gathering a large dataset of existing floor plans for training. This can include publicly available architectural images, 3D models, or user-submitted designs.
3. **Prompt Processing**: Developing a system to interpret user prompts like "Make a floor plan for a house with two bedrooms."
4. **Design Generation**: Using the processed prompt to generate a floor plan that meets user requirements.

### Possible Technologies & Tools

#### Natural Language Processing (NLP)
- **NLTK (Natural Language Toolkit)**: For text processing and analysis.
- **spaCy**: A modern NLP library optimized for performance and usability.

#### Computer Vision
- **OpenCV**: A robust library for computer vision tasks.
- **Pillow**: A Python imaging library for image processing.

#### AI Frameworks for Model Training
- **TensorFlow**: Google's open-source machine learning framework.
- **PyTorch**: Facebook's open-source deep learning framework.
- **Keras**: A high-level neural networks API for easy model building.

#### Generative Models
- **Generative Adversarial Networks (GANs)** and **Variational Autoencoders (VAEs)** to generate unique floor plan designs.
- **TensorFlow-GAN** and **PyTorch-GAN**: Frameworks to develop generative AI models.

### App Flow Overview
1. **User Input**: The user describes their floor plan requirements.
2. **NLP Processing**: The system processes the input and extracts design details.
3. **Data Retrieval**: The app fetches relevant floor plan references from the dataset.
4. **Design Generation**: The AI model creates a custom floor plan.
5. **Visualization**: The generated design is displayed with 3D rendering or other visualization tools.

### Next Steps
1. Develop an NLP pipeline using **NLTK** or **spaCy** to process user inputs.
2. Create a dataset of floor plans for AI training.
3. Build a generative model using **TensorFlow-GAN** or **PyTorch-GAN**.

## Conclusion

At this stage, I am not yet close to my MVP. In fact, I have more questions than answers. However, I now have a structured guide to follow. This journey into AI has already shown me how complex but exciting this field is.

## Additional Thoughts

Beyond this project, I also have other ideas for using OLLAMA. For example, developing an **Azure DevOps extension for code review**. The key difference would be that it runs within a local infrastructure instead of the cloud, ensuring that the code remains private and is not exposed to third-party services.

This journey is just beginning, and I am excited to see where it takes me next!
