# Data_Science_With_GenAI

A comprehensive repository covering essential topics in Data Science, Machine Learning, and Python programming with practical implementations and assignments.

## 📚 Repository Structure

```
.
├── Python_Basics.ipynb              # Python fundamentals and concepts
├── Data_Types_and_Structures.ipynb  # Python data types and structures
├── Functions.ipynb                  # Python functions and advanced concepts
├── Python_OOPS.ipynb              # Object-Oriented Programming in Python
├── Data_Toolkit/                   # Data manipulation and analysis tools
├── Error_handling/                 # Exception handling and file operations
├── Machine_Learning/               # ML algorithms and implementations
├── Restful_API/                   # API development with Flask
├── Statistics/                    # Statistical analysis and methods
└── README.md                      # This file
```

## 🐍 Python Fundamentals

### [Python Basics](Python_Basics.ipynb)
- **What is Python and why is it popular?** - Overview of Python's versatility in web development, data science, and machine learning
- **Python Interpreter** - Understanding how Python executes code line-by-line
- Core programming concepts and Python syntax

### [Data Types and Structures](Data_Types_and_Structures.ipynb)
- Python built-in data types
- Lists, tuples, dictionaries, and sets
- Data structure operations and methods

### [Functions](Functions.ipynb)
- Function definition and calling
- **Generator functions** - Including file reading implementations
- Lambda functions and advanced concepts
- **File operations** - Line-by-line reading with generators

### [Python OOPS](Python_OOPS.ipynb)
- Object-Oriented Programming concepts
- Classes, objects, inheritance, and polymorphism
- Design patterns and best practices

## 🔧 Data Toolkit

### [Data Analysis Tools](Data_Toolkit/Data_Toolkit.ipynb)
- **Pandas describe() function** - Statistical summaries of datasets
- **Missing data handling** - Critical for reliable analysis using `fillna()`, `dropna()`, and interpolation
- **Plotly visualization** - Interactive, web-ready visualizations with built-in features
- Working with [services.csv](Data_Toolkit/services.csv) dataset

## ⚠️ Error Handling & File Operations

### [Exception Handling](Error_handling/files_and_exceptional_handling_assignment.ipynb)
Comprehensive coverage of Python error handling:

- **Exception handling basics** - `try`, `except`, `else`, and `finally` blocks
- **File operations** - Reading, writing, and manipulating files
- **Logging module** - Different logging levels (DEBUG, INFO, WARNING, ERROR, CRITICAL)
- **Memory management** - Python's garbage collection and optimization
- **Multithreading vs Multiprocessing** - Understanding the differences

#### Key Features:
- **Division by zero handling** - Proper exception catching
- **File existence checking** - Using `os.path.exists()`
- **Context managers** - Safe file handling with `with` statements
- **Word counting** - File content analysis
- **Memory profiling** - Performance monitoring

## 🤖 Machine Learning

### [Machine Learning Fundamentals](Machine_Learning/Machine_learning.ipynb)
- **Data preprocessing** - Essential for model training
- **Test sets** - Unbiased model evaluation
- **Data splitting** - Using [`train_test_split`](Machine_Learning/Machine_learning.ipynb)
- **Data encoding** - Label encoding and one-hot encoding techniques

### [Advanced ML Concepts](Machine_Learning/Used.ipynb)
Key machine learning terminology and concepts:
- **Ethics and Bias** - Addressing fairness in ML models
- **Interpretability** - Understanding model decisions
- **Scalability** - Handling increasing data complexity
- **Transfer Learning** - Adapting pre-trained models
- **Ensemble Learning** - Combining multiple models
- **Data Preprocessing** - Normalization and feature scaling

### [Decision Trees](Machine_Learning/DecisionTree/)
Comprehensive decision tree implementations:

#### [DecisionTreeAssignment.ipynb](Machine_Learning/DecisionTree/DecisionTreeAssignment.ipynb)
- **Gini Impurity** - Feature importance calculation
- **Entropy criterion** - Alternative splitting method with perfect accuracy
- **Decision Tree Regressor** - Housing dataset analysis with MSE evaluation
- **Tree visualization** - Using graphviz for model interpretation
- **Max depth comparison** - Comparing constrained vs. fully grown trees

## 🌐 RESTful API Development

### [Flask API Development](Restful_API/Restful_API_&_Flask.ipynb)
Complete guide to building APIs with Flask:

- **Flask basics** - Lightweight Python web framework
- **Routing** - URL-to-function mapping with `@app.route()`
- **HTTP methods** - GET, POST, PUT, PATCH, DELETE
- **JSON handling** - Request/response formatting
- **Security** - Authentication, validation, and CORS
- **Status codes** - Proper HTTP response codes (200, 201, 400, 401, 404, 500)

## 📊 Statistics

### [Statistical Analysis](Statistics/)
- **Independent T-tests** - Statistical hypothesis testing
- Advanced statistical methods and implementations

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Data_Science_With_GenAI
   ```

2. **Install required packages:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn flask jupyter plotly memory-profiler graphviz
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Start with Python Basics:**
   - Open [`Python_Basics.ipynb`](Python_Basics.ipynb) to begin your journey

## 📋 Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Basic understanding of programming concepts

## 🛠️ Key Libraries Used

- **Data Analysis:** pandas, numpy
- **Visualization:** matplotlib, seaborn, plotly
- **Machine Learning:** scikit-learn
- **Web Development:** Flask
- **Utilities:** logging, os, memory-profiler

## 🎯 Learning Path

1. **Foundation:** Start with [Python Basics](Python_Basics.ipynb)
2. **Data Handling:** Move to [Data Types](Data_Types_and_Structures.ipynb) and [Functions](Functions.ipynb)
3. **Error Management:** Learn [Exception Handling](Error_handling/files_and_exceptional_handling_assignment.ipynb)
4. **Data Science:** Explore [Data Toolkit](Data_Toolkit/Data_Toolkit.ipynb)
5. **Machine Learning:** Dive into [ML concepts](Machine_Learning/) and [Decision Trees](Machine_Learning/DecisionTree/)
6. **API Development:** Build with [Flask](Restful_API/Restful_API_&_Flask.ipynb)
7. **Advanced Topics:** Explore [Statistics](Statistics/) and specialized implementations

## 🤝 Contributing

Feel free to contribute by:
- Adding new examples
- Improving existing code
- Fixing bugs
- Enhancing documentation

## 📜 License

This project is open source and available under the MIT License.

---

**Happy Learning! 🎓**

*This repository provides a comprehensive foundation for Data Science, Machine Learning, and Python development with practical, hands-on examples.*

