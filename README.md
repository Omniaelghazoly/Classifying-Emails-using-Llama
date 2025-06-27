# Classifying-Emails-using-Llama
This project is part of Llama Fundamental Track on DataCamp

Every day, professionals wade through hundreds of emails, from urgent client requests to promotional offers. It's like trying to find important messages in a digital ocean. But AI can help you stay afloat by automatically sorting emails to highlight what matters most.

You've been asked to build an intelligent email assistant using Llama, to help users automatically classify their incoming emails. Your system will identify which emails need immediate attention, which are regular updates, and which are promotions that can wait or be archived.

The Data
You'll work with a dataset of various email examples, ranging from urgent business communications to promotional offers. Here's a peek at what you'll be working with:

email_categories_data.csv
Column | Description | |--------|-------------| | email_id | A unique identifier for each email in the dataset. | | email_content | The full email text including subject line and body. Each email follows a format of "Subject" followed by the message content on a new line. | | expected_category | The correct classification of the email: Priority, Updates, or Promotions. This will be used to validate your model's performance. |
