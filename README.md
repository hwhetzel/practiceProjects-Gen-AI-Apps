# practiceProjects-Gen-AI-Apps
Practice/Learning Projects from the Building Generative AI-Powered Applications with Python Course in the IBM AI Developer Certification on Coursera. 

**Building Generative AI-Powered Applications with Python - Practice Projects**

Welcome to my collection of practice projects completed as part of the Building Generative AI-Powered Applications with Python course on Coursera. These projects focus on building generative AI applications using Python, with a special emphasis on using cutting-edge models and frameworks.

**About This Repository**

This repository contains a series of Python-based practice projects that I completed as part of my coursework in Building Generative AI-Powered Applications with Python on Coursera. The projects cover key concepts in generative AI, such as building models that can generate text, images, and other data types.

The projects followed a structured curriculum and were based on step-by-step tutorials, where I learned how to implement various generative models.

The projects were all made on IBM Skills Network Labs, which is a virtual lab environment. So some of these projects might not fully work unless changed.

**Course Link:**

https://www.coursera.org/learn/building-gen-ai-powered-applications

<br>
<br>

**Practice Project 1: Give Meaningful Names to Your Photos with AI**

**Description:**

In this project, I built an image captioning tool using the BLIP model (Bootstrapping Language-Image Pretraining) from Hugging Face’s Transformers library. The model generates captions for images by understanding both the visual content and contextual relationships within the image. I used Gradio to create a simple, user-friendly web interface that allows users to upload images and receive automatic captions.

**Learning Outcomes:**

- Learn how the BLIP model combines vision and language to generate meaningful captions for images.

- Use Hugging Face’s Transformers library to easily integrate pre-trained models into an application.

- Implement a user interface with Gradio, making it simple for non-technical users to interact with the AI model.

**Key Features:**

- Upload an image to the app.

- Automatically generate a caption describing the image.

- Interactive interface powered by Gradio for easy deployment.

**Technologies Used**

Programming Language: Python

Libraries/Frameworks:

- Hugging Face Transformers: For accessing pre-trained BLIP model.

- Gradio: For creating an interactive web interface to interact with the model.

- PIL (Python Imaging Library): For handling image processing.

- Torch: For running the deep learning model.

- NumPy: For numerical operations and data handling.

- Matplotlib: For displaying images (optional, if required for visualization).

- Requests: For making HTTP requests to fetch webpage content and images.

- BeautifulSoup: For parsing HTML content and extracting image URLs.

**A Note on the Project**

This project uses BLIP, a transformer-based model that combines vision and language understanding, to generate captions for uploaded images. It is designed to show how generative AI models can be applied to real-world tasks like image captioning.
The application is built using Gradio, a powerful library that simplifies the process of creating interactive, user-friendly web interfaces for AI models. This project serves as a practical example of how AI can be deployed and made accessible to end-users.

<br>

**Practice Project 2: Build Your Own Chatbot Web App with GPT-3.5**

**Description:**

In this project, I built an AI-powered chatbot web application using OpenAI’s GPT-3.5 model integrated with Streamlit. The app allows users to interact with a generative AI model in a conversational format. By leveraging the OpenAI API, the chatbot generates intelligent and context-aware responses to user input. Streamlit provides a lightweight and intuitive web interface that makes the application both functional and easy to use.

**Learning Outcomes:**

- Understand how large language models like GPT-3.5 can be used to build conversational AI applications.

- Learn how to interact with the OpenAI API to send prompts and receive generated responses.

- Use Streamlit to design and deploy an interactive chatbot interface accessible through the browser.

**Key Features:**

-User input field to enter text queries.

- Automatically generates responses using GPT-3.5 based on the conversation history.

- Simple and interactive web UI using Streamlit for easy deployment and use.

- Maintains conversational memory to keep the chat coherent.

**Technologies Used**

Programming Language: Python

Libraries/Frameworks:

- OpenAI: To access and use the GPT-3.5 language model.

- Streamlit: For creating an interactive and real-time web-based chatbot interface.

- Python Built-in Libraries: For handling API keys, storing session state, and formatting responses.

**A Note on the Project**

This project demonstrates how to integrate a powerful language model into a real-time web interface, enabling users to engage with AI in a familiar chat-based format. It showcases the accessibility of generative AI technologies when paired with user-friendly frameworks like Streamlit. The chatbot is designed for quick prototyping and can be extended for use cases like customer support, virtual assistants, or educational tools. This project is a hands-on example of how conversational AI can be brought from concept to deployment with minimal overhead.

<br>

**Practice Project 3: Business AI Meeting Companion STT**

**Description**

