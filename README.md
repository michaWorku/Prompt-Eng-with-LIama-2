# **Prompt Engineering with Llama 2 & 3**

## **Course Overview**
This course, [**Prompt Engineering with Llama 2 & 3**](https://www.deeplearning.ai/short-courses/prompt-engineering-with-llama-2/) is designed to teach the best practices for interacting with Meta's Llama models, including Llama 2 Chat, Code Llama, and Llama Guard. The course provides hands-on experience with effective prompting techniques for various tasks such as text classification, logical reasoning, and code generation. You'll also learn about ensuring safety in AI interactions using Llama Guard, and get the opportunity to work with Llama 2 and Llama 3 models, including local deployment options.

## **Course Content**
The course covers the following key topics:
1. **Introduction to Llama Models**
   - Overview of Llama 2 and Llama 3 models and their capabilities.
   - Differences between base and chat models, and their use cases.
2. **Prompt Engineering Techniques**
   - Few-shot prompting, chain-of-thought prompting, and role-based prompting.
   - Techniques for improving model responses by adding context and examples.
3. **Multi-Turn Conversations**
   - Managing multi-turn interactions and context maintenance across multiple prompts.
4. **Code Llama for Code Generation**
   - Using Code Llama models for code completion, generation, and optimization.
5. **Llama Guard**
   - Implementing safety measures to ensure safe AI responses and interaction.
6. **Llama Helper Function Walkthrough**
   - Understanding and using the Llama helper function to interact with Llama models via API calls.

## **Notebooks**
The course provides the following notebooks for hands-on learning:
- [L2_getting_started.ipynb]() – Introduction to Llama 2 and 3 models, including setup and usage.
- [L3_multi_turn_conversations.ipynb]() – Techniques for handling multi-turn conversations with Llama models.
- [L4_prompt_engineering_techniques.ipynb]() – A deep dive into prompt engineering methods such as few-shot and chain-of-thought prompting.
- [L5_comparing_llama_models.ipynb]() – Comparison of different Llama 2 and Llama 3 models across tasks like sentiment classification and summarization.
- [L6_code_llama.ipynb]() – Exploring Code Llama for code generation, completion, and in-filling.
- [L7_llama_guard.ipynb]() – Implementing Llama Guard for safety checks on inputs and outputs.
- [L8_walkthrough_helper_function.ipynb]() – Step-by-step guide for using the Llama helper function to interact with the Together.AI API.

## **Getting Started**
To get started, follow these steps:
1. **Install the Required Libraries**
   - Ensure you have Python installed.
   - Install the necessary dependencies by running:
     ```
     pip install -r requirements.txt
     ```
2. **Set Up the API Key for Together.AI**
   - Create an account on [Together.AI](https://api.together.xyz/).
   - Obtain your API key and set it as an environment variable:
     ```
     export TOGETHER_API_KEY=<your_api_key>
     ```
   - Alternatively, use `python-dotenv` to load the API key from a `.env` file.
3. **Run the Notebooks**
   - Open and run the provided Jupyter notebooks in your local environment to explore the course material and practice using Llama models.

## **Resources and References**
For further learning and references, you may find these resources helpful:
- [Llama 2 & 3 Official Documentation](https://ai.meta.com/llama/)
- [Prompt Engineering with llama 2 & 3](https://www.deeplearning.ai/short-courses/prompt-engineering-with-llama-2/)
- [Together.AI API Documentation](https://api.together.xyz/docs)

## **Helpers & Utils**
The **utils.py** file provides several helper functions to simplify interaction with the Llama models:
- **`llama`** – Core function for querying Llama models.
- **`llama_guard`** – Uses Llama Guard for safety checks on inputs and outputs.
- **`safe_llama`** – Runs Llama models with built-in safety filters.
- **`code_llama`** – Optimized for code-related queries and generation.
- **`llama_chat`** – Manages multi-turn conversations by maintaining prompt-response history.
- **`retry_logic`** – Implements retry logic for handling API failures with exponential backoff.

These helpers simplify working with the models and ensure smooth and safe interactions.


By following the instructions above, you'll be able to work through the notebooks and leverage the power of Llama models for various tasks, from natural language processing to code generation, with safety measures in place. Enjoy your learning journey!