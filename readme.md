# VitalGuide  
 
**VitalGuide** is an offline emergency assistance app using Retrieval-Augmented Generation (RAG) with the Gemma model. It provides survival guidance, first-aid tips, and multilingual support during natural disasters when connectivity is unavailable. The app serves as a lifeline, offering reliable survival guidance and emergency first-aid instructions tailored to the needs of individuals, communities, and first responders.  

At its core, VitalGuide utilizes a **Retrieval-Augmented Generation (RAG)** system powered by the **Gemma 2 model**. This combination ensures quick and accurate responses to user queries by leveraging government datasets, trusted sources, PDFs, and emergency guides.  

### Key Features:  
1. **Offline Functionality**:  
   - Operates seamlessly without internet access, making it a reliable resource during connectivity outages.  
   
2. **Survival and First-Aid Guidance**:  
   - Provides critical survival tips and first-aid instructions to tackle emergency scenarios effectively.  

3. **Multilingual Support**:  
   - Ensures accessibility for diverse populations by supporting multiple languages.  

4. **Trusted Data Sources**:  
   - Uses verified datasets and resources from trusted authorities to guarantee accuracy and reliability.  

VitalGuide bridges the gap between life-threatening emergencies and the lack of conventional communication methods. Whether you are an individual in need of immediate assistance, a community leader coordinating disaster response, or a first responder managing chaotic situations, VitalGuide equips you with lifesaving knowledge anytime, anywhere.  

---

### Technology Stack
#### Frontend
 - **Gradio**: For creating an interactive and user-friendly interface.
#### Backend
 - **Ollama**: To enable local usage of the Gemma model.
 - **Gemma-2** Model: Provides retrieval-augmented responses for survival guidance.
 - **LangChain**: Orchestrates interactions between the RAG pipeline components.
 - **ChromaDB**: Used as a vector database for storing and retrieving indexed documents.

---

### Prerequisites
**Install Ollama**
VitalGuide requires Ollama to run the Gemma model locally.

Install Ollama by following the instructions from the Ollama website.

Once installed, pull the required Gemma model by running:

    ```bash
    ollama pull gemma2:2b

    ```
This step downloads the Gemma2:2b model necessary for the app to function properly.

---

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/quaidkhalid/ViatalGuide-powered-by-Gemme-2.git  
   ```    

2. Install the dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```  

3. Run the application:  
   ```bash
   python app.py            

   ```  
4. Run the application with UI:  
```bash
python appUI.py            

   ```  

---


**Empower yourself with lifesaving knowledge—VitalGuide is here to assist, even when the world goes offline.**