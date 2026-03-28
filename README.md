
# Ex.No.3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques

### Date: 20-02-2026

### Register Number: 212223230159

---

# Aim

To write prompts for the following prompt types and evaluate them using one use case:

1. Straightforward Prompts
2. Tabular Format Prompting
3. Preceding Question Prompting
4. Missing Word Prompting

---

# Tools Required

* AI text generation system (ChatGPT, Gemini, Claude)
* MS Word / Excel (for documenting outputs)
* Internet access for live interaction testing

---

# Theory

Prompt engineering refers to designing and structuring inputs given to AI systems to achieve accurate and user‑relevant outputs. Different prompting strategies affect the **clarity, depth, and format** of chatbot responses.

## 1. Straightforward Prompting

* Simple and direct instruction
* Produces focused answers for short queries

## 2. Tabular Prompting

* AI is explicitly asked to present output in table form
* Best for structured data, comparisons, or multi‑step solutions

## 3. Preceding Question Prompting

* Builds context from previous user questions
* Enables a continuous, interactive flow of conversation

## 4. Missing Word Prompting

* Fill‑in‑the‑blank style prompting
* Encourages recall‑based learning and engagement

---

# Explanation

### Use Case Chosen: General Knowledge and Science Education

General Knowledge and Science Education refers to the broad understanding and awareness of facts, concepts, and principles across various disciplines, including science, geography, technology, environment, and current affairs. It helps in developing informed and critical‑thinking individuals.

All four prompt types are applied to this use case.

---

# Procedure

Three scenarios were tested using different prompting techniques. The responses were analyzed based on:

* Clarity
* Structure
* Engagement

---

# Scenario 1: Product Troubleshooting

| **Prompt Type**              | **Example Prompt**                                                         | **Sample Output**                                      |
| ---------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------ |
| Straightforward Prompting    | “My washing machine is not draining water. What should I do?”              | *Check drain pipe, remove blockages, restart machine.* |
| Tabular Prompting            | “List causes and fixes for a washing machine not draining water.”          | See table below.                                       |
| Preceding Question Prompting | Q1: “My washing machine won’t drain.” <br> Q2: “It makes a humming sound.” | *Motor issue suspected; service required.*             |


## Troubleshooting Table


| **Possible Cause** | **Solution**                   |
| ------------------ | ------------------------------ |
| Blocked drain pipe | Clean or unclog pipe.          |
| Faulty pump        | Replace or repair pump.        |
| Overloaded clothes | Reduce load and restart cycle. |
| Motor issue        | Contact service technician.    |

---

# Scenario 2: Order Tracking


| **Prompt Type**              | **Example Prompt**                                     | **Sample Output**                            |
| ---------------------------- | ------------------------------------------------------ | -------------------------------------------- |
| Straightforward Prompting    | “Track order #88954 placed on 30th August.”            | *Shipped, arriving 6th September.*           |
| Tabular Prompting            | “Show current status of order #88954 in table format.” | See table below.                             |
| Preceding Question Prompting | Q1: “Where is order #88954?” <br> Q2: “Is it delayed?” | *Expected to arrive on time, 6th September.* |


## Order Status Table


| **Stage**       | **Status**         | **Date**    |
| --------------- | ------------------ | ----------- |
| Order Confirmed | Successful         | 30-Aug-2025 |
| Packed          | Completed          | 31-Aug-2025 |
| Shipped         | In transit         | 02-Sep-2025 |
| Delivery        | Expected 06-Sep-25 | —           |
---

# Scenario 3: General Inquiry

| **Prompt Type**              | **Example Prompt**                                                              | **Sample Output**                                                |
| ---------------------------- | ------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Straightforward Prompting    | “What is your company’s return policy?”                                         | *Return within 15 days of delivery.*                             |
| Tabular Prompting            | “Show return and replacement policy details in a table.”                        | See table below.                                                 |
| Preceding Question Prompting | Q1: “Do you allow returns after 20 days?” <br> Q2: “Then what about exchanges?” | *No returns after 20 days, but exchanges allowed up to 30 days.* |
## Return / Replacement Policy Table

