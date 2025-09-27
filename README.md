<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Md Sarwar Jahan - Data Analyst & Economist</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f9fafb;
            color: #1f2937;
        }
        .section-title {
            font-size: 2rem;
            font-weight: bold;
            color: #1e40af;
            margin-bottom: 1rem;
        }
        .card {
            background-color: #ffffff;
            border-radius: 0.5rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
            margin-bottom: 1.5rem;
        }
        .badge {
            display: inline-block;
            padding: 0.5rem 1rem;
            margin: 0.25rem;
            border-radius: 9999px;
            background-color: #e0e7ff;
            color: #4338ca;
            font-size: 0.875rem;
        }
        a {
            color: #2563eb;
            text-decoration: none;
            transition: color 0.2s;
        }
        a:hover {
            color: #1e40af;
            text-decoration: underline;
        }
    </style>
</head>
<body class="max-w-4xl mx-auto p-6">
    <!-- Header Section -->
    <header class="text-center mb-12">
        <img src="https://via.placeholder.com/1200x300?text=Data+Analyst+%26+Economist" alt="Profile Banner" class="w-full h-48 object-cover rounded-lg mb-4">
        <h1 class="text-4xl font-bold text-gray-800">Md Sarwar Jahan</h1>
        <p class="text-lg text-gray-600 mt-2">Data Analyst | Economist | Passionate about Data-Driven Insights</p>
        <div class="flex justify-center space-x-4 mt-4">
            <a href="https://www.linkedin.com/in/jahan-md-sarwar" target="_blank">
                <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin" alt="LinkedIn">
            </a>
            <a href="https://github.com/md-sarwar-jahan" target="_blank">
                <img src="https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github" alt="GitHub">
            </a>
        </div>
    </header>

    <!-- Skills Section -->
    <section class="mb-12">
        <h2 class="section-title">Skills</h2>
        <div class="card">
            <ul class="list-disc list-inside space-y-2">
                <li><strong>Programming & Tools</strong>: Python (Pandas, NumPy, Matplotlib, Seaborn), MySQL, PostgreSQL, Power BI, Advanced Excel</li>
                <li><strong>Data Analysis</strong>: Data Cleaning, Exploratory Data Analysis (EDA), Visualization, Machine Learning Basics</li>
                <li><strong>Domains</strong>: E-commerce Analytics, Economic Modeling, Sales Forecasting, Customer Insights</li>
                <li><strong>Soft Skills</strong>: Problem-Solving, Research, Thesis Writing, Creative Thinking</li>
            </ul>
            <div class="mt-4">
                <img src="https://skillicons.dev/icons?i=python,mysql,postgresql,excel,powerbi,git,github" alt="Skills Icons">
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section class="mb-12">
        <h2 class="section-title">Education</h2>
        <div class="card">
            <h3 class="text-xl font-semibold">MSc in Economics</h3>
            <p class="text-gray-600">Johannes Gutenberg University, Mainz | [Graduation Year]</p>
            <p class="mt-2">Thesis: "Trade Effects of Brexit" – Analyzed 82 million data points using Python to evaluate post-Brexit trade impacts.</p>
            <h3 class="text-xl font-semibold mt-4">Certifications</h3>
            <ul class="list-disc list-inside space-y-2">
                <li>IBM Data Science Professional Certificate</li>
                <li>Advanced Excel Course</li>
                <li>Power BI Course</li>
                <li>MySQL Course</li>
            </ul>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="mb-12">
        <h2 class="section-title">Projects</h2>
        <!-- Project 1 -->
        <div class="card">
            <h3 class="text-xl font-semibold">Ecommerce MySQL Analysis Project</h3>
            <img src="https://via.placeholder.com/800x400?text=Ecommerce+MySQL+Project+Screenshot" alt="Ecommerce Project Screenshot" class="w-full h-48 object-cover rounded-lg my-4">
            <p class="mb-2">This project uses MySQL to analyze e-commerce sales data, including data quality checks, business KPIs, customer insights, and sales target analysis. Additionally, I created a Power BI dashboard for bicycle sales visualization.</p>
            <p><strong>Files</strong>:</p>
            <ul class="list-disc list-inside space-y-1">
                <li><code>list_of_orders.csv</code>: Order details like customer names and dates.</li>
                <li><code>order_details.csv</code>: Order items, amounts, and profits.</li>
                <li><code>sales_target.csv</code>: Monthly sales targets by category.</li>
                <li><code>ecommerce_analysis.sql</code>: MySQL script for database setup and analysis.</li>
            </ul>
            <p class="mt-2"><strong>How to Run</strong>:</p>
            <ol class="list-decimal list-inside space-y-1">
                <li>Import the CSV files into MySQL using MySQL Workbench or phpMyAdmin.</li>
                <li>Run the <code>ecommerce_analysis.sql</code> script to set up the database and see the analysis.</li>
            </ol>
            <p class="mt-2"><strong>What This Project Shows</strong>:</p>
            <ul class="list-disc list-inside space-y-1">
                <li><strong>Data Quality</strong>: Checks for duplicates, missing data, and negative amounts.</li>
                <li><strong>Business KPIs</strong>: Calculates total revenue, profit, and average order value.</li>
                <li><strong>Customer Insights</strong>: Finds repeat customers and top cities for sales.</li>
                <li><strong>Sales Targets</strong>: Compares actual sales to targets.</li>
                <li><strong>Retention</strong>: Analyzes customer purchases over time.</li>
            </ul>
            <p class="mt-4"><a href="https://github.com/md-sarwar-jahan/ecommerce-mysql-analysis" target="_blank" class="font-semibold">View Repository</a></p>
        </div>
        <!-- Project 2 -->
        <div class="card">
            <h3 class="text-xl font-semibold">E-commerce Analytics — UK Online Retail (Kaggle)</h3>
            <img src="https://via.placeholder.com/800x400?text=UK+Online+Retail+Project+Screenshot" alt="UK Online Retail Screenshot" class="w-full h-48 object-cover rounded-lg my-4">
            <p class="mb-2">This project analyzes the UK Online Retail dataset from Kaggle, focusing on sales trends, customer behavior, product performance, and return patterns.</p>
            <p><strong>Dataset</strong>: <a href="https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset" target="_blank">Kaggle – E-commerce Data</a></p>
            <p class="mt-2"><strong>Key Insights</strong>:</p>
            <ul class="list-disc list-inside space-y-1">
                <li><strong>Monthly Revenue Trend</strong>: Clear seasonal peaks in November & December (holiday effect).</li>
                <li><strong>Top Products (Pareto 80/20)</strong>: ~20% of SKUs generate ~80% of total revenue.</li>
                <li><strong>Top Countries</strong>: United Kingdom dominates sales; Germany, France, and EIRE follow.</li>
                <li><strong>Customer Concentration</strong>: A small group of customers provides high lifetime value (LTV).</li>
                <li><strong>Basket Size</strong>: Most orders are small, but bulk purchases create long tails.</li>
                <li><strong>RFM Segmentation</strong>: Recency, Frequency, and Monetary scores identify Champions, Loyal, At-Risk customers.</li>
                <li><strong>Returns / Cancellations</strong>: Negative quantities reveal top return-prone products and months.</li>
            </ul>
            <p class="mt-4"><a href="https://github.com/md-sarwar-jahan/Ecommerce_analysis" target="_blank" class="font-semibold">View Repository</a></p>
        </div>
        <!-- Project 3 -->
        <div class="card">
            <h3 class="text-xl font-semibold">Car Pricing Data Analysis</h3>
            <img src="https://via.placeholder.com/800x400?text=Car+Pricing+Project+Screenshot" alt="Car Pricing Project Screenshot" class="w-full h-48 object-cover rounded-lg my-4">
            <p class="mb-2">This Python-based project analyzes used car pricing data, handling data cleaning (e.g., null/missing values, outliers, and inconsistencies) and performing exploratory data analysis.</p>
            <p class="mt-4"><a href="https://github.com/md-sarwar-jahan/Car-pricing-data-analysis" target="_blank" class="font-semibold">View Repository</a></p>
        </div>
        <!-- Project 4 -->
        <div class="card">
            <h3 class="text-xl font-semibold">Laptop Pricing Data Analysis</h3>
            <img src="https://via.placeholder.com/800x400?text=Laptop+Pricing+Project+Screenshot" alt="Laptop Pricing Project Screenshot" class="w-full h-48 object-cover rounded-lg my-4">
            <p class="mb-2">This Python-based project analyzes laptop pricing data, focusing on data cleaning (e.g., null/missing values, outliers, and inconsistencies) and exploratory data analysis.</p>
            <p class="mt-4"><a href="https://github.com/md-sarwar-jahan/Laptop-pricing-data-analysis" target="_blank" class="font-semibold">View Repository</a></p>
        </div>
        <!-- Project 5 -->
        <div class="card">
            <h3 class="text-xl font-semibold">Instagram Clone Data for SQL</h3>
            <img src="https://via.placeholder.com/800x400?text=Instagram+Clone+SQL+Project+Screenshot" alt="Instagram Clone SQL Screenshot" class="w-full h-48 object-cover rounded-lg my-4">
            <p class="mb-2">This project involves SQL-based analysis of an Instagram clone dataset, exploring user interactions and data patterns.</p>
            <p class="mt-4"><a href="https://github.com/md-sarwar-jahan/Instagram-clone-data-for-SQL" target="_blank" class="font-semibold">View Repository</a></p>
        </div>
        <!-- Project 6 -->
        <div class="card">
            <h3 class="text-xl font-semibold">Excel Sales Performance</h3>
            <img src="https://via.placeholder.com/800x400?text=Excel+Sales+Performance+Project+Screenshot" alt="Excel Sales Performance Screenshot" class="w-full h-48 object-cover rounded-lg my-4">
            <p class="mb-2">This project uses advanced Excel techniques to analyze sales performance data, creating visualizations and actionable insights.</p>
            <p class="mt-4"><a href="https://github.com/md-sarwar-jahan/Excel-sales-performance" target="_blank" class="font-semibold">View Repository</a></p>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="mb-12">
        <h2 class="section-title">Contact</h2>
        <div class="card">
            <p>Feel free to reach out for collaborations, questions, or discussions!</p>
            <ul class="list-disc list-inside space-y-2">
                <li><strong>Email</strong>: <a href="mailto:sarwartareq@gmail.com">sarwartareq@gmail.com</a></li>
                <li><strong>LinkedIn</strong>: <a href="https://www.linkedin.com/in/jahan-md-sarwar" target="_blank">Md Sarwar Jahan</a></li>
                <li><strong>GitHub</strong>: <a href="https://github.com/md-sarwar-jahan" target="_blank">md-sarwar-jahan</a></li>
            </ul>
            <p class="mt-4">💬 Ask me about my projects or sales prediction collaborations!</p>
            <p>🤝 Looking for help with my Ecommerce MySQL project.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center text-gray-600 mt-12">
        <p>Thanks for visiting my profile! 🚀 <br> Fun fact: I think I am creative!</p>
    </footer>
</body>
</html>
