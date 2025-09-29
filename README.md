# Call-History-Analyzer
A powerful, client-side web tool to analyze any CSV call log. Features intelligent column mapping, dynamic filters, and interactive visualizations with Chart.js. Gain insights instantly and securely, right in your browser.

Universal Call History Analyzer
A Standalone Business Intelligence Tool for Call Data
The Universal Call History Analyzer is a powerful, client-side business intelligence tool designed to transform raw call log data from any CSV source into actionable insights. Built with modern JavaScript, this tool empowers business analysts, team leads, and managers to analyze call performance, identify trends, and make data-driven decisions without any backend infrastructure or data privacy concerns.

Since the entire application runs in the browser, no sensitive call data is ever uploaded to a server, ensuring 100% privacy and security.

**Live Demo & Screenshot**
[demo link here coming soon]

![screenshot1](https://github.com/user-attachments/assets/c3e7ed71-acd8-4ea1-bb84-4b704e0d35d0)

**Key Features**
This tool was engineered to be both powerful and user-friendly, providing a seamless analysis experience.

📄 Dynamic CSV Parsing: Upload any call history CSV file. The robust PapaParse library handles the parsing, ensuring compatibility with various formats and delimiters.

🧠 Intelligent Column Mapping: The system automatically detects and suggests mappings for common columns like Date, Duration, Direction, and User. Users can easily override these suggestions via an intuitive UI to handle any CSV structure.

🔍 Powerful & Granular Filtering:
Global Filters: Instantly narrow down the entire dataset by including or excluding rows containing specific keywords.
Column-Specific Filters: Dynamically generated checkbox filters for categorical data (e.g., call Direction), allowing for precise data segmentation.

📊 In-Depth Analytics & Aggregation: The tool automatically calculates key performance indicators (KPIs) from the filtered data, including:
Total call volume
Average, minimum, and maximum call durations
Counts of unique callers and recipients
Per-user call metrics
Breakdowns by call direction (Inbound vs. Outbound)
📈 Interactive Data Visualizations: Powered by Chart.js, the dashboard brings data to life with:
Bar Charts: Compare call volumes per user or agent.
Pie Charts: Understand the distribution of call directions.
Line Charts: Track call volume trends over time.

🔒 100% Client-Side & Secure: All file processing, filtering, and analysis happen exclusively in the user's browser. This makes the tool incredibly fast and guarantees that sensitive data remains private and secure.

**Tech Stack**
This project was built from the ground up using modern web technologies with zero reliance on backend frameworks.
Core: HTML5, CSS3 (Flexbox & Grid Layout), Modern JavaScript (ES6+)
CSV Parsing: PapaParse - For fast and reliable in-browser CSV parsing.
Data Visualization: Chart.js - For creating beautiful, responsive, and interactive charts.
Date/Time Manipulation: date-fns - A lightweight and modern library for reliable date parsing and formatting.

**How to Use**
As a standalone tool, getting started is incredibly simple:
Download the analyzer.html file from this repository.
Open the file in any modern web browser (like Chrome, Firefox, or Edge).
Follow the on-screen steps:
Upload your CSV call log.
Map the columns to their correct roles.
Filter the data using the sidebar controls.
Analyze the results on the dashboard!

**Project Purpose & Business Application**
The goal of this project was to create a practical business analysis tool that solves a common problem: making sense of raw data exports. Many phone systems and CRMs export data in slightly different formats, making it difficult for non-technical users to analyze.

This tool serves as a universal adapter, empowering anyone to:
Quickly assess agent or team performance.
Identify peak call times and trends.
Understand the balance between inbound and outbound call activity.
Gain valuable business insights without needing complex spreadsheet formulas or dedicated BI software.
