# 🤖 Agentic AI Projects Collection

> **A comprehensive collection of AI-powered applications demonstrating various frameworks, technologies, and use cases in modern AI development.**

![AI Projects](https://img.shields.io/badge/AI-Powered-Collection-blue) ![Python](https://img.shields.io/badge/Python-3.8+-green) ![Streamlit](https://img.shields.io/badge/Streamlit-Web%20Apps-red) ![LangChain](https://img.shields.io/badge/LangChain-Framework-orange)

## 📚 Overview

This repository contains a diverse collection of AI-powered applications built using cutting-edge frameworks and technologies. Each project demonstrates different aspects of modern AI development, from multi-agent systems to conversational AI, from code analysis to financial planning.

## 🏗️ Technology Stack Overview

### **Core AI Frameworks**

| Framework | Description | Projects Using |
|-----------|-------------|----------------|
| **LangChain** | LLM application framework for building AI applications | 3 projects |
| **LangGraph** | Stateful, multi-actor applications with LLMs | 2 projects |
| **AutoGen** | Multi-agent conversation framework by Microsoft | 4 projects |
| **CrewAI** | Framework for orchestrating role-playing autonomous AI agents | 1 project |

### **LLM Providers**

| Provider | Model | Projects Using |
|----------|-------|----------------|
| **Google Gemini** | Gemini 1.5 Flash | 8 projects |
| **OpenAI** | GPT models | 1 project |

### **UI Frameworks**

| Framework | Description | Projects Using |
|-----------|-------------|----------------|
| **Streamlit** | Web app framework for data science | 5 projects |
| **Gradio** | Web interface for ML models | 2 projects |
| **Jupyter/Colab** | Notebook-based interfaces | 3 projects |

## 🎯 Projects by Technology Category

### **🤖 Multi-Agent Systems (AutoGen)**

#### 1. **AI Bill Management Agent**
- **Technology**: AutoGen + Google Gemini + Streamlit
- **Features**: Multi-agent collaboration for bill processing, expense categorization, and financial insights
- **Agents**: UserProxy, Bill Processing, Expense Summarization, Group Chat Manager
- **Use Case**: Automated expense tracking and financial analysis

#### 2. **Smart Health Assistant**
- **Technology**: AutoGen + Google Gemini + Jupyter
- **Features**: Personalized health, diet, and fitness plan generation
- **Agents**: BMI Specialist, Diet Planner, Workout Scheduler, User Proxy
- **Use Case**: Comprehensive health and wellness planning

#### 3. **Smart Content Creation**
- **Technology**: AutoGen + Google Gemini + Colab
- **Features**: Reflection-based content refinement through collaborative AI agents
- **Agents**: Content Architect, Quality Inspector with reflection mechanisms
- **Use Case**: High-quality content creation and refinement

#### 4. **EDA Multi-Agent System**
- **Technology**: AutoGen + Google Gemini + Jupyter
- **Features**: Automated exploratory data analysis with specialized agents
- **Agents**: Data Preparation, EDA, Report Generator, Critic, Executor, Admin
- **Use Case**: Streamlined data analysis and reporting

### **🔗 LangChain & LangGraph Applications**

#### 5. **LangGraph Math & Q&A Agent**
- **Technology**: LangGraph + LangChain + Google Gemini + Gradio
- **Features**: Intelligent routing between general Q&A and mathematical calculations
- **Tools**: Custom mathematical functions (addition, subtraction, multiplication, division)
- **Use Case**: Educational tool for math and general knowledge queries

#### 6. **Multi-Agent RAG System**
- **Technology**: LangGraph + LangChain + Google Gemini + Streamlit
- **Features**: Intelligent query routing between web search, RAG, and LLM reasoning
- **Agents**: Router, Web Research, RAG, LLM, Summarization
- **Use Case**: Comprehensive research and information retrieval system

### **👥 CrewAI Applications**

#### 7. **Personalized Education Assistant**
- **Technology**: CrewAI + Google Gemini + Streamlit
- **Features**: Sequential AI agents for personalized learning path generation
- **Agents**: Learning Material Curator, Quiz Creator, Project Mentor
- **Use Case**: Customized educational content and assessment generation

### **🎨 Streamlit Web Applications**

#### 8. **Automated Code Debugging Assistant**
- **Technology**: Google Gemini + Streamlit + AST Analysis
- **Features**: AI-powered code analysis, static analysis, and intelligent suggestions
- **Capabilities**: Code metrics, issue detection, best practices enforcement
- **Use Case**: Code quality improvement and debugging assistance

#### 9. **Financial Portfolio Manager**
- **Technology**: Multi-agent + Google Gemini + Streamlit
- **Features**: Intelligent investment analysis and personalized financial planning
- **Agents**: Portfolio Analyst, Growth/Value Strategist, Financial Advisor
- **Use Case**: Investment strategy and financial planning

### **🌐 Conversational AI & Travel**

#### 10. **Intelligent Travel Assistant**
- **Technology**: LangChain + Google Gemini + Gradio
- **Features**: Live weather information, tourist attractions, travel tips
- **Integrations**: WeatherAPI, DuckDuckGo search
- **Use Case**: Travel planning and destination information

#### 11. **Conversational AI for Competitor Analysis**
- **Technology**: LangChain + Search Tools + Visualization
- **Features**: Retail competitor analysis with data visualization
- **Capabilities**: Market analysis, competitor insights, visual reports
- **Use Case**: Business intelligence and market research

## 🚀 Quick Start Guide

### **Prerequisites**
- Python 3.8 or higher
- Google Gemini API key ([Get it here](https://makersuite.google.com/app/apikey))
- For some projects: Additional API keys (Serper, WeatherAPI, etc.)

### **Installation**

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Agentic_AI_Projects
   ```

2. **Navigate to specific project**
   ```bash
   cd [project-name]
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   ```bash
   # Create .env file
   echo GEMINI_API_KEY=your_gemini_api_key_here > .env
   ```

5. **Run the application**
   ```bash
   # For Streamlit apps
   streamlit run main.py
   
   # For Jupyter notebooks
   jupyter notebook
   
   # For Gradio apps
   python app.py
   ```

## 📊 Project Statistics

| Category | Count | Technologies |
|----------|-------|--------------|
| **Multi-Agent Systems** | 4 | AutoGen, CrewAI |
| **LangChain/LangGraph** | 2 | LangChain, LangGraph |
| **Streamlit Web Apps** | 3 | Streamlit, Gemini |
| **Conversational AI** | 2 | LangChain, Gradio |
| **Total Projects** | **11** | Various AI frameworks |

## 🎯 Learning Paths

### **Beginner Level**
1. **Intelligent Travel Assistant** - Basic LangChain integration
2. **Automated Code Debugging Assistant** - Simple AI-powered tools
3. **Conversational AI for Competitor Analysis** - Basic conversational AI

### **Intermediate Level**
1. **Smart Health Assistant** - Multi-agent collaboration
2. **LangGraph Math & Q&A Agent** - Stateful workflows
3. **Financial Portfolio Manager** - Complex multi-agent systems

### **Advanced Level**
1. **Multi-Agent RAG System** - Advanced query routing
2. **Smart Content Creation** - Reflection-based agentic patterns
3. **EDA Multi-Agent System** - Specialized domain agents
4. **Personalized Education Assistant** - Sequential agent workflows

## 🛠️ Technology Deep Dive

### **AutoGen Framework**
- **Purpose**: Multi-agent conversation and collaboration
- **Key Features**: Agent orchestration, conversation management, tool integration
- **Projects**: Bill Management, Health Assistant, Content Creation, EDA System

### **LangChain Framework**
- **Purpose**: LLM application development
- **Key Features**: Chain composition, memory management, tool integration
- **Projects**: Travel Assistant, Competitor Analysis

### **LangGraph Framework**
- **Purpose**: Stateful, multi-actor applications
- **Key Features**: Workflow orchestration, state management, conditional routing
- **Projects**: Math & Q&A Agent, Multi-Agent RAG System

### **CrewAI Framework**
- **Purpose**: Role-playing autonomous AI agents
- **Key Features**: Sequential processing, specialized agent roles, structured outputs
- **Projects**: Personalized Education Assistant

## 📈 Key Features Across Projects

### **Multi-Agent Collaboration**
- Agent specialization and role definition
- Inter-agent communication and coordination
- Sequential and parallel processing workflows
- Quality assurance through agent critique

### **AI-Powered Analysis**
- Natural language processing and understanding
- Code analysis and improvement suggestions
- Financial data analysis and recommendations
- Health and wellness planning

### **Modern User Interfaces**
- Responsive web applications with Streamlit
- Interactive Gradio interfaces
- Jupyter notebook-based interfaces
- Real-time progress tracking and feedback

### **Data Processing & Visualization**
- Real-time data analysis and insights
- Interactive charts and graphs
- Export capabilities (CSV, JSON, reports)
- Custom data visualization

## 🔧 Configuration & Setup

### **Environment Variables**
Most projects require the following environment variables:

```env
# Required for most projects
GEMINI_API_KEY=your_gemini_api_key_here

# Optional for specific projects
SERPER_API_KEY=your_serper_api_key_here
WEATHER_API_KEY=your_weather_api_key_here
```

### **API Key Setup**
1. **Google Gemini**: [Get API key](https://makersuite.google.com/app/apikey)
2. **Serper (for web search)**: [Get API key](https://serper.dev/)
3. **WeatherAPI**: [Get API key](https://www.weatherapi.com/)

## 🎨 UI/UX Features

### **Design Patterns**
- **Glassmorphism**: Modern glass-like UI elements
- **Dark Theme**: Eye-friendly color schemes
- **Responsive Design**: Works on all screen sizes
- **Interactive Elements**: Hover effects and animations

### **User Experience**
- **Real-time Feedback**: Instant processing results
- **Progress Tracking**: Visual indicators for long-running tasks
- **Error Handling**: Graceful error management
- **Export Options**: Download results and reports

## 🚀 Deployment Options

### **Local Development**
- All projects can run locally with Python
- Virtual environment recommended
- Local API key management

### **Cloud Deployment**
- **Google Colab**: Notebook-based projects
- **Streamlit Cloud**: Streamlit applications
- **Hugging Face Spaces**: Gradio applications
- **Heroku/Vercel**: Web application deployment

## 📚 Educational Value

### **AI Framework Learning**
- **AutoGen**: Multi-agent system design
- **LangChain**: LLM application development
- **LangGraph**: Stateful workflow orchestration
- **CrewAI**: Sequential agent processing

### **Practical Applications**
- **Code Analysis**: Static analysis and improvement
- **Financial Planning**: Investment strategy and portfolio management
- **Health & Wellness**: Personalized health recommendations
- **Education**: Customized learning paths
- **Business Intelligence**: Competitor analysis and market research

## 🙏 Acknowledgments

- **Google AI**: For providing the Gemini API platform
- **Microsoft**: For AutoGen multi-agent framework
- **LangChain**: For the excellent AI framework
- **CrewAI**: For role-playing agent framework
- **Streamlit**: For the beautiful web interface framework
- **Open Source Community**: For continuous inspiration and support

## 📞 Support

- 🐛 **Bug Reports**: Open an issue on GitHub
- 💡 **Feature Requests**: Discuss in GitHub Discussions
- 📧 **Contact**: Reach out for collaboration

---

**Built with ❤️ using cutting-edge AI frameworks and technologies**

*Empowering AI development through practical, real-world applications* 