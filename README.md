# WhatsApp-Group-Sentiment-Analysis-
This repository contains a Python script for sentiment analysis of chat data. It utilizes libraries such as pandas for data manipulation and textblob for sentiment analysis.
Installation
1. Clone this repository to your local machine:
git clone https://github.com/your_username/your_repository.git

2. Install the required dependencies:
pip install pandas
pip install textblob

**Usage**

1. Ensure you have a chat log file in a compatible format. The script expects the data to be in the following format:
MM/DD/YY, HH:MM (am/pm) - +XXX XX XXX XXXX: Message text

2. Modify the data_path variable in the script to specify the path to your chat log file.

3. Run the script:
python sentiment_analysis.py

4. After execution, the script will generate a CSV file named Final data.csv containing the analyzed data.
