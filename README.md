# Shooting-Sports-Mastermind

🤖 [Access Chatbot Here](https://shooting-chatbot-73f9e9488409.herokuapp.com/) 🤖

# Motivation

As a rifle shooter, the world of shooting sports is close to my heart 💟. <br>

While practicing, I often had to deal with the complicated rules and regulations of our sport. These rules cover aspects such as weapon weight, clothing thickness standards, maximum sling width, shoe sole flexibility, and many more, all of which are potential reasons for disqualification. Navigating through multiple handbooks and resources to find accurate information was not only time-consuming but also challenging. <br>

Recognizing this need, I started working on a RAG-based chatbot a few weeks ago to streamline this process! I gathered comprehensive shooting-related handbooks, including those from the ISSF - International Shooting Sport Federation, and developed a chatbot to provide quick and accurate responses about shooting rules and regulations for both shooters and juries.<br>

<div style="display: flex; justify-content: space-between;">
  <img src="Images/i1.webp" alt="Image 1" width="400"/>     
  <img src="Images/i2.jpeg" alt="Image 2" width="400"/>
</div>


## Tech Stack

* 𝗣𝗿𝗼𝗺𝗽𝘁 𝗥𝗲𝘀𝗽𝗼𝗻𝘀𝗲𝘀: GPT-4.0 Mini
* 𝗧𝗲𝘅𝘁 𝗘𝗺𝗯𝗲𝗱𝗱𝗶𝗻𝗴: GTE-base
* 𝗩𝗲𝗰𝘁𝗼𝗿 𝗗𝗕: Pinecone
* 𝗖𝗜/𝗖𝗗: GitHub Actions
* 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁: Heroku

## Data Sources
The knowledge base is built using shooting-related PDFs collected from various online and offline sources. The PDF content includes, but is not limited to:
 <br>
- Weapon setup guidelines (Rifle/Pistol/Shotgun)<br>
- Safety protocols <br>
- Measurement rules <br>
- Anti-doping Rules
- Disqualification rules <br>


## Installation & Setup
**1. Clone the Repository:** <br>

```bash
git clone https://github.com/pragatinaikare/RAG_BASED_CHATBOT.gi
```

**2. Install Dependencies:**

```bash
pip install -r requirements.txt
```

**3. Set Up API Keys:** 
You will need to create accounts with Pinecone and OpenAI to get your API keys. Add these keys in keys.txt file inside Docs Folder

**4.** 
```bash
pip install -r requirements.txt
```

## References
1] [Searching for Best Practices in Retrieval-Augmented Generation](https://arxiv.org/abs/2407.01219)<br>
2] [Context Embeddings for Efficient Answer Generation in RAG](https://arxiv.org/abs/2407.09252)<br>
3] [RAGAS: Automated Evaluation of Retrieval-Augmented Generation](https://arxiv.org/abs/2309.15217)<br>

