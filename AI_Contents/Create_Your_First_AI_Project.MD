*WHATSAPP GUIDE: HOW TO CREATE YOUR FIRST AI PROJECT USING YOUR OWN PDF/WORD DOCUMENTS (Gemini, ChatGPT, Claude, Grok & Copilot)*

*INTRODUCTION*
This guide will teach you how to build a personal or company-level AI assistant that:

* Reads and understands any PDF, Word document, or training manual
* Generates accurate responses based ONLY on your uploaded files (not the internet)
* Follows a structured format (lesson plans, analysis templates, report formats, etc.)
* Works on any LLM platform: *Google Gemini Gems, ChatGPT Custom GPTs, Claude Projects, Grok Projects, and Microsoft Copilot GPTs*

This mirrors the sample project structure:

1. *E-Notes* (knowledge base)
2. *Structure* (how AI should respond)
3. *Instruction* (prompt to control the AI)

---

## *STEP 1: PREPARE YOUR PROJECT FILES*

Every AI project needs 3 components:

### *1. The Source Document (Your Knowledge Base)*

Examples:

* Company PDF manuals
* School e-notes
* Policy documents
* Internal SOPs
* Training materials
* Handbooks

This document acts as the *ONLY source of truth* for the AI.
Example from your physics project: *SSS1 Physics E-Note file*.

---

### *2. The Response Structure (Your Output Format)*

This is the exact format the AI must follow when generating results.

Examples:

* Weekly lesson note format
* Report template
* Customer response structure
* Summary structure
* Compliance checklist

In your sample project: *Lesson Plan Structure template*.

---

### *3. Instruction File (Your Operating Rules for the AI)*

This tells the AI:

* When it should generate an answer
* What format to follow
* What rules to obey
* What to avoid
* How to handle missing information

In your sample project: *Instruction A.txt*.

---

## *STEP 2: CHOOSE YOUR AI PLATFORM*

You can build this project using *any AI model*. Each platform has a project mode where you can upload files.

*A. Google Gemini – “Create a Gem”*

* Go to [https://gemini.google.com](https://gemini.google.com)
* Click: *Create → New Gem*
* Upload your files (PDF, Word, text)
* Paste your instruction script
* Name your Gem (e.g., “Lesson Note Generator”)

---

*B. ChatGPT – “Create a Custom GPT”*

* Go to [https://chat.openai.com/create](https://chat.openai.com/create)
* Upload your files
* Paste your instruction text in the “Instructions” section
* Set: “Use only the provided files”
* Save as a Custom GPT

---

*C. Claude AI – “Create a Project”*

* Go to Claude.ai
* Click *Projects*
* Upload your files
* Add your instruction text
* Save

---

*D. Grok – “Create a Grok Project”*

* Go to x.ai
* Start a new project
* Upload the knowledge files
* Add system instructions
* Save

---

*E. Microsoft Copilot – “Copilot GPT or Copilot Studio”*

* For simple use: Copilot GPT Builder
* For advanced: Copilot Studio
* Upload files, add instructions, save

---

## *STEP 3: WRITE THE CORE INSTRUCTION FOR THE AI*

Use this framework (you will replace the examples with your own files):

---

### *CORE INSTRUCTION TEMPLATE*

“You are an expert assistant.
Your job is to generate answers strictly using ONLY the uploaded documents.
Whenever the user calls a specific request (e.g., ‘Week 1 lesson note’, ‘Summaries’, ‘Extract key points’), follow the format in the Structure File and extract your content ONLY from the E-Note file.

Rules:

* Do not use internet information
* Do not hallucinate
* If content is missing, write: *CONTENT GAP DETECTED*
* Always follow the structure template exactly
* Keep all responses professional, clear, and consistent”

---

Paste the instruction into:

* Gemini Gem instructions
* ChatGPT Builder → “Instructions”
* Claude Project → “System Prompt”
* Grok Project → “Instruction”
* Copilot Studio → “System Message”

---

## *STEP 4: UPLOAD YOUR FILES PROPERLY*

You must upload the files in this exact order:

1. *E-Note / Knowledge Base*
2. *Structure Template*
3. *Instruction Script*

Label them clearly.
Most platforms allow *drag and drop*.

For best performance:

* Use PDF or .txt format
* Remove unnecessary images
* Keep titles clean
* Ensure the file matches the structure you want

---

## *STEP 5: TEST THE AI WITH CONTROLLED COMMANDS*

Test it using simple, clear prompts like:

* “Week 1”
* “Generate the lesson note for Week Two”
* “Create a summary of the measurement unit chapter”
* “Extract 15 exam questions from the uploaded material”
* “Follow the structure template to output a compliant lesson plan”

If the AI responds perfectly, your project is ready.
If it struggles, adjust the instruction until behavior stabilizes.

---

## *STEP 6: EXAMPLES OF REAL-WORLD USE CASES*

This workflow is powerful for people who regularly receive documents at work:

### *A. Education*

* Automated lesson plans
* Summaries for students
* Exam questions
* Topic explanations
* Weekly assessments

### *B. Corporate Admin*

* Convert PDF policies into readable summaries
* Generate staff training guides
* Convert procedures into checklists
* Extract key points from long documents
* Create automated email templates from manuals

### *C. Government / NGOs*

* Convert policy releases into public-friendly summaries
* Automatic report drafting
* Data extraction from official documents

### *D. Business*

* SOP document automation
* Staff training materials
* Customer response templates
* Contracts summarization

---

## *STEP 7: GOOD PRACTICES TO KEEP YOUR AI PROJECT ACCURATE*

1. *Keep documents clean and well-scanned*
2. *Update your files regularly*
3. *Do NOT mix unrelated documents in the same project*
4. *Create separate projects for separate topics*
5. *Use strong instructions: no internet, no external data*
6. *Define the response structure explicitly*

---

## *STEP 8: ADVANCED VERSION (OPTIONAL)*

Add these for stronger control:

* “Always cite the section of the document used.”
* “Do not answer if the document does not support the claim.”
* “Follow my structure word-for-word.”
* “Keep tone professional and instructional.”
* “Convert tables into structured lists.”

---

## *FINAL RESULT*

By the end of this project, you will be able to build:

* A *private AI tutor*
* A *lesson-plan automator*
* A *company policy assistant*
* A *document-based chatbot*
* A *research extraction tool*
* A *personal PDF analysis system*

All based completely on your own documents.
