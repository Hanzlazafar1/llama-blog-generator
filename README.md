#   AI Blog Generator using LLaMA 2 and Streamlit

This is a simple Streamlit web app that generates blogs using the LLaMA 2 model based on the provided topic, word count, and target audience.

##   Features

- Generate blogs by just entering a topic
- Choose desired blog length (number of words)
- Select your target audience:
  - Researchers
  - Data Scientists
  - Common People

##  Model Used

- **LLaMA 2 (7B)** running locally via `CTransformers`
- Model File: `llama-2-7b-chat.ggmlv3.q8_0.bin`

##   Tech Stack

- Python
- Streamlit
- LangChain
- CTransformers

##   How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-blog-generator.git
   cd ai-blog-generator
