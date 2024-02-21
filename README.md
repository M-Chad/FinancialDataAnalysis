# FinancialDataAnalysis

This project is a comprehensive financial data analysis platform built on AWS, leveraging a serverless architecture for processing and analyzing financial market data. It utilizes Python for ETL processes, PostgreSQL for data storage, and a static website hosted on Amazon S3 for visualization. The core functionality centers around fetching real-time financial data using the Alpha Vantage API, calculating key financial indicators such as moving averages and the Relative Strength Index (RSI), and presenting this data through an interactive web interface.

Key Features:
Real-time Data Fetching: Utilizes AWS Lambda to fetch real-time financial data from Alpha Vantage API, supporting various financial instruments.
Data Processing & Analysis: Implements ETL processes in Python to calculate moving averages and RSI, key indicators for financial analysis.
Serverless Data Storage: Leverages Amazon RDS (PostgreSQL) for efficient data storage and retrieval, ensuring scalability and cost-effectiveness.
Interactive Data Visualization: A static website hosted on Amazon S3 displays the calculated financial indicators, offering users insights into market trends.
Infrastructure as Code (IaC): Uses Terraform to define and deploy the AWS infrastructure, ensuring reproducibility and ease of deployment.
Containerization & Orchestration: Incorporates Docker for containerization and AWS services for orchestration, showcasing modern deployment practices.
Cost-Effective: Designed within AWS Free Tier limits to minimize operational costs while maintaining scalability and performance.
Technologies Used:

AWS Services: Lambda, RDS (PostgreSQL), S3, CloudWatch
Programming Languages & Tools: Python, SQL, Terraform, Docker
APIs: Alpha Vantage for financial data
Frontend: HTML, CSS, JavaScript (for the static site)
Architecture Overview:
The platform adopts a serverless architecture, with AWS Lambda functions handling data fetching, processing, and loading tasks. Data is stored in a PostgreSQL database hosted on Amazon RDS, while the static website on Amazon S3 serves as the presentation layer. Terraform scripts define the infrastructure, ensuring that the entire setup can be easily replicated or modified.

Project Goals:
To provide an easy-to-use platform for financial market analysis.
To demonstrate the practical application of AWS in building serverless data pipelines.
To showcase the integration of various technologies (Python, SQL, AWS, Docker) in a real-world project.
How to Use:
Setup AWS and Terraform: Follow the setup instructions to initialize your AWS environment and deploy the infrastructure using Terraform.
Data Processing: The platform automatically fetches and processes data at scheduled intervals. Users can modify the Lambda function for different financial instruments or indicators.
Viewing Data: Access the static website hosted on S3 for visualizations of moving averages and RSI, providing insights into market behavior.
Contributing:
Contributions are welcome! Whether it's adding new features, improving the documentation, or reporting issues, your input is highly valued. Please see the contributing guide for more details.