In this project, I developed an AI-powered meeting assistant that transcribes business meeting conversations and summarizes them into concise, actionable key points. The application uses OpenAI's Whisper model to convert speech to text, and IBM Watson’s Natural Language Understanding (NLU) to generate summaries and extract critical insights. The user interacts with the system through an intuitive Gradio web interface, enabling a seamless voice-to-summary experience.

**Learning Outcomes**

- Understand how to use OpenAI Whisper to transcribe audio into accurate text.

- Apply IBM Watson's NLU to summarize transcribed text and extract key decision points.

- Integrate multiple AI services into a cohesive voice processing application.

- Design an interactive web interface with Hugging Face Gradio for end-user access.

- Set up and manage a Python virtual environment for multi-library AI development.

**Key Features**

- Upload an audio file from a meeting.

- Transcribe speech to text using OpenAI Whisper.

- Summarize the transcription and extract key decisions using IBM Watson NLU.

- Display results in a clean, browser-based Gradio interface.

- Modular and customizable architecture for educational or enterprise use.

**Technologies Used**

Programming Language: Python

Libraries/Frameworks:

- OpenAI Whisper – For high-accuracy speech-to-text conversion.

- IBM Watson Natural Language Understanding (NLU) – For summarization and extracting key topics.

- Gradio – To create the user-friendly web interface.

- Transformers (Hugging Face) – To load and manage pre-trained models.

- Torch – Backend for running Whisper.

- LangChain – To structure and streamline interactions between components.

- huggingface-hub – For connecting to models hosted on Hugging Face.


**A Note on the Project**

This project demonstrates how AI can enhance productivity by turning long, unstructured spoken content into focused, actionable summaries. The application showcases how powerful generative models like Whisper and NLU can be orchestrated into real-world workflows with just a few libraries and tools. Designed for simplicity and adaptability, this project serves as an excellent introduction to combining speech and language AI in practical applications.

<br>

**Practice Project 4: Chatbot for Your Data**

**Description**

In this project, I built a private chatbot application that summarizes and answers questions about the content of PDF documents using generative AI. The app uses Meta’s open-access Llama 2 language model in combination with Retrieval-Augmented Generation (RAG) to process private data securely and provide accurate, context-aware answers. The backend is powered by Flask and LangChain, and the app interface allows users to upload a PDF and chat with an AI assistant that reads and understands the document.

This solution is designed to help users extract valuable insights from large and potentially sensitive documents without sending their data to public cloud-based models. It is especially useful for professionals handling confidential reports, researchers analyzing long papers, or anyone who needs to quickly understand complex documents.

**Learning Outcomes**

- Explain how LLMs and generative AI can help to summarize and understand data.

- Explain the basics of LangChain and AI applications.

- Set up a development environment for building an assistant using Python Flask.

- Implement PDF upload functionality to allow the assistant to comprehend file input from users.

- Implement Llama 2 and RAG for extracting data from large texts.

- Integrate the assistant with open source models to give it a high level of intelligence and the ability to understand and respond to user requests.

- Demonstrate web application development using Flask and Python.

- Apply the LangChain framework to interpret and respond to user inputs effectively.

**Key Features**

- Upload a PDF document to the application.

- Automatically parse and summarize the document contents using Llama 2 with RAG.

- Ask custom questions to a chatbot about the content of the PDF.

- Receive detailed, context-aware answers generated by the LLM.

- Full-stack solution using open-source technologies for private deployment.

**Technologies Used**

Programming Language: Python

Libraries/Frameworks:

- Meta Llama 2: Open-access large language model for natural language understanding and generation.

- LangChain: Framework for building applications with LLMs, specifically for managing document parsing, vector storage, and AI pipelines.

- Flask: Lightweight Python web framework for backend development.

- PyPDF2 / pdfplumber: For extracting text from PDFs.

- FAISS: For efficient vector search in the RAG pipeline.

- Hugging Face Transformers: For LLM integration.

- Gradio (optional UI component): For building simple web-based interfaces.

- Other Libraries: os, dotenv, re, json, uuid, etc.

**A Note on the Project**

This project illustrates the power of LLMs like Llama 2 when combined with private deployment and RAG techniques. Instead of exposing sensitive data to public APIs, the chatbot is run locally, ensuring that all document content remains secure. The integration of Flask and LangChain demonstrates a practical way to build real-world AI tools that bridge natural language understanding with interactive applications. This project serves as a template for building data-aware assistants that are customizable, secure, and easy to deploy in professional environments.



<br>



**Practice Project 5:**

**Description**



**Learning Outcomes**

- 

**Key Features**

- 

**Technologies Used**

Programming Language: Python

Libraries/Frameworks:

- 


**A Note on the Project**



<br>

**Practice Project 6:**

**Description**



**Learning Outcomes**

- 

**Key Features**

- 

**Technologies Used**

Programming Language: Python

Libraries/Frameworks:

- 


**A Note on the Project**
