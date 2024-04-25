
# Cyber Threat Detection using Machine Learning

This project implements a cyber threat detection system using machine learning techniques in Python. The system is designed to detect threats in URLs and is developed in PyCharm IDE. It also includes support for running in Jupyter Notebook.

## Introduction

Recent advancements in computer and network technology have increased the importance of cyber security to combat evolving cyber threats. Traditional methods like firewall configurations have proven insufficient against modern intrusion techniques, necessitating innovative approaches for effective security measures. Intrusion Detection Systems (IDS) play a crucial role in identifying and mitigating cyber attacks. However, traditional cyber security methods face challenges such as untrained personnel and limited access to clean data, exacerbating cybercrime.

To address these challenges, this project leverages Artificial Intelligence techniques, particularly Machine Learning, to enhance cyber security through learning-based methods for detecting cyber attacks. The project introduces a novel Binary Grasshopper Optimized Twin Support Vector Machine (BGOTSVM) based security model. This model ranks security features according to their relevance and selects significant features to develop an IDS model. By reducing feature dimensions, this approach improves predictive performance for unidentified tests and lowers computational expenses.

## Requirements

To run this project, you'll need the following Python packages:

- Jupyter
- NumPy
- Pandas
- SciPy
- Matplotlib
- Scikit-learn (version 0.0)
- Flask
- Django (version 3.1.10)
- mysqlclient

Ensure that Python version 3.10.11 is installed on your system.

## Abstract

The difficulty of ensuring cyber-security is steadily growing due to the alarming development in computer connectivity and the sizeable number of applications associated with computers in recent years. The system requires robust defense against the growing number of cyber threats. This project proposes a novel Binary Grasshopper Optimized Twin Support Vector Machine (BGOTSVM) based security model, which first considers the security features ranking according to their relevance before developing an IDS model based on the significant features that have been selected. By lowering the feature dimensions, this approach not only improves predictive performance for unidentified tests but also lowers the model's computational expense. Trials are conducted using four common ML techniques to compare the results to those of the current approaches (Decision Tree, Random Decision Forest, Random Tree, and Artificial Neural Network). The experimental findings of this study confirm that the suggested methods may be used as learning-based models for network intrusion detection and demonstrate that, when used in the real world, they outperform conventional ML techniques.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/vsnsrujana123/cyberThreatDetectionUsingML.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the project:

    - For Jupyter Notebook:

        ```bash
        jupyter notebook
        ```

    - For Django:

        ```bash
        python manage.py runserver
        ```

    - For Flask:

        ```bash
        flask run
        ```

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to adjust the README according to your project structure, additional information, or specific requirements. Let me know if you need further assistance!
