# CRM-Software-Implementation

## Overview
This project implements a basic Customer Relationship Management (CRM) system to manage customer information, track interactions, and generate reports. The project demonstrates how a CRM system can improve customer relationship management and increase operational efficiency.

## Table of Contents

1. [Key Features](#key-features)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Setup](#setup)
5. [Usage](#usage)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact Information](#contact-information)

## Key Features ✨

- **Customer Data Management:** Store and manage customer information.
- **Interaction Tracking:** Keep track of interactions with customers.
- **Sales and Marketing Integration:** Integrate with sales and marketing tools to streamline workflows.
- **Analytics and Reporting:** Generate reports and analytics to gain insights into customer behavior and sales performance.

## Dataset 📊

The project uses a simulated customer dataset with the following columns:
- `customer_id`: Unique identifier for each customer
- `name`: Customer's name
- `email`: Customer's email address
- `phone`: Customer's phone number
- `company`: Customer's associated company
- `last_contacted`: The last date the customer was contacted

Sample data:
```csv
customer_id,name,email,phone,company,last_contacted
1,Customer_1,customer1@example.com,1234567891,Vandelay Industries,2023-04-10
2,Customer_2,customer2@example.com,1234567892,Acme Corp,2023-06-27
3,Customer_3,customer3@example.com,1234567893,Hooli,2023-01-30
4,Customer_4,customer4@example.com,1234567894,Hooli,2023-05-28
5,Customer_5,customer5@example.com,1234567895,Hooli,2023-05-28
```

## Project Structure 📂

```
crm-system/
├── src/
│   ├── crm.py               # Main script for CRM operations
│   ├── data_loader.py       # Script to load and preprocess data
│   ├── reports.py           # Script to generate reports
│   └── requirements.txt     # List of Python libraries needed
├── data/
│   └── customers.csv        # Sample customer data
├── README.md                # Project documentation
└── .gitignore               # Ignored files and directories
```

## Setup 🚀

1. **Clone the repository:** 
   ```sh
   git clone <your-github-repo-url>
   cd crm-system
   ```
2. **Create a virtual environment:** 
   ```sh
   python -m venv venv
   ```
3. **Activate the virtual environment:**
   ```sh
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. **Install dependencies:**
   ```sh
   pip install -r src/requirements.txt
   ```

## Usage

1. **Load Customer Data:**
   ```sh
   python src/data_loader.py
   ```
   This script loads the customer data from `customers.csv` and prints a sample of the data.

2. **Run CRM Operations:**
   ```sh
   python src/crm.py
   ```
   This script performs example CRM operations such as retrieving customer info and updating the last contacted date.

3. **Generate Reports:**
   ```sh
   python src/reports.py
   ```
   This script generates a report showing the number of customers per company and saves it as an image in the `reports/` directory.

## Results 🏆

### Sample Customer Data
When you run the `data_loader.py` script, you will see a sample of the customer data:
```
Sample Customer Data:
   customer_id        name                  email       phone              company last_contacted
0            1  Customer_1  customer1@example.com  1234567891  Vandelay Industries     2023-04-10
1            2  Customer_2  customer2@example.com  1234567892            Acme Corp     2023-06-27
2            3  Customer_3  customer3@example.com  1234567893                Hooli     2023-01-30
3            4  Customer_4  customer4@example.com  1234567894                Hooli     2023-05-28
4            5  Customer_5  customer5@example.com  1234567895                Hooli     2023-05-28
```

### Example CRM Operations
When you run the `crm.py` script, you will see example operations such as retrieving customer info and updating the last contacted date:
```
Get Customer Info:
{'customer_id': 1, 'name': 'Customer_1', 'email': 'customer1@example.com', 'phone': '1234567891', 'company': 'Vandelay Industries', 'last_contacted': '2023-04-10'}

Update Last Contacted Date:
{'customer_id': 1, 'name': 'Customer_1', 'email': 'customer1@example.com', 'phone': '1234567891', 'company': 'Vandelay Industries', 'last_contacted': '2023-07-04'}
```

### Reports
When you run the `reports.py` script, it generates a report showing the number of customers per company and saves it as an image `customers_per_company.png` in the `reports/` directory.

![Customers per Company](https://raw.githubusercontent.com/Nick9695/CRM-Software-Implementation/main/customers_per_company.png)

## Conclusion

This project demonstrates a basic CRM system with customer data management, interaction tracking, and report generation. The system effectively showcases how CRM tools can improve customer relationship management and operational efficiency.

## Contributing 🤝

Feel free to fork this repository, experiment, and contribute your improvements! Pull requests are welcome.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact Information 📧
![Screenshot 2023-12-11 224350](https://github.com/Nick9695/Personality-Quiz-Assignment/assets/148968130/3c82c2b7-876d-447d-b149-dcd2fddedf23)
**Nikhil Raju Gadekar**


- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/nikhil-gadekar-1951a8245)
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nick9695)
- [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gernikhilgadekar@gmail.com)
```
