📊 Business Contact Dashboard for Ministry of Youth
🎯 Project Overview
This interactive web dashboard was developed for the AAST Buisness Adminstration Students Council to present to the Egyptian Ministry of Youth in order to digitally manage and analyze business contacts across key industry sectors. The platform features real-time data visualization, company management tools, and bilingual support (Arabic/English), enabling ministry officials to efficiently track youth business initiatives and generate insights for policy development.
🚀 Live Demo

🌐 Access the Dashboard : https://business-contact-dashboard.streamlit.app/

📋 Features

📈 Analytics & Visualization

Interactive bar charts and donut charts showing company distribution by sector
Real-time statistics and KPIs (Key Performance Indicators)
Visual word cloud of company names for quick insights

🔍 Data Management

Advanced filtering by industry category
Company name search functionality
Comprehensive data table view with export capabilities

✏️ CRUD Operations

➕ Add new companies and categories
🗑️ Delete existing companies and categories
Real-time data updates with session management

📤 Export Capabilities

Export data to Microsoft Word format
Export data to Excel format
Download filtered results as CSV

🌐 Multi-language Support

Category names available in both English and Arabic
Designed for Egyptian market requirements

🏭 Industry Coverage
The dashboard covers key business sectors in Egypt:

Fast Food & Restaurants | الوجبات السريعة والمطاعم
Desserts & Bakery | الحلويات والمخبوزات
Cafés | المقاهي
Games & Entertainment | الألعاب والترفيه
Snacks & Packaged Foods | الوجبات الخفيفة والأطعمة المعبأة
Beverages | المشروبات
Companies & Corporations | شركات

🛠️ Technology Stack

Frontend: Streamlit (Python web framework)
Data Processing: Pandas for data manipulation
Visualizations: Plotly for interactive charts
Word Cloud: WordCloud library for text visualization
Export Functions: python-docx, openpyxl
Deployment: Streamlit Cloud

📊 Dashboard Screenshots
Main Analytics View

Company distribution charts
Category-wise statistics
Interactive filtering options

Data Management Interface

CRUD operations panel
Real-time data updates
Export functionality

🎓 Academic Context
Institution: Arab Academy for Science, Technology & Maritime Transport (AAST)
Target Audience: Egyptian Ministry of Youth
Purpose: Digital transformation initiative for youth business sector oversight
Academic Level: Advanced software engineering project
🌟 Key Benefits 

Centralized Data Management: Single platform for all youth business contacts
Real-time Insights: Instant analytics on business sector distribution
Efficient Operations: Streamlined data entry and management workflows
Export Capabilities: Easy reporting for ministry documentation
Scalable Solution: Built to accommodate growing business database with out the need to integrate a SQL database for simplicity
User-friendly Interface: Intuitive design requiring minimal training

🚀 Getting Started
Prerequisites
bashPython 3.8+
pip (Python package manager)
Installation
bash# Clone the repository
git clone https://github.com/engoayoubfo22/business-contact-dashboard.git

# Navigate to project directory
cd business-contact-dashboard

# Install dependencies
pip install -r requirements.txt

# Generate data files
python parse_data.py

# Run the dashboard
streamlit run dashboard.py
Deployment
The dashboard is deployed on Streamlit Cloud for public access and can be easily integrated into the Ministry's digital infrastructure.
📁 Project Structure
business-contact-dashboard/

├── dashboard.py              # Main Streamlit application

├── parse_data.py            # Data processing script

├── requirements.txt         # Python dependencies

├── parsed_data.csv          # Business contacts data

├── category_translations.txt # Arabic translations

└── README.md               # Project documentation

👥 Contributors
AAST Development Team

Project developed as part of academic collaboration with Egyptian Ministry of Youth
Focused on practical solutions for public sector digital transformation


