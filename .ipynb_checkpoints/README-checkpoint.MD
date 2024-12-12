This script processes web server access logs to extract and analyze various metrics.

Dataset:
The dataset used in this script is available at:
https://www.kaggle.com/datasets/eliasdabbas/web-server-access-logs/data


Functionality:
- Reads the web server access logs from a specified file.
- Parses each log entry to extract relevant information such as IP address, timestamp, request method, URL, HTTP status code, and user agent.
- Analyzes the extracted data to compute metrics such as the number of requests per IP address, the most requested URLs, and the distribution of HTTP status codes.
- Generates summary statistics and visualizations to provide insights into the web server traffic.

Usage:
1. Ensure the dataset is downloaded from the provided link.
2. Update the file path in the script to point to the downloaded dataset.
3. Run the script to process the logs and generate the analysis.

Dependencies:
- pandas
- matplotlib
- seaborn

Example:
    python process_logs.py

Author:
[Your Name]

Date:
[Date]

