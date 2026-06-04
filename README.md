#🚚 LogiTrack: Supply Chain Bottleneck & Delivery Performance Optimization

An end-to-end data analytics project engineered to identify shipping bottlenecks, assess logistics carrier reliability, and surface processing lags across regional distribution centers using Python (Pandas) and SQL (CTEs & Window Functions).

---

#📊 Business Problem
A multinational logistics provider is experiencing inconsistent delivery times and unexplained spikes in transit fuel costs. This project cleanses irregular system-generated transactional records and applies advanced analytics to uncover exactly which routes, distribution centers, and shipping carriers are driving 80% of operational inefficiencies.

#🛠️ Data Infrastructure & Tech Stack
* Cloud Environment: Google Colab Ecosystem
* Data Engineering & Wrangling: Python 3, Pandas, NumPy
* Relational Database & Analytics:** SQLite3 (Using Common Table Expressions, Window Functions, and Multi-Table Inner Joins)
* Data Visualization: Matplotlib & Seaborn

#🗄️ Relational Database Architecture
The analytical engine joins three relational database objects:
1. "orders": Core transaction ledger detailing shipping statuses, timestamps, and actual fuel expenses.
2. "routes": Operational route configurations containing calculated distances and baselines for estimated transit hours.
3. "distribution_centers": Facilities master tracking real-time layout capacity thresholds ('Optimal', 'Near Capacity', 'Overcapacity').

#🔍 Core Analytical Insights Featured
* Carrier Reliability Indexes: Utilizing SQL "RANK() OVER" partitioned by delivery hour variances to rank performance.
* Facility Processing Latency: Mapping structural delays back to overcapacity distribution centers.
* Financial Anomaly Detection: Resolving systematic negative value pipeline errors via Pandas cleansing.

---

#🚀 How to Explore the Analysis
---
Simply open the "LogiTrack_Supply_Chain_Project.ipynb" file inside this repository to review the fully executed code blocks, mathematical cleaning routines, interactive data frames, and graphical diagnostic charts.
