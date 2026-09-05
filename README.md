# ✍️ Text Generation using AI

An AI-powered **text generation application built with Python, Streamlit, and Hugging Face Transformers** as part of the Generative AI task.

The application allows users to enter a natural-language prompt and generate AI-based text using the **DistilGPT-2** pre-trained language model.

> **Idea → Prompt → Generative AI → Working AI Application**

---

## 📌 Overview

**Text Generation using AI** is an interactive web application that generates text based on a user-provided prompt.

The application provides a simple interface where users can:

* Enter a text prompt
* Adjust the maximum generated text length
* Control the randomness of generation using temperature
* Generate AI-based text
* View the generated result directly in the application

The application was developed with the assistance of **Generative AI**, which was used to generate the application code from a natural-language description of the required functionality and user experience.

The generated application was then run and tested to verify its functionality.

---

## 🤖 Generative AI Creation

The application was created with the assistance of **Generative AI** through a prompt-based development approach.

A natural-language prompt was provided describing:

* The required application
* User interface
* Text-generation functionality
* Generation controls
* AI model integration
* Expected user interaction

Generative AI generated the application code based on these requirements.

The generated code was then run using **Streamlit** and tested with different prompts and generation settings.

This demonstrates how Generative AI can assist in transforming a natural-language idea into a functional AI-powered application.

---

## ✨ Features

* ✍️ AI-powered text generation
* 💬 Natural-language prompt input
* 📏 Adjustable maximum text length
* 🌡️ Adjustable temperature
* ⚡ Real-time text generation
* 🤖 DistilGPT-2 pre-trained language model
* 🖥️ Simple and interactive interface
* 🔄 Supports different text-generation prompts
* 🌐 Streamlit-based web application
* 📝 Displays generated text directly in the interface

---

## 🧠 How It Works

The application follows a simple AI text-generation pipeline:

```text
        User Prompt
             ↓
    Streamlit Application
             ↓
   Hugging Face Transformers
             ↓
        DistilGPT-2
             ↓
     AI Text Generation
             ↓
      Generated Text
             ↓
      Display to User
```

### 🔍 Process Explanation

**1. User Input**

The user enters a natural-language prompt into the application.

**2. Generation Settings**

The user can adjust:

* Maximum length
* Temperature

**3. Model Processing**

The prompt is passed to the **DistilGPT-2** language model through the Hugging Face Transformers library.

**4. Text Generation**

DistilGPT-2 predicts and generates text based on the provided prompt and selected generation settings.

**5. Output**

The generated text is displayed to the user through the Streamlit interface.

---

## 🛠️ Tools & Technologies Used

| Tool / Technology             | Purpose                                             |
| ----------------------------- | --------------------------------------------------- |
| **Python**                    | Application logic and implementation                |
| **Streamlit**                 | Interactive web application interface               |
| **Hugging Face Transformers** | Provides the text-generation pipeline               |
| **DistilGPT-2**               | Pre-trained language model used for text generation |
| **Generative AI**             | Assisted in generating the application code         |
| **Web Browser**               | Running and testing the application                 |
| **GitHub**                    | Project repository and documentation                |

---

## 🤖 AI Model — DistilGPT-2

The application uses **DistilGPT-2**, a smaller and faster version of GPT-2 designed for text-generation tasks.

The model receives the user's prompt and generates continuation text based on patterns learned during its training.

The model is accessed through the **Hugging Face Transformers** library.

```text
User Prompt
     ↓
DistilGPT-2
     ↓
Predicted Text
     ↓
Generated Output
```

---

## ⚙️ Text Generation Controls

The application provides controls that allow users to customize the generated output.

### 📏 Maximum Length

The **Maximum Length** slider controls the maximum number of tokens that can be generated.

The application provides:

| Setting | Value |
| ------- | ----: |
| Minimum |    30 |
| Maximum |   200 |
| Default |   100 |

A higher value allows the model to generate a longer response.

---

### 🌡️ Temperature

The **Temperature** slider controls the randomness of the generated text.

The application provides:

| Setting | Value |
| ------- | ----: |
| Minimum |   0.1 |
| Maximum |   1.5 |
| Default |   0.7 |

A lower temperature generally produces more predictable text, while a higher temperature can produce more varied outputs.

---

## 💡 Prompt-Based Development

The development process followed these steps:

### 1. 💭 Idea

An idea for an AI-powered Text Generation application was identified.

### 2. 📝 Prompt Creation

A natural-language prompt was created describing the required functionality, interface, and user experience.

### 3. 🤖 Generative AI

The prompt was provided to a Generative AI tool.

### 4. 💻 Code Generation

The Generative AI tool generated the application code.

### 5. ▶️ Application Execution

The generated application was run using Streamlit.

### 6. 🧪 Testing

The application was tested using different prompts and generation settings.

---

## 🔄 Development Workflow

```text
       💭 Application Idea
              ↓
     📝 Natural-Language Prompt
              ↓
        🤖 Generative AI
              ↓
        💻 Generated Code
              ↓
       🐍 Python Application
              ↓
       🌐 Streamlit Interface
              ↓
        🤖 DistilGPT-2
              ↓
         🧪 Testing
              ↓
     ✍️ Generated Text
```

---

## 🎮 How to Use

### Step 1 — Start the Application

Run the Streamlit application.

```bash
streamlit run app.py
```

> Replace `app.py` with the actual Python filename if your file has a different name.

