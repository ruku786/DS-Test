# DS-Test
Problem Statement: Data Scraping and Supplier Cohort Analysis for Aerospace CNC Manufacturing

Step 1: Data Collection via Web Scraping
1.1. Identify and Select Websites
Potential Sources:
ThomasNet: A well-known directory for industrial suppliers.
1.2. Web Scraping Tool Development
Tools to Use:
Python Libraries:
BeautifulSoup for parsing HTML and extracting data.
Scrapy for managing complex web scraping tasks.
Selenium if dynamic content loading is involved.
Data Points to Collect:
Supplier Name
Location (City, State, Country)
Aerospace certifications (e.g., AS9100)
Materials they specialize in (e.g., Titanium, Aluminum)
Maximum part size and complexity they can handle
Available machine types and capabilities (e.g., 5-axis milling, precision grinding)
Historical performance data (e.g., delivery times, defect rates)
1.3. Data Cleaning and Structuring
Data Format:
Store the scraped data in a structured format such as CSV or JSON.
Clean the data by handling missing values, removing duplicates, and standardizing the format (e.g., standardizing location names and material types).
Step 2: Cohort Analysis of Supplier Capabilities
2.1. Define Criteria for Cohort Creation
Cohort Criteria Examples:
Material Expertise:
Suppliers specializing in high-strength alloys like Titanium or Inconel.
Manufacturing Capabilities:
Suppliers with advanced machining capabilities like 5-axis CNC machining.
Certification Levels:
Suppliers with aerospace certifications like AS9100 or ISO 9001.
2.2. Develop Metrics for Evaluation
Evaluation Metrics Examples:
Range of Part Sizes:
Measure the maximum and minimum part sizes each supplier can handle.
Complexity of Parts:
Evaluate the complexity of parts they can produce (e.g., multi-axis milling capabilities).
Historical Reliability:
Analyze data on on-time delivery and defect rates to assess supplier reliability.
2.3. Visualization and Trend Analysis
Tools:
Python Libraries:
Matplotlib or Seaborn for creating plots.
Pandas for data manipulation and cohort analysis.
Plotly for interactive visualizations.
Visualizations:
Trends in supplier capabilities over time.
Growth or decline in specific cohorts.
Comparison of cohorts based on historical reliability.
