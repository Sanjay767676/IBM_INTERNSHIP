# 🤖 IBM Watson AI Financial Advisor with stock predictions Agent

## 📋 Overview

This project contains a Jupyter notebook that demonstrates the use of IBM Watson AI agents configured in **Agent Lab** within the IBM Cloud platform. The notebook showcases how to create and deploy a financial advisor AI agent specifically designed for Indian users, providing guidance on personal and business finance topics.

The agent is created and runs directly in the IBM Cloud environment using watsonx.ai services.

## ✨ Features

- 🏢 **IBM Cloud Agent Lab**: Built and deployed directly in IBM Cloud's Agent Lab
- 💰 **Financial AI Agent**: Specialized financial advisor agent for Indian users
- 🔧 **Multi-tool Integration**: Includes tools for web search, weather, Wikipedia, and web crawling
- 🇮🇳 **Indian Financial Focus**: Tailored for Indian financial systems, regulations, and currency (INR ₹)
- 🔗 **LangGraph Integration**: Built using LangGraph for agent orchestration
- 🤖 **Watson AI Models**: Powered by IBM's watsonx.ai foundation models

## 🚀 Prerequisites

- ☁️ IBM Cloud account with access to watsonx.ai
- 🧪 Agent Lab access in IBM Cloud
- 🔑 Personal API key for IBM Cloud services

## ⚙️ IBM Cloud Setup

### 1. 🔐 Access Agent Lab
- Log into your IBM Cloud account
- Navigate to watsonx.ai service
- Access Agent Lab from the watsonx.ai dashboard

### 2. 🏗️ Create the Financial Advisor Agent
- Use the provided notebook code in Agent Lab
- Configure the agent with the specified tools and parameters
- Deploy the agent in your IBM Cloud environment

### 3. 🔧 Configure Credentials
The notebook includes functions to handle IBM Cloud authentication:
- Personal API key management
- Bearer token generation
- Project/Space ID configuration

## ⚙️ Agent Configuration

### 🤖 Model Settings
- **Model**: `meta-llama/llama-3-3-70b-instruct`
- **Temperature**: 0 (deterministic responses)
- **Max Tokens**: 2000
- **Top P**: 1

### 🛠️ Available Tools
- 🔍 **Google Search**: Web search functionality
- 🦆 **DuckDuckGo**: Alternative search engine
- 📚 **Wikipedia**: Knowledge base access
- 🕷️ **Web Crawler**: Web content extraction
- 🌤️ **Weather**: Weather information

## 💬 Usage

### 🚀 Running the Agent
1. **Execute the notebook** in IBM Cloud's Agent Lab environment
2. **Enter your IBM Cloud API key** when prompted
3. **Ask financial questions** through the agent interface

### 💡 Example Questions
The agent can help with:
- 💰 **Budgeting and Saving**: Indian income profiles and saving strategies
- 📊 **Tax Planning**: ITR filing, exemptions, and Indian tax laws
- 📈 **Investments**: FDs, SIPs, ELSS, NPS, and Indian stock markets
- 🏦 **Banking**: UPI, NEFT, IMPS, and Indian banking systems
- 💳 **Loans**: Eligibility criteria and loan types from Indian banks/NBFCs

## 🎯 Financial Expertise

The agent is specifically trained for Indian financial contexts:
- 📋 Indian Income Tax Act and GST laws
- 🏛️ RBI guidelines and SEBI regulations
- 📊 Indian stock markets (NSE, BSE)
- 💼 Mutual funds, PPF, EPF, NPS
- 🏦 Indian banking systems and digital payments

## 🔒 Security and Compliance

- ⚠️ **No Financial Advice**: The agent provides guidance but not specific investment advice
- 📋 **SEBI Compliance**: Always recommends consulting SEBI-registered advisors
- 🛡️ **IBM Cloud Security**: Leverages IBM Cloud's enterprise-grade security
- 🔐 **Data Privacy**: Follows IBM's data protection standards

## 🔧 Troubleshooting

### 🚨 Common Issues
1. **API Key Error**: Ensure your IBM Cloud API key is valid and has proper permissions
2. **Model Access**: Verify you have access to the specified model in your watsonx.ai instance
3. **Agent Lab Access**: Confirm you have proper access to Agent Lab in IBM Cloud

### 📚 Getting Help
- 📖 IBM Cloud Documentation: [https://cloud.ibm.com/docs](https://cloud.ibm.com/docs)
- 🤖 Watson AI Documentation: [https://www.ibm.com/watson](https://www.ibm.com/watson)
- 🆘 IBM Cloud Support: [https://cloud.ibm.com/support](https://cloud.ibm.com/support)

## 📄 License

This project is licensed under the ILAN License. See the notebook for full license details.

**Copyright © 2024 IBM**

## 🆘 Support

For technical support:
- 🆘 IBM Cloud Support: [https://cloud.ibm.com/support](https://cloud.ibm.com/support)
- 🤖 Watson AI Documentation: [https://www.ibm.com/watson](https://www.ibm.com/watson)

---


**Note**: This agent is created and runs in IBM Cloud's Agent Lab environment. The notebook code is auto-generated and optimized for the IBM Cloud platform. 