### Step 2 — Enter a Prompt

Enter a text prompt in the application.

For example:

```text
Artificial Intelligence is changing the world because
```

### Step 3 — Adjust Maximum Length

Use the **Maximum Length** slider to select the desired generation length.

### Step 4 — Adjust Temperature

Use the **Temperature** slider to control the randomness of the generated text.

### Step 5 — Generate Text

Click the **Generate Text** button.

### Step 6 — View the Result

The generated text will be displayed under the **Generated Text** section.

---

## 💻 Installation

### 1. Clone the Repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

### 2. Navigate to the Project Folder

```bash
cd Text_Generation_using_AI
```

### 3. Install Required Libraries

```bash
pip install streamlit transformers torch
```

### 4. Run the Application

```bash
streamlit run app.py
```

The Streamlit application will open in the browser.

---

## 📦 Requirements

The main Python libraries required for the application are:

```text
streamlit
transformers
torch
```

You can also create a `requirements.txt` file containing:

```text
streamlit
transformers
torch
```

Then install the dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🧪 Testing

The application was tested to verify that the main functionality works correctly.

The following features were checked:

* ✅ Application opens successfully
* ✅ Streamlit interface loads correctly
* ✅ User can enter a prompt
* ✅ Empty prompt validation works correctly
* ✅ Maximum Length can be adjusted
* ✅ Temperature can be adjusted
* ✅ Text generation works successfully
* ✅ DistilGPT-2 generates text
* ✅ Generated text is displayed
* ✅ Different prompts can be processed
* ✅ Application responds to user interaction

---

## 📊 Application Details

| Feature                   | Details                   |
| ------------------------- | ------------------------- |
| ✍️ Application Type       | AI Text Generator         |
| 🤖 AI Model               | DistilGPT-2               |
| 🖥️ Framework             | Streamlit                 |
| 🐍 Programming Language   | Python                    |
| 📚 AI Library             | Hugging Face Transformers |
| 💬 Input                  | Natural-Language Prompt   |
| 📏 Maximum Length         | 30–200                    |
| 📌 Default Maximum Length | 100                       |
| 🌡️ Temperature           | 0.1–1.5                   |
| 📌 Default Temperature    | 0.7                       |
| 🌐 Platform               | Web Application           |

---

## 🎯 Project Objective

The main objective of this project is to demonstrate the practical use of **Generative AI and pre-trained language models for text generation**.

The project combines:

* Natural-language prompting
* Generative AI-assisted development
* Python programming
* Streamlit application development
* Hugging Face Transformers
* Pre-trained language models

It demonstrates how a language model can be integrated into an interactive application where users can generate text based on their own prompts.

---

## 🌟 Key Learning

Through this project, the following concepts were explored:

* 🤖 Generative AI
* 🧠 Large language models
* ✍️ Text generation
* 📝 Prompt-based interaction
* 🐍 Python application development
* 🌐 Streamlit
* 🤗 Hugging Face Transformers
* 🔤 Pre-trained language models
* 🌡️ Temperature-based generation control
* 📏 Generation length control
* 🧪 Testing AI-generated applications

---

## 💭 Generative AI Development Concept

Traditional application development can follow:

```text
Idea
 ↓
Requirements
 ↓
Manual Coding
 ↓
Testing
 ↓
Application
```

This project demonstrates an AI-assisted development workflow:

```text
Idea
 ↓
Natural-Language Prompt
 ↓
Generative AI
 ↓
Generated Code
 ↓
Run Application
 ↓
Testing
 ↓
Working AI Application
```

This approach demonstrates how Generative AI can accelerate the initial development and prototyping of applications.

---

## 🚀 Project Outcome

The **Text Generation using AI** application was successfully created and tested as a functional AI-powered web application.

The project demonstrates how a pre-trained language model such as **DistilGPT-2** can be integrated into a Streamlit interface to generate text from user-provided prompts.

It also demonstrates how **Generative AI can assist in transforming a natural-language application description into working Python application code**.

---

## 👤 Task Information

| Category                 | Details                         |
| ------------------------ | ------------------------------- |
| **Task**                 | Generative AI – Text Generation |
| **Application**          | Text Generation using AI        |
| **AI Model**             | DistilGPT-2                     |
| **Framework**            | Streamlit                       |
| **Programming Language** | Python                          |
| **AI Library**           | Hugging Face Transformers       |
| **Development Approach** | Prompt-Based Development        |
| **Application Type**     | AI-Powered Web Application      |

---

## ⭐ Key Highlight

```text
       💡 IDEA
          ↓
       📝 PROMPT
          ↓
    🤖 GENERATIVE AI
          ↓
     💻 GENERATED CODE
          ↓
       🐍 PYTHON
          ↓
      🌐 STREAMLIT
          ↓
     🤖 DISTILGPT-2
          ↓
    ✍️ GENERATED TEXT
```

> **Idea → Natural-Language Prompt → Generative AI → Working Text Generation Application**

---

## 📌 Conclusion

**Text Generation using AI** demonstrates the practical application of Generative AI, Python, Streamlit, and pre-trained language models.

By combining **prompt-based development** with the **DistilGPT-2** model, the project provides an interactive environment where users can experiment with AI-based text generation.

The project highlights how Generative AI can assist developers in rapidly prototyping functional applications while also demonstrating the integration of modern AI models into user-friendly interfaces.

---

✍️ **Prompt. Generate. Explore.**
