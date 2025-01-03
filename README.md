# T81 559:Applications of Generative Artificial Intelligence

[Washington University in St. Louis](http://www.wustl.edu)

Instructor: [Jeff Heaton](https://sites.wustl.edu/jeffheaton/)

- Section 1. Spring 2025, Wednesday, 6:00 PM, Location: January Hall / 10

# Course Description

This course covers the dynamic world of Generative Artificial Intelligence providing hands-on practical applications of Large Language Models (LLMs) and advanced text-to-image networks. Using Python as the primary tool, students will interact with OpenAI's models for both text and images. The course begins with a solid foundation in generative AI principles, moving swiftly into the utilization of LangChain for model-agnostic access and the management of prompts, indexes, chains, and agents. A significant focus is placed on the integration of the Retrieval-Augmented Generation (RAG) model with graph databases, unlocking new possibilities in AI applications.

As the course progresses, students will delve into sophisticated image generation and augmentation techniques, including LORA (LOw-Rank Adaptation), and learn the art of fine-tuning generative neural networks for specific needs. The final part of the course is dedicated to mastering prompt engineering, a critical skill for optimizing the efficiency and creativity of AI outputs. Ideal for students, researchers, and professionals in computer science or related fields, this course offers a transformative learning experience where technology meets creativity, paving the way for innovative applications in the realm of Generative AI.

Note: This course will require the purchase of up to $100 in OpenAI API credits to complete the course.

# Objectives

1. Learn how Generative AI fits into the landscape of deep learning and predictive AI.
2. Be able to create ChatBots, Agents, and other LLM-based automation assistants.
3. Understand how to make use of image generative AI programatically.

# Syllabus

This [syllabus](https://data.heatonresearch.com/wustl/syllabus/jheaton-t81-559-spring-2025-syllabus.pdf) presents the expected class schedule, due dates, and reading assignments. Download current syllabus.

| Module                                                                       | Content                                                                                                                                                                                                                                                                                                                                                                     |
| ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Module 1](t81_559_class_01_1_overview.ipynb)<br>**Meet on 01/15/2025**      | **Module 1: Introduction to Generative AI**<ul><li>1.1: Course Overview<li>1.2: Generative AI Overview<li>1.3: Introduction to OpenAI<li>1.4: Introduction to LangChain<li>1.5: Prompt Engineering<li>**We will meet on campus this week! (first meeting)**</ul>                                                                                                            |
| [Module 2](t81_559_class_02_1_dev.ipynb)<br>Week of 1/22/2025                | **Module 2: Prompt Based Development**<ul><li>2.1: Prompting for Code Generation<li>2.2: Handling Revision Prompts<li>2.3: Using a LLM to Help Debug<li>2.4: Tracking Prompts in Software Development<li>2.5: Limits of LLM Code Generation<li>[Module 1 Program](./assignments/assignment_yourname_t81_559_class1.ipynb) due: 1/23/2025<li> Icebreaker due: 1/23/2025</ul> |
| [Module 3](t81_559_class_03_1_llm.ipynb)<br>Week of 1/29/2025                | **Module 3: Introduction to Large Language Models**<ul><li>3.1: Foundation Models<li>3.2: Text Generation<li>3.3: Text Summarization<li>3.4: Text Classification<li>3.5 LLM Writes a Book<li>[Module 2 Program](./assignments/assignment_yourname_t81_559_class2.ipynb) due: 1/30/2025</ul>                                                                                 |
| [Module 4](t81_559_class_04_1_langchain_chat.ipynb)<br>Week of 2/5/2025      | **Module 4: LangChain: Chat and Memory**<ul><li>4.1: LangChain Conversations<li>4.2: Conversation Buffer Window Memory<li>4.3: Conversation Token Buffer Memory<li>4.4: Conversation Summary Memory<li>4.5: Persisting Langchain Memory<li>[Module 3: Program](./assignments/assignment_yourname_t81_559_class3.ipynb) due: 2/6/2025</ul>                                   |
| [Module 5](t81_559_class_05_1_langchain_data.ipynb)<br>**Meet on 2/12/2025** | **Module 5: LangChain: Data Extraction**<ul><li>5.1: Structured Output Parser<li>5.2: Other Parsers (CSV, JSON, Pandas, Datetime)<li>5.3: Pydantic parser<li>5.4: Custom Output Parser<li>5.5: Output-Fixing Parser<li>[Module 4 Program](./assignments/assignment_yourname_t81_559_class4.ipynb) due: 2/13/2025</ul>                                                       |
| [Module 6](t81_559_class_06_1_rag.ipynb)<br>Week of 2/19/2025                | **Module 6: Retrieval-Augmented Generation (RAG)**<ul><li>6.1 Introduction to RAG<li>6.2 Introduction to ChromaDB<li>6.3 Understanding Embeddings<li>6.4 Q&A Over Documents<li>6.5 Embedding Databases<li>[Module 5 Program](./assignments/assignment_yourname_t81_559_class5.ipynb) due: 2/20/2025</ul><li>**We will meet on campus this week! (second meeting)**          |
| [Module 7](t81_559_class_07_1_agents.ipynb)<br>Week of 2/26/2025             | **Module 7: LangChain: Agents**<ul><li>7.1: Introduction to LangChain Agents<li>7.2: Understanding LangChain Agent Tools<li>7.3: LangChain Retrival and Search Tools<li>7.4: Constructing LangChain Agents<li>7.5: Custom Agents<li>[Module 6 Program](./assignments/assignment_yourname_t81_559_class6.ipynb) due: 2/27/2025</ul>                                          |
| [Module 8](t81_559_class_08_1_kaggle_intro.ipynb)<br>**Meet on 3/5/2025**    | **Module 8: Kaggle Assignment**<ul><li>8.1: Introduction to Kaggle<li>8.2: Kaggle Notebooks<li>8.3: Small Large Language Models <li>8.4: Accessing Small LLM from Kaggle<li>8.5: Current Semester's Kaggle<li>[Module 7 Program](./assignments/assignment_yourname_t81_559_class7.ipynb) due: 3/6/2025<li>**We will meet on campus this week! (third meeting)**</ul>        |
| [Module 9](t81_559_class_09_1_image_genai.ipynb)<br>Week of 3/19/2025        | **Module 9: MultiModal and Text to Image**<ul><li>9.1: Introduction to MultiModal and Text to Image<li>9.2: Generating Images with DALL·E<li>9.3: Editing Existing Images with DALL·E<li>9.4: MultiModal Models<li>9.5: Illustrated Book<li>[Module 8 Program](./assignments/assignment_yourname_t81_559_class8.ipynb) due: 3/20/2025</ul>                                  |
| [Module 10](t81_559_class_10_1_streamlit.ipynb)<br>Week of 3/26/2025         | **Module 10: Introduction to StreamLit**<ul><li>10.1: Running StreamLit in Google Colab<li>10.2: StreamLit Introduction<li>10.3: Understanding Streamlit State<li>10.4: Creating a Chat Application<li>10.5: More Advanced Chat Application<li>[Module 9 Program](./assignments/assignment_yourname_t81_559_class9.ipynb) due: 3/27/2025</ul>                               |
| [Module 11](t81_559_class_11_1_finetune.ipynb)<br>Week of 4/2/2025           | **Module 11: Fine Tuning**<ul><li>11.1: When is fine tuning necessary<li>11.2: Preparing a dataset for fine tuning<li>11.3: OepnAI Fine Tuning<li>11.4: Application of Fine Tuning<li>11.5: Evaluating Fine Tuning and Optimization<li>[Module 10 Program](./assignments/assignment_yourname_t81_559_class10.ipynb) due: 4/3/2025</ul>                                      |
| [Module 12](t81_559_class_12_1_prompt_engineering.ipynb)<br>Week of 4/9/2025 | **Module 12: Prompt Engineering**<ul><li>12.1 Intro to Prompt Engineering<li>12.2 Few Shot and Chain of Thought<li>12.3: Persona and Role Patterns<li>12.4: Question, Refinement and Verification Patterns<li>12.5: Content Creation and Structured Prompt Patterns</ul>                                                                                                    |
| [Module 13](t81_559_class_13_1_speech_models.ipynb)<br>Week of 4/16/2025     | **Module 13: Speech Processing**<ul><li>13.1: Voice-Based ChatBots <li>13.2: OpenAI Speech Generation<li>13.3: OpenAI Speech Recognition<li>13.4: A Voice-Based ChatBot<li>13.5: Future Directions in GenAI<li>Kaggle Assignment due: 4/17/2025 (approx 4-6PM, due to Kaggle GMT timezone)</ul>                                                                             |
| Week 14<br>**Meet on 4/23/2025**                                             | **Week 14: Kaggle Presentations**<ul><li>Top Kaggle teams will present<li>**We will meet on campus this week! (fourth meeting)**<li>Final project due: 4/23/2025</ul>                                                                                                                                                                                                       |
