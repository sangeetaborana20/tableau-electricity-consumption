📖 Overview
This project analyzes electricity consumption patterns across Indian states using Tableau dashboards integrated into a Flask web application. The goal is to transform raw electricity usage data into interactive visual insights that support energy planning, research, and decision-making.

Team Members:-     
Sangeeta Borana - Member     
Rushikesh Mhaske - Team Lead     
Saloni Hegde - Member     
Rutuja Potghan - Member     

Users can:
- Explore state-wise electricity consumption
- Compare regional demand trends
- Analyze time-based usage patterns
- Interact with dashboards directly via a web interface

---
## 🗂️ Project Structure
 

---

## ⚙️ Technology Stack
|   Component        | Tool/Technology                            |
|----------------------|------------------------------------------|
| Data Storage       | CSV Dataset                                   |
| Visualization       | Tableau Desktop & Tableau Public |
| Web Integration  | HTML (iframe embedding)            |
| Backend              | Flask (Python)                                |
| Deployment        | Tableau Public + Flask Web App   | 


## 🔄 System Workflow
1. Data Layer: CSV dataset with states, regions, coordinates, dates, and usage.
2. Visualization Layer: Tableau dashboards (bar charts, line charts, maps).
3. Web Integration Layer: Dashboards embedded into HTML via iframe.
4. Access: Flask serves the HTML page, enabling browser-based interaction.


## 🚀 Installation & Setup
### Prerequisites
- Python 3.x
- Flask (`pip install flask`)
- Tableau Desktop + Tableau Public account
- Modern browser (Chrome/Edge)

### Steps
1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd electricity-consumption-dashboard

2 :Place the dataset (Consumption.csv) in the project folder.
3 : Run the Flask app:
        ->python app.py

5: :Open http://127.0.0.1:5000/ in your browser to view the dashboard.

📊 Features
•	State-wise Analysis: Compare electricity usage across states.
•	Regional Analysis: Group states by North, South, East, West.
•	Trend Analysis: Time-based electricity demand visualization.
•	Interactive Filters: Explore data dynamically.
•	Web Access: Dashboards embedded via Flask + HTML.
________________________________________
📈 Results
•	Clear visualization of electricity consumption patterns.
•	Interactive dashboards accessible via web browser.
•	Supports government, research, and educational use cases.
________________________________________
🔮 Future Enhancements
•	Real-time electricity consumption integration.
•	Machine learning models for demand forecasting.
•	Mobile-friendly dashboard interface.
•	Cloud-based storage for scalability.
