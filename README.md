💱 LangChain Currency Converter
🚀 Overview

This project is an AI-powered Currency Converter built using LangChain Tool Calling.
It uses a Large Language Model (LLM) to intelligently decide which tools to call for performing real-time currency conversion.

🧠 Features
🔧 Custom tools using LangChain (@tool)
🤖 LLM-based tool calling
🌐 Real-time currency exchange rate API integration
🔁 Multi-step reasoning (rate fetching → conversion)
💬 Natural language input support
🏗️ Tech Stack
Python
LangChain
OpenAI / LLM
Requests
ExchangeRate API
⚙️ How It Works

User enters a query:

Convert 100 INR to USD
LLM processes the query and:
Calls get_conversion_factor tool
Then calls convert tool

Final output:

100 INR = 1.20 USD
🔧 Tools Implemented
1. get_conversion_factor

Fetches real-time exchange rates from API.

2. convert

Performs currency conversion using fetched rate.

3. multiply (Demo Tool)

Used to test tool calling functionality.

📂 Project Structure
langchain-currency-converter/
│── Tool_calling_in_langchain.ipynb
│── README.md

📸 Example
Input: Convert 500 INR to USD  
Output: 500 INR = 6.02 USD
🎯 Learning Outcomes
LangChain tool calling implementation
Building real-world LLM applications
API integration with AI workflows
Multi-step reasoning
🔮 Future Improvements
🤖 Add AgentExecutor (automate tool calls)
🌐 Build Streamlit UI
📊 Add logging and error handling
🔗 Support multiple APIs

👩‍💻 Author
Diksha Patil

⭐ Support

If you found this project helpful, give it a ⭐ on GitHub!
