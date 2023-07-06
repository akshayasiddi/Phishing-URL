# Phishing URL Detection
This project aims to develop a Python-based system for real-time detection of phishing URLs. By leveraging machine learning algorithms, the system can distinguish between legitimate and phishing URLs with a high level of accuracy. The project includes feature extraction to analyze URL characteristics and identify potential indicators of phishing. Additionally, a user-friendly interface with a pop-up notification box is integrated to provide instant feedback on URL legitimacy.

# Usage
1. Ensure that Python 3.x is installed on your system.

Install the required dependencies by running the following command:

``` pip install -r requirements.txt ```

2. Prepare the datasets:

    -   Place the legitimate-urls.csv file in the same directory as classifier.py.
    -    Place the phishing-urls.csv file in the same directory as classifier.py.
    
3. Run the classifier:
   
``` python classifier.py ```

The program will display the user-friendly interface with a pop-up notification box.
Enter a URL in the provided input field, and the system will analyze the URL and provide instant feedback on its legitimacy.
