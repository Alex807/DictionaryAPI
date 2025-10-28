# 📚 Multilingual Dictionary Application 📚

## 📋 Overview
A sophisticated multilingual-English dictionary application integrating **3 external REST APIs** with intelligent **caching mechanism** to optimize response times and preserve API token usage. Features **automated persistence** with real-time database state management and **GUI interface** using JavaSwing.

## ✨ Key Features
- **🌐 Multi-API Integration** - Dictionary API, MyMemory Translation, Cohere AI
- **💾 Smart Caching** - Local storage with persistent `.txt` database
- **🖥️ Dual Interface** - Both CLI and GUI versions available
- **🔄 Real-Time Translation** - Instant word definitions and translations
- **📝 Comprehensive Results** - Definitions, examples, synonyms, and antonyms
- **🗣️ Multi-Language Support** - Translation between multiple languages

## 🛠️ Technology Stack

**Core:** Java 11+, JavaSwing GUI, HTTP Client, JSON Processing

**Architecture:** Singleton Pattern, MVC Structure, REST API Integration, File I/O

**APIs:** Dictionary API (dictionaryapi.dev), MyMemory Translation API, Cohere AI API

## 🧩 Components
- **RunApp**: Main entry point for CLI and GUI options (user decides where to continue app execution)
- **GUI**: Graphical interface with modern styling
- **OnlineDictionary**: Core component managing the lookup process for information
- **Translator**: Converts words between languages
- **AIComponent**: Generates examples and related words
- **DataBaseManager**: Handles local storage
- **JSON_Parser**: Processes API responses
- **LanguageCodeFinder**: Maps language names to ISO codes

## 🏗️ Architecture
- **Singleton Pattern** for components needing single instances
- **MVC-like structure** separating data, logic, and interfaces
- **Local caching** to improve performance and save free tokens for the AI model

## 🚀 Usage
 ### Compile: javac RunApp.java  
Make sure you compile all components. 

 ### Execute: java RunApp
- **You don't need to run separated files for CLI/GUI, both are integrated into 'RunApp' entry point.**
- Launch and select "yes"/"y" for GUI version, otherwise you will go for CLI version.