| **Policy Type** | **Details**                       |
| --------------- | --------------------------------- |
| Return          | Within 15 days of purchase.       |
| Replacement     | Allowed up to 30 days.            |
| Refund          | Processed within 7 business days. |
---

# Observations

* Straightforward prompts provide direct answers quickly
* Tabular prompts provide structured information
* Preceding question prompts improve conversational context

---

# Detailed Explanation of Prompt Types

## 1. Straightforward Prompts

Direct and simple queries to get specific answers.

### Example 1

**Prompt:** Define photosynthesis in one sentence

**Response:**
Photosynthesis is the process by which green plants use sunlight, carbon dioxide, and water to produce food and oxygen.

### Example 2

**Prompt:** List three advantages of electric vehicles

**Response:**  
 1. Lower emissions – Electric vehicles produce zero tailpipe emissions, reducing air pollution and greenhouse gases.
 2. Lower operating costs – Electricity is generally cheaper than gasoline, and EVs have fewer moving parts, leading to lower maintenance costs.
 3. Energy efficiency – EVs convert a higher percentage of energy from the grid to power at the wheels compared to internal combustion engine vehicles.
---

## 2. Tabular Format Prompting

#### **2. Tabular Format Prompting**  
Information is presented in a structured table format.  

- **Prompt:**  
  ``  Compare and contrast AC and DC current in a table.``
  
  **Response:**
   <img width="996" height="257" alt="Screenshot 2025-09-25 085003" src="https://github.com/user-attachments/assets/bea2fe15-a0d8-495d-9e52-131fd37be38d" />

- **Prompt:**  
  `` Provide a table listing five programming languages, their paradigms, and one use case each.``
  
  **Response:**
     <img width="1043" height="347" alt="Screenshot 2025-09-25 085452" src="https://github.com/user-attachments/assets/caae9f0e-64c9-47b9-981e-21cc223512d7" />

---

## 3. Preceding Question Prompting

### Example 1

A question followed by a deeper explanation or reasoning.  

- **Prompt:**  
  `Why is climate change a global concern? Explain how greenhouse gases contribute to global warming.`  

**Response:**  
Climate change is a global concern because it affects the entire planet, leading to rising sea levels, extreme weather events, food and water insecurity, ecosystem disruption, and economic and health impacts that cross national borders. No country is immune, and global cooperation is essential to mitigate its effects and adapt to its consequences.

- **Prompt:**  
  `How do vaccines work? Describe the process of immunization in simple terms.`  

**Response:** 
1. A vaccine is given, usually as a shot. It contains a harmless part of a virus or bacteria (like a protein or a weakened/killed version).
2. Your immune system sees it as a threat and responds by making antibodies—proteins that fight the germ.
3. It also creates memory cells that "remember" how to fight that germ in the future.

---

## 4. Missing Word Prompting

### Example 1

**Prompt:** The capital of France is ____

**Response:** Paris

### Example 2

**Prompt:** In photosynthesis plants produce ____

**Response:** Glucose and Oxygen

---

## **Evaluation:**

| Prompt Type | Use Case Scenario | Strengths | Limitations | Result |
|-------------|-------------------|-----------|-------------|--------|
| Straightforward Prompt | Quick revision before exam | Simple, fast recall | Lacks details | Best for memory refresh |
| Tabular Format Prompt | Compare AM, FM, QPSK | Structured, clear | Needs prior understanding | Best for detailed comparison |
| Preceding Question Prompt | Understanding "why" & "how" | Encourages reasoning | Can be lengthy | Best for conceptual clarity |
| Missing Word Prompt | Exam recall practice | Good for assessment | Limited depth | Best for quick recall |
---


### **Conclusion:**  
Using the four prompt types, we explored how to generate diverse responses for the General Knowledge and Science Education . Each method provided a unique way to structure the query, improving clarity and depth of the generated responses.  

---

# Result

Thus, the prompts were executed successfully, and the report for the chosen use case was generated.

