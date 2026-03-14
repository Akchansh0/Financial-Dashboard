P&L Dashboard — Small Business Financial Overview
A clean, dark-themed Profit & Loss dashboard built for small businesses.
No login. No software. Just open the file in any browser and it works.

What's Inside

6 KPI cards — Revenue, Expenses, Gross Profit, Net Profit, Gross Margin, Profit Margin
Revenue vs Expenses trend — monthly line chart with hover tooltips
4 smart insight cards — best month, worst month, expense peak, revenue dip
Revenue by source — donut chart (Product Sales, Service Revenue, Other Income)
Gross Profit by month — bar chart
Expense breakdown — visual bar list with cost alert


How to Use

Download index.html
Open it in any browser (Chrome, Firefox, Safari, Edge)
Replace the sample data in the <script> section at the bottom of the file with your own numbers
Save and refresh — done

No installation. No dependencies to install. Works completely offline.

Customisation
All data lives in three simple arrays near the bottom of the file:
jsconst REV = [38243, 28005, ...]; // Your monthly revenue figures
const EXP = [19215, 16134, ...]; // Your monthly expense figures
const GP  = [19028, 11871, ...]; // Your monthly gross profit figures
Update the KPI cards and insight panels in the HTML to match your numbers.
The color system is fully controlled by CSS variables at the top — easy to retheme.

Tech Stack

Pure HTML, CSS, JavaScript
Chart.js 4.4 — loaded via CDN
DM Sans + DM Mono — loaded via Google Fonts
Zero frameworks. Zero build steps.


License
Personal and commercial use allowed.
You may use this dashboard for your own business or for clients.
Please do not resell or redistribute the source file as a template product.

About
Built as a cleaner alternative to cluttered Excel dashboards.
Designed for founders, freelancers, and small business owners who want
a fast, readable snapshot of their financials — without the spreadsheet overhead.
