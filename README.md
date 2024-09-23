<!--
**JelinR/JelinR** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

Hi, I'm Jelin Raphael Akkara, a Master's student in Physics of Data at the University of Padua. My interests span **Natural Language Processing, Computer Vision, and their intersection in fields like Embodied AI**. Below is a selection of projects, both major and minor, that have influenced my growth and shaped my interests. Feel free to reach out using the provided contact information.

Personal Site: [https://jelinr.github.io/](https://jelinr.github.io/)

## Major Projects

 These refer to projects that I have improved upon pre-existing models or methods using innovative approaches, often producing surprisingly good results. 

-  [Lightweight CNN for Speech Keyword Detection](https://github.com/JelinR/Speech_KWS_Lightweight): Developed a lightweight CNN model (31k parameters) to classify speech keywords with 90.27% categorical accuracy on the Google V12 Speech Commands Dataset. The model has a 39 ms average inference time and uses 90 KB memory, competing with SoTA models like TDNN (250k parameters, 94% accuracy). 

- [YOLOv8n Object Detection using Blob Enhancers](https://github.com/JelinR/ultralytics_forked): Improved YOLOv8n for small human (far away or occluded persons) detection by 1.1% by adding a pre-processing layer that enhances regions of interest (through blob detection) before fine-tuning the model. The preprocessing speed merely increased by 2 ms (from 7 ms to 9 ms).

- [Fake News Recognition with Naive Bayes](https://github.com/JelinR/Fake_News_Detection): Built an efficient text classifier in R for fake news detection using Multinomial Naive Bayes. A SQL-based approach enabled handling term-context matrices efficiently, training on 20,800 rows (average 4,544 words) in under 30 seconds.

- [Dask Distributed Analysis with Big Data](https://github.com/JelinR/big-data-anomaly-detection): Implemented anomaly detection on a large industrial dataset (~5GB) using a virtual cluster of 3 worker nodes. Efficiently utilized low-level map-reduce parallelization to process the big data. 


## Minor Projects

These refer to projects that I use to get comfortable with a concept or tool. The focus of these projects is to familiarize myself with the tool, and it is less about deriving benchmark-worthy results. 


- [Learning Kant using LLM and RAG](https://github.com/JelinR/LLM_RAG_Learning_Kant): Tested RAG's capability using Llama-2 as the chatbot LLM, FAISS as the vector store, and HuggingFace for the pipeline on four influential works of Immanuel Kant, optimizing prompts and parameters for best results.

- [Audio Generation using Variational Autoencoders](https://github.com/JelinR/VAE_Audio_Generation): Built a continuously varying latent space using VAE to generate speech keyword audio samples. This was done by optimizing the latent dimension and the encoder and decoder parameters, experimenting with assymetric structures.

- [Predicting Plasma Crashes with Transformers](https://github.com/JelinR/Plasma_Evolution_Analysis): Conducted anomaly detection (magnetic crashes) on a highly imbalanced time series dataset (plasma evolution) using three architectures: 1-D CNN, DNN, and Transformer.

- [Muon Pair Detection](https://github.com/JelinR/LCPModA-Y5-Gr6): Identified rare muon events using a signal selection strategy with linear interpolation and count thresholds on a four-layer detector, modeled after CMS drift tubes.
