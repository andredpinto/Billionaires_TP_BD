# Billionaires Relational Database Web App

A dynamic, full-stack web application built to query, filter, and navigate a relational database of the world's billionaires. 

This project serves as an interactive frontend for a custom SQL database, demonstrating the ability to bridge backend data processing with frontend user interfaces using Python and Flask.

## Features
* **Advanced Search:** Query the database by name.
* **Dynamic Routing:** HTML pages are rendered dynamically based on real-time SQL queries.
* **Data Filtering:** Clean, intuitive UI to sort and filter billionaire demographics.
* **Custom Backend Logic:** Raw SQL queries integrated directly into Flask routes for efficient data retrieval.

## Tech Stack
* **Backend:** Python, Flask
* **Database:** SQLite
* **Frontend:** HTML5, CSS3, Jinja2 Templating

## Getting Started

Follow these instructions to run the application locally on your machine.

### Prerequisites
Make sure you have Python 3.x installed. 

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/andredpinto/Billionaires_TP_BD
   cd Billionaires_TP_BD
   ```

2. Create and activate a virtual environment (recommended):
```
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. Install required dependencies:
```
pip install --user Flask
```

4. Run the Flask application:
```bash
python3 app/app.py
```

5. Open you browser and navigate to:
http://127.0.0.1:5000   (TODO: check)
