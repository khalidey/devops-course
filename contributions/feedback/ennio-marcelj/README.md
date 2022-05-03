# Feedback for Leveraging Kubernetes for Machine Learning with Kubeflow

The essay has a very interesting and practical subject for ML practitioners as Docker, Kubernetes and Kubeflow are highly demanded technologies in the Machine Learning field due to addressing some of the big challenges when it comes to developing and deploying ML systems.

## High level strengths and weaknesses of the Essay

### Strengths

- Thorough introduction and explanation of the main technologies (Docker, Kubernetes and Kubeflow)
- Very well structured and has a great flow as the sections build upon one another
- Essay is very visually appealing and professional
- Many references/resources utilized to explain the work

### Weaknesses

- Relies solely on text to explain two of the main technologies (Docker and Kubernetes)
- Few instances where some technical terms used should have been explained

## Feedback per section

### I. Introduction

The introduction does a great job in showing the complexity involved when it comes to training, developing and deploying ML systems. I especially liked figure 1, a typical ML pipeline, as it provides a great visualization to illustrate the step procedure for ML models and their design. The introduction also does a great job in outlining the main technologies to be explained in this essay (Docker, Kubernetes and Kubeflow) whilst also providing a quick explanation to each. While figure 1 does a great job to illustrate the ML pipeline, it would have been even better if the author specifically mentions which parts of the ML pipeline tend to be the most troublesome and how the explained technologies (Docker etc…) help overcome these ML pipeline blocks.

### II. Docker

Figures 2 and 3 provide nice and easy to read visualizations to show the popularity of Docker and how it is a highly sought out technology these days among many professionals. I also liked the paragraph about the history for the name ‘Docker’ and how the shipping industry was revolutionized. Finally, Docker is explained in a simple yet precise manner into what the technology actually is and a great comparison is made to virtual machines (VMs) and the benefits of using Docker over them. This is especially important as new users (to Docker technology) tend to be confused about the difference between Docker technology and VMs and so the author does a great job in explaining the differences and advantages here. In addition to explaining what Docker is, a figure to visually illustrate Docker technology (E.g the layers structure) would have been a great addition here as it would greatly help in the understanding rather than just relying on text.

### III. Kubernetes

This section nicely relates Kubernetes back to the previously explained section (Docker) and how Kubernetes builds upon Docker. A simple and easy explanation about Kubernetes as an ‘orchestrator’ is provided, but the term ’cluster-nodes’ should have been explained as some readers may not be familiar with that term. Also adding a figure(s) with the explanation would have been better to visually illustrate the technology architecture.

### IV. Kubeflow

Again, this section does a great job at relating Kubeflow back to the previous section (Kubernetes) and how this all connects to one another. A precise and detailed explanation of Kubeflow is provided whilst also explaining why Kubeflow would be a great tool for ML practitioners. Section A does well in emphasizing the portability and repeatability properties that Kubeflow provides and how they are a big benefit for ML practitioners. Section B does a good job of explaining Kubeflow’s architecture whilst also using nice figures to visually show this. The 5-step pipeline example was also a great thing to add to help illustrate Kubeflow’s functionality.

### V. Conclusion

Great summary about the main contents of the essay and important key takeaways are nicely given as a final take away message for the readers.

## Pointers to additional material

The following [article](https://towardsdatascience.com/machine-learning-pipelines-with-kubeflow-4c59ad05522) provides more thorough and detailed steps on how to automate a machine learning workflow using the Kubeflow pipelines explained in this essay.

This [article](https://thenewstack.io/kubeflow-where-machine-learning-meets-the-modern-infrastructure/) provides a nice overview and visual figures of Kubeflow and some of its use cases.
