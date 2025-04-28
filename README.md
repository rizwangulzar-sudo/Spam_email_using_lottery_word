# Email Spam Detection using Bayes' Theorem

## 🧠 **Project Overview**

This project implements an **Email Spam Detection** system using **Bayes' Theorem** to classify emails as **spam** or **normal** based on the occurrence of certain keywords. For example, if an email contains the word "lottery," the system calculates the probability of it being spam.

---

## 📊 **Problem Statement**

The problem is to determine whether an email is **spam** based on the occurrence of specific words in the email content. For this project, the word "lottery" is used as an indicator, and Bayes' Theorem is applied to calculate the probability of an email being spam given the presence of this word.

---

## 📐 **Methodology**

We use **Bayes' Theorem** to calculate the conditional probability:

\[
P(\text{Spam} | \text{"lottery"}) = \frac{P(\text{"lottery"} | \text{Spam}) \times P(\text{Spam})}{P(\text{"lottery"})}
\]

Where:
- \(P(\text{Spam})\) is the prior probability of an email being spam.
- \(P(\text{"lottery"} | \text{Spam})\) is the likelihood of the word "lottery" appearing in a spam email.
- \(P(\text{"lottery"})\) is the total probability of encountering the word "lottery" in any email.

By plugging in the relevant values, Bayes' Theorem helps us calculate the probability of an email being spam based on the observed word.

---

## 🛠️ **Project Requirements**

- Python 3.x
- Google Colab (or Jupyter Notebook)
- GitHub for version control and hosting the project

---

## 💻 **Code Explanation**

### 1. **Input Data**:
   - The project assumes prior probabilities for spam and normal emails.
   - Likelihood values for the word "lottery" in spam and normal emails are given.

### 2. **Bayes' Theorem Calculation**:
   Using the input data, Bayes' Theorem is applied to calculate the probability of an email being spam given the occurrence of the word "lottery."

### 3. **Output**:
   The output is the probability that the email is spam, based on the presence of specific words.

---

## 📈 **Results**

- If the word "lottery" appears in an email, the probability of it being **spam** is approximately **81.8%** based on the given prior and likelihood values.

---

## 🚀 **How to Run the Code**

1. **Clone the repository**:

   ```bash
   git clone https://github.com/YourUsername/Email-Spam-Detection.git
