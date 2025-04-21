<a name="readme-top"></a>

<!--
!!! IMPORTANT !!!
This README is an example of how you could professionally present your codebase. 
Writing documentation is a crucial part of your work as a professional software developer and cannot be ignored. 

You should modify this file to match your project and remove sections that don't apply.

REQUIRED SECTIONS:
- Table of Contents
- About the Project
  - Built With
  - Live Demo
- Getting Started
- Authors
- Future Features
- Contributing
- Show your support
- Acknowledgements
- License

OPTIONAL SECTIONS:
- FAQ

After you're finished please remove all the comments and instructions!

For more information on the importance of a professional README for your repositories: https://github.com/microverseinc/curriculum-transversal-skills/blob/main/documentation/articles/readme_best_practices.md
-->

<div align="center">

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 Machine Learning Insights into Titanic and Wine Data](#about-project)
  - [🛠 PYTHON](#built-with)
    - [Python: Core programming language.
    - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`.
    - Jupyter Notebook: Analysis conducted in `TitanicWineML.ipynb`]
  - [Key Features](#key-features)
  - Titanic Survival Prediction:
      - Decision tree classification with pruning to optimize performance.
      - KNN classification with optimal neighbor selection and distance metric analysis.
      - Logistic regression for baseline comparison.
   - Wine Quality Analysis:
      - LASSO regression for feature selection in red and white wine datasets.
      - KNN regression compared with linear regression for quality prediction.
   - Comparative Insights:
       - Evaluation of model generalization using cross-validation.
       - Feature importance analysis for wine quality.
- [💻 Getting Started](#getting-started)
    - To get a local copy up and running, follow these steps.
  - [Prerequisites](#prerequisites)
    - Python 3.x
    - Jupyter Notebook
    - Git
  - [Setup](#setup)
     - Clone this repository: `git clone https://github.com/Marlyn-Mayienga/TitanicWineML.git`
  - [Install](#install)
     - Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn statsmodels`
  - [Usage](#usage)
     - Ensure the datasets `titanic3.csv`, `winequality-red.csv`, and `winequality-white.csv` are placed in the project directory.
     - Open `TitanicWineML.ipynb` in Jupyter Notebook.
     - Run all cells to reproduce the analyses, including:
          - Decision tree pruning and evaluation for Titanic survival.
          - KNN optimization for Titanic classification.
          - LASSO and KNN regression for wine quality prediction.
- [👥 Authors](#authors)
   - 👤 **Marlyn Mayienga**

- GitHub: [@Marlyn_Mayienga](https://github.com/Marlyn_Mayienga)
- Twitter: [@Merl_Mayienga](https://twitter.com/M_ayienga)
- LinkedIn: [Marlyn_Mayienga](https://linkedin.com/in/Marlyn_Mayienga)
- [🔭 Future Features](#future-features)
    - Incorporate additional ensemble techniques (e.g., KNN).
    - Explore advanced feature interactions for improved accuracy.
    - Add visualizations of survival patterns by class and embarkation port.

Contributions, issues, and feature requests are welcome!

- [🤝 Contributing](#contributing)
     - Feel free to fork the repository, submit pull requests, or open issues for bugs and feature suggestions. Check the issues page for ongoing tasks

- [⭐️ Show your support](#support)
     - Give a ⭐️ if you like this project! Your support motivates further development.
       
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)
   - This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
