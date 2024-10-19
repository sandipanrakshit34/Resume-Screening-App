# Resume Screening App
<center> <img src = "https://github.com/sandipanrakshit34/Resume-Screening-App/blob/main/feature1.adf306a03abd.png" width = 100%>
## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Architecture](#architecture)
- [Data Flow](#data-flow)
- [Model Training](#model-training)
- [Performance Metrics](#performance-metrics)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The **Resume Screening App** is a machine learning application designed to streamline the hiring process by analyzing and scoring resumes based on their alignment with job requirements. The app uses advanced Natural Language Processing (NLP) techniques and machine learning algorithms to provide users with valuable insights into their resumes, helping them improve their chances of landing a job.

## Features

- **Resume Upload**: Users can upload their resumes in various formats (PDF, DOCX, TXT) for analysis.

- **Data Cleaning**: Automatically cleans the uploaded resumes by removing unnecessary characters, links, and formatting to ensure effective text analysis.

- **Resume Scoring**: Assigns a score to each resume based on relevance to the job description, evaluating the presence of essential skills, experiences, and keywords.

- **Category Prediction**: Classifies resumes into predefined job categories (e.g., Data Scientist, Software Engineer, etc.) to guide users on where they fit best.

- **Data Visualization**: Visualizes resume submissions and scores using interactive plots and charts, providing users with insights into their submission landscape.

- **Text Vectorization**: Transforms resume text into numerical representations using TF-IDF vectorization, allowing effective training of machine learning models.

- **Model Training**: Implements a K-Nearest Neighbors (KNN) classifier for predicting resume categories, achieving high accuracy based on historical data.

- **User Feedback**: Provides actionable feedback and suggestions for improving resume scores.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - NLTK (Natural Language Toolkit)
  - Scikit-learn
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Frameworks**: Flask (for web application)
- **Environment**: Jupyter Notebook, IDE (VS Code or PyCharm)
## Author

- [@sandipanrakshit34](https://github.com/sandipanrakshit34)

##

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python (version 3.6 or higher)
- Pip (Python package installer)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sandipanrakshit34/resume-screening-app.git
   cd resume-screening-app
