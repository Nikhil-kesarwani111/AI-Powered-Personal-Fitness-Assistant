# AI-Powered Personal Fitness Assistant

A **GenAI-driven personal fitness assistant** that generates personalized workout, nutrition, and recovery recommendations using **LLM reasoning combined with Retrieval-Augmented Generation (RAG)** over user-specific data.

The system is designed using **Langflow for rapid LLM workflow validation** and productionized in **Python**, with contextual memory stored in **Astra DB** and an interactive **Streamlit interface**.

---

## Key Capabilities

- Personalized recommendations based on **injuries, fitness goals, activity level, and equipment availability**
- Context-aware responses using **RAG over user profiles and personal notes**
- Multi-path LLM workflows validated in Langflow and converted to Python
- Real-time interaction through a structured Streamlit UI
- Modular, production-oriented codebase

---

## System Overview

**High-level flow:**

<img width="470" height="659" alt="image" src="https://github.com/user-attachments/assets/27c2ed14-2e20-4c44-ba85-1c949407eeef" />

---

## LLM Workflow Design

The assistant supports **three distinct reasoning paths**:

1. **Profile-based fitness guidance**  
   Generates workout and recovery plans aligned with user constraints.

2. **Nutrition recommendations**  
   Produces goal-oriented dietary guidance.

3. **Free-form fitness queries**  
   Handles open-ended user questions with contextual memory.

Workflows were first **designed and validated in Langflow**, then implemented as **maintainable Python modules** for production use.

---

## Retrieval-Augmented Generation (RAG)

- **Vector Database:** Astra DB  
- **Context Sources:**
  - Structured user profile data
  - Unstructured personal fitness notes

This enables memory-aware, personalized responses instead of stateless LLM outputs.

---

## Tech Stack

- **Language:** Python  
- **LLM Orchestration:** Langflow, LangChain  
- **Vector Database:** Astra DB  
- **Frontend:** Streamlit  

---



## Project Structure
<img width="433" height="502" alt="image" src="https://github.com/user-attachments/assets/90c516ae-80c6-4f60-8c54-7c459cee5f90" />

## Project: 
<p align="center">
  <img src="https://github.com/user-attachments/assets/24ca2e3c-bf50-4d86-9e9d-37410532616d" width="48%" />
  <img src="https://github.com/user-attachments/assets/609ea9de-7230-4302-8b13-caca0821ac9f" width="48%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/dd69c1bc-73dc-407a-af0e-c3b9c73e9d84" width="48%" />
  <img src="https://github.com/user-attachments/assets/bedb5d11-70f3-40d2-853f-91e12859e7e2" width="48%" />
</p>


---

## Local Setup

```bash
git clone https://github.com/Nikhil-kesarwani111/AI-Powered-Personal-Fitness-Assistant.git
cd AI-Powered-Personal-Fitness-Assistant
python -m venv env
source env/bin/activate   # Windows: env\Scripts\activate
pip install -r requirements.txt
streamlit run main.py


