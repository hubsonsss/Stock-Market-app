# 📊 Advanced Stock Market Analytics Application
# Authors:
- Hubert Sobociński
- Zuzanna Sieńko
## 📌 Abstract

The Stock Market Analytics Application constitutes a sophisticated, real-time Android platform designed to facilitate the retrieval, processing, and visualization of equity market data. Developed in Java, the system seamlessly integrates with external stock exchange APIs to ensure the provision of high-fidelity financial information. Through dynamic charting and historical trend analysis, users can derive actionable insights and make informed investment decisions.

## 🚀 Key Functionalities

📈 Live Market Data Acquisition – Establishes API connections to fetch and update stock prices in real time.

🔍 Corporate Securities Lookup – Enables users to query publicly traded companies and retrieve financial metrics.

📊 Historical Performance Analysis – Provides longitudinal stock data visualization for trend assessment.

📉 Dynamic Graphical Representation – Leverages advanced charting libraries to illustrate price fluctuations.

📅 Trading Session Validation – Implements an algorithmic mechanism to adjust queries to permissible trading days.

## 🛠️ Technical Stack

☕ Java – Primary programming language for application logic.

🔄 Retrofit – Framework for structured API interaction and asynchronous data retrieval.

📜 Gson – Library employed for efficient JSON parsing and data serialization.

📊 MPAndroidChart – Visualization toolset for graphical stock market representation.

📱 Android Jetpack – Utilized for lifecycle management and UI architecture.

## 🔗 API Integration & Data Handling

The system interfaces with the Tiingo Stock Market API to acquire real-time stock valuations and corporate metadata. The Service.java module orchestrates API requests while ensuring robustness through comprehensive error handling and logging mechanisms.

## 📂 Codebase Overview

### 📡 Service.java

Defines RESTful API endpoints and executes data acquisition routines via Retrofit.

Implements fetchCompanyStockData() for structured financial data retrieval.

Enforces network resilience protocols and logs anomalies.

### 📆 DateValidator.java

Employs heuristic algorithms to align requested dates with valid trading periods.

Implements constraints to preclude future date selection anomalies.

### 🕒 LocalDateDeserializer.java

Decodes temporal JSON representations into standardized date objects.

Accommodates diverse timestamp formats for enhanced API compatibility.

## 📸 Illustrations
![476162822_587424687604090_2344051250062288457_n](https://github.com/user-attachments/assets/70571c50-25bb-4261-b6e7-fa7e39420239)
![475857870_999029402091548_542346319747179093_n](https://github.com/user-attachments/assets/2f7516f0-12c7-4808-9337-b9def3e4728e)
![475728215_508841525150264_2145937572363024625_n](https://github.com/user-attachments/assets/c64e99a8-5588-4739-9977-a6e95e00a2fa)

