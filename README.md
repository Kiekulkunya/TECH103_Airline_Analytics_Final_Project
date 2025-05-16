🛫 🤖 TECH 103 - Final Project Submission “ Next-Gen AI Airline Semantic Search Intelligence and Agentic AI Weather Alert Assistance Prototype (Beta)”
Summary:

[https://furry-pizza-7fa.notion.site/TECH-103-Final-Project-Submission-Next-Gen-AI-Airline-Semantic-Search-Intelligence-and-Agentic-A-1f5111afefc18008b04ef9db0e54b8f1?pvs=73](https://furry-pizza-7fa.notion.site/TECH-103-Final-Project-Submission-Next-Gen-AI-Airline-Semantic-Search-Intelligence-and-Agentic-A-1f5111afefc18008b04ef9db0e54b8f1)

https://colab.research.google.com/drive/1vi0s1py6sztmVOsv8XClpwxwQa7vBUHA?usp=sharing

### About project

Solo Final Project by Kiris (Kulkunya) Prayarach

**Project Name: “Next-Gen AI Airline Search & Agentic Weather Alert System Prototype** (Beta version)” *

*Since Miami Search engines prototype 1.0, 2.0 and 3.0 had been launched and submitted for work assignment previously.   

**Business Intuitions:**

“In the post-COVID-19 era, the competitive edge across all sectors—including the airline industry—has shifted toward the power of information, reviews, and customer ratings rather than relying solely on physical service delivery. Early adoption of innovative and automated search tools helps close critical information gaps and enables cheaper, faster, and more efficient communication with customers.

AI-powered airline search solutions, capable of processing both structured and unstructured data at scale, present a compelling opportunity to build intelligent tools using advanced AI techniques. These tools not only streamline information discovery but also enhance the overall customer experience.

Furthermore, the integration of mini Agentic AI for real-time weather forecasting and automated alerts via email transcends traditional services. This innovation addresses complex challenges in travel management and provides timely, mission-critical information to support customers in making informed decisions during emergencies or high-stakes travel scenarios.” (70%Human, 30% AI) 

**AI Work Objectives:** 

**I. Development of Adaptive Airline Semantic Search Engine**

- Designed and launched an innovative airline search engine from the ground up using a basic RAG framework integrated with LLMs.
- Scaled the solution to incorporate advanced RAG techniques with chunking and API integration for high-performance semantic search.
- Implemented the system on a user-friendly Gradio interface to enable real-time search and retrieval capabilities for flight-related queries.

**II. Deployment of Agentic AI for Proactive Weather Alerts**

- Developed and deployed a mini Agentic AI system capable of automatically sending real-time weather alerts to passengers scheduled to fly to high-rainfall airport cities.
- The system provides early notifications advising travelers to arrive ahead of time, helping to mitigate the impact of severe weather, road congestion, and potential flight delays or cancellations.

**Databases: Github, ChatGPT Research, Kaggle**

### **Outcomes:**

- Successfully developed an **AI-powered Airline Semantic Search Engine** using LLM-based RAG architecture combined with API integration, enabling intelligent and context-aware airline information retrieval.
- Deployed a **Mini Agentic AI System** that proactively sends weather alerts via email to passengers flying to high-risk, heavy-rain cities—improving travel safety, reducing uncertainty, and enhancing overall customer experience.

**Integrating AI: Mind Map Conceptual Framework & Workflow Process:**

https://preview-d57e6b4d--concise-mind-canvas.lovable.app/

![Mindmap ai.png](attachment:b5bba3cc-b901-4986-a358-ecbda91bb277:Mindmap_ai.png)

**Workflow Summary:** 

```
*   i.  Uploaded data from raw Github with easily maintainance for back-end process 
*   ii. Initiated Innovative Features namely Distance (latitude,longitude) for creating Flight types (Short, Medium, Long), Departure, Destination and combined databased together
*   iii. Data Preparation & EDA : cleaning, handling missing data, dtype correction, font errors. 
*   iv.  Run GPU vs. CPU for exploring performance 
*   v.   Build RAG, embedding and lauched RAG Search for Airline
*   vi.  Scale up Work process by leveraing advanced AI Search Techniques by exploring API, openAI, Chunking, Qdrant, CLI and executed Search 
*   vii. Adopting Gradio Interface and Launched Airline Search Intellligence

```

```jsx
Mini Agentic AI
*   i.   Orchastra  Weather Forecast with Airline big data. Using weather ai for automation and efficiency to predict weather condition by assigning heavy rain, sunny, or cloudly, or strom obtained from weather forecast API
*   ii.  Executed n&n Agentic AI with combinations nodes (google sheet, IF, Filter, AI Agent, openai, Gmail)
*   iii. Validate automation for ensuring everything works well by creating google sheet to check how many emails sent out to customers and correctly

```

Results: 

Weather API Forecast automation 

![Weatherai_Forecast.png](attachment:272f4409-8dab-4361-8192-c95ffd5016a9:Weatherai_Forecast.png)

Basic Data cleaning by Missingno

![Data Cleaning.png](attachment:a8941b4f-5538-4383-8a79-21b060d38d58:Data_Cleaning.png)

Executed GPU with impressive less time consuming (40.4s). 

![GPU time 2.png](attachment:d4a66710-a4e2-44cd-9da2-59fd61ad727a:GPU_time_2.png)

Executed CPU with waiting long long times (196s)  longer time than GPU by 4.9 times

![CPU.png](attachment:c9d0cd4d-116b-4874-a4e5-cd3f2623e50c:CPU.png)

Folium Visualization & Storytelling

![Folium.png](attachment:f378c6e2-5179-40ad-b042-e4652b9d87b1:Folium.png)

Implemented Advanced Interactive Queries and response for RAG Airline Search

[Interface Search.mp4](attachment:681eefd3-2ad7-4a67-af57-001b169bca8e:Interface_Search.mp4)

[Interface3.mp4](attachment:2ea689e4-0ae9-4021-9f02-c8bbcd85df99:Interface3.mp4)

 Gradio Interface Airline Search

[Gradio2.mp4](attachment:3390cdc3-5614-420e-9c2e-e4644a515958:Gradio2.mp4)

Agentic AI for Weather Forecasting and Send Alert Email

[Agentic AI send email.mp4](attachment:7b52739e-8186-4e23-9a8d-bfc918463e2a:Agentic_AI_send_email.mp4)

**Addressing Ethical and Hallucination**

Ask AI Search to respond using metadata and content from chunking of text only!!!

![Clear Queries for best results.png](attachment:956f3ab9-07db-4f1e-9106-1c384856fc3b:Clear_Queries_for_best_results.png)

**Another clear queries to Agentic AI for data privacy by avoiding sending email to general public who are irrelevant or create miss understanding messages to make up panic situation.**

STEPS

1. Retrieve Weather Condition and Airline information
2. combine weather Condition with Airline information
3. Analyze those information
4. Create the weather forecasting alert message to who will travel on May 18,2025 and alert customers about weather condition that might cause heavy road traffic, flight delay, or flight cancellation
5. Send the message via Send_Mail

If the customers are the post-covid reviews, greeting them and make a good word for making customers have a pleasant flight and send the email.

If the Customers are not post_covid_review who post reviews before Covid-19, create greeting words and wish them back to normal life on their travelling and wish them enjoy the flight services and send the email.

TOOLS

Send_Mail: this too allows sending emails.

CONSTRAINS

You must send email about weather to customers who will depart from the Heavy Rain City and Alert.

The output format of the email must be in plain text and emoji of rainy and airplane on subject and email.

**The good prompts come out with the quality outcomes. This shows we address ethical and moral concerns in avoiding text auto generation that makes people in panic by making up story due to unclear commands or prompts by Human or AI or both of them.**

![Clear message.png](attachment:b3084186-6e45-4c4c-8dbb-f4ea2b615bff:Clear_message.png)

**Data Reference:**

```
 https://www.kaggle.com/datasets/juhibhojani/airline-reviews
 
```

 **Data Airline Source:**

```
 [https://raw.githubusercontent.com/danielkellen6/MABA6490-Assignment2/refs/heads/main/hotelReviewsInMiami__en2019100120191005.csvhttps://raw.githubusercontent.com/danielkellen6/MABA6490-Assignment2/refs/heads/main/hotelReviewsInMiami__en2019100120191005.csv](https://raw.githubusercontent.com/Kiekulkunya/TECH103_Airline_Analytics_Final_Project/main/Airline%20Operational%20Scope%20Classification.pdf)
```

**Raw Github data**

```
https://raw.githubusercontent.com/Kiekulkunya/TECH103_Airline_Analytics_Final_Project/refs/heads/main/Airline_review.csv
```

**Data Airport, Latitude, Longitude**

https://github.com/Kiekulkunya/TECH103_Airline_Analytics_Final_Project/blob/main/Airline%20Operational%20Scope%20Classification.pdf

```
[https://raw.githubusercontent.com/danielkellen6/MABA6490-Assignment2/refs/heads/main/hotelReviewsInMiami__en2019100120191005.csv](https://raw.githubusercontent.com/Kiekulkunya/TECH103_Airline_Analytics_Final_Project/main/Airline%20Operational%20Scope%20Classification.pdf)
```

### Google Colab Shared Codes:

```
https://colab.research.google.com/drive/1vi0s1py6sztmVOsv8XClpwxwQa7vBUHA?usp=sharing
```

### Github:

https://github.com/Kiekulkunya/TECH103_Airline_Analytics_Final_Project

### Jupyter Files:
