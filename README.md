![Email Inbox](email_inbox.jpg)

## Intelligent Email Classifier using LLaMA

Every day, professionals sift through hundreds of emails—from urgent client requests to promotional offers. It's like trying to find a needle in a digital haystack. But AI can help: by automatically sorting emails, it highlights what matters most.

In this project, you've been tasked with building an **intelligent email assistant** powered by **LLaMA**, capable of classifying incoming emails into three useful categories:

- **Priority** – Urgent or important messages requiring immediate attention  
- **Updates** – Informational or routine notifications  
- **Promotions** – Marketing content, discounts, or newsletters

---

## 📂 The Dataset

You’ll be working with a structured dataset of diverse email examples, including business communications, system notifications, and marketing messages.

### `email_categories_data.csv`

| Column            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `email_id`        | A unique identifier for each email in the dataset                          |
| `email_content`   | Full email text, including subject and body. Format: `"Subject"` then body |
| `expected_category` | The true label of the email: `Priority`, `Updates`, or `Promotions`       |

Use this labeled data to train and evaluate your LLaMA-powered classification model.

---

💡 Stay tuned for further instructions on preprocessing, model usage, and evaluation!
