# BI-BizAnalytics Cameroon
A BI Web Application

General Overview:
Background / Problem: 
Small businesses in Cameroon — particularly informal shops and vendors operating through WhatsApp, Facebook, and physical storefronts in cities like Buea — manage their sales records manually in notebooks and spreadsheets. This lack of data infrastructure means business owners have no visibility into their sales trends, cannot identify their best-performing products, and make restocking decisions based on intuition rather than evidence. The result is persistent stockouts, overstocking of slow-moving items, and missed revenue opportunities.

Objective: 
The aim of this project is to build BizAnalytics — a full-stack web application that allows small business owners to upload their sales data, view an interactive analytics dashboard, receive machine learning-powered demand predictions for every product, and access an AI-driven business advisory chatbot. The system is designed to be accessible to business owners without any technical background.
Methods: The project was developed across five structured phases following SWEBOK Software Construction principles. The backend was built using Python and Flask, with Pandas handling data processing and Scikit-learn's Random Forest 
Regressor serving as the demand prediction model. The frontend was constructed using HTML, CSS, JavaScript, and Chart.js for visualisations. User authentication was implemented with Flask sessions, and the advisory module was powered by the Anthropic Claude API
Key Results: 
The project delivered a fully functional, locally hosted web application with all five core modules operating correctly: file upload and data cleaning, sales analytics dashboard with ten interactive charts, Random Forest demand prediction with restock advice, an AI-powered advisory chatbot, and a manual sales recording interface. All backend endpoints were tested and passed. The application was deployed to Render.com, where all pages functioned correctly within a session. A persistent data challenge on Render's free tier was identified and documented, and the application currently runs optimally on the local Flask environment. But after persisting, I was able to deploy the backend with Railway and the frontend with Netlify.

Conclusion / Implication: 
BizAnalytics demonstrates that SWEBOK's Software Construction principles, when applied systematically, produce a modular, testable, and extensible system that addresses a genuine problem faced by small businesses in Cameroon. With a clear roadmap for cloud deployment and future enhancements, the system represents a solid foundation for a production-ready business intelligence platform.

Objectives:
The specific objectives of this project are:
•	To build a web application where business owners can upload their sales data in CSV or Excel format and receive immediate feedback on data quality and structure.
•	To develop an analytics dashboard displaying ten interactive charts covering revenue trends, top products, sales channels, customer behaviour, and demographic breakdowns.
•	To develop and integrate a machine learning model that predicts product demand and generates restock advice categorised as High, Moderate, Low, or Very Low.
•	To implement an AI-powered business advisory chatbot using the Anthropic Claude API that can answer natural language questions about the uploaded sales data.
•	To apply proper software construction principles across all five SWEBOK Knowledge Areas throughout the development process.
•	To deploy the application using a Docker-based pipeline and document the deployment experience, including challenges encountered.
•	To implement a manual transaction recording module allowing business owners without digital sales records to begin capturing data immediately.



