Email Spam Detection using Bayes Theorem
Project Overview
This project implements a simple Email Spam Detection system using Bayes' Theorem. The goal of the project is to determine the probability that an email is spam given the occurrence of specific words (e.g., "lottery") in the email content.

Problem Statement:
Given an email, if it contains certain words like "lottery", "win", or "prize", the system calculates the probability that the email is spam using Bayes' Theorem.

Methodology
The Bayes' Theorem is used to update the probability of an email being spam after observing the presence of specific words in the email. The formula is as follows:

𝑃
(
Spam
∣
"lottery"
)
=
𝑃
(
"lottery"
∣
Spam
)
×
𝑃
(
Spam
)
𝑃
(
"lottery"
)
P(Spam∣"lottery")= 
P("lottery")
P("lottery"∣Spam)×P(Spam)
​
 
Where:

𝑃
(
Spam
)
P(Spam) is the prior probability of an email being spam.

𝑃
(
"lottery"
∣
Spam
)
P("lottery"∣Spam) is the likelihood of the word "lottery" appearing in a spam email.

𝑃
(
"lottery"
)
P("lottery") is the total probability of encountering the word "lottery" in any email.

Project Requirements
Python 3.x

Google Colab (for running the notebook)

GitHub for version control and hosting the project

Code Explanation
Input Data: The project assumes certain prior probabilities for spam and normal emails, and the likelihood of the word "lottery" appearing in spam and normal emails.

Bayes' Theorem Calculation: Using the given input data, Bayes' Theorem is applied to calculate the probability of an email being spam after observing the word "lottery".

Output: The result is the probability that the email is spam, based on the occurrence of specific words.

Results
Based on the provided probabilities:

If the word "lottery" appears in an email, the probability that it is spam is approximately 81.8%.

How to Run the Code
Clone the repository:

bash
Copy
Edit
git clone https://github.com/YourUsername/Email-Spam-Detection.git
Open the Spam-Detection.ipynb notebook in Google Colab or Jupyter Notebook.

Run the cells to perform the Bayes' Theorem calculation for spam detection.

You can modify the input data (prior probabilities and likelihood values) to observe how different conditions affect the spam detection result.

Contributing
Feel free to fork this repository, make improvements, and contribute to enhancing the email spam detection system.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Notes:
Replace YourUsername with your GitHub username in the repository URL.

You can further enhance this project by incorporating more complex machine learning techniques and datasets to improve spam detection accuracy.
