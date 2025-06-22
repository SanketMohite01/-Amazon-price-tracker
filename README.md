# -Amazon-price-tracker

This is a Python script that automatically tracks the price of a product on Amazon and notifies you via email when the price drops below a specified target.

## 🚀 Features

- Scrapes the latest price from an Amazon product page
- Sends email alerts when the price falls below your set limit
- Easy configuration using a `.env` file

## 🛠️ Technologies Used

- Python 3
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) – for parsing HTML
- [Requests](https://docs.python-requests.org/) – for fetching webpage content
- [smtplib](https://docs.python.org/3/library/smtplib.html) – for sending emails
- [dotenv](https://pypi.org/project/python-dotenv/) – for handling environment variables

## 🔧 Setup Instructions

### 1. Clone the Repository

git clone https://github.com/your-username/amazon-price-tracker.git
cd amazon-price-tracker

#2. Install Dependencies

pip install -r requirements.txt

#3.Create a .env File

EMAIL=your_email@example.com
PASSWORD=your_password


4. Update the Product URL

  url = "https://www.amazon.in/your-product-url"
target_price = 999.99  # your target price here

6. Run the Script
   
   python main.py
   
