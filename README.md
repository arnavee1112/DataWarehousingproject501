📦 MegaStar AI Order Assistant
An AI-powered warehouse optimization system that intelligently plans picking routes, checks product availability, and offers real-time assistance for order management.

🧠 Project Context
This repository contains the group project for the course Introduction to Artificial Intelligence (AI 501), undertaken at [Your Institution Name].

The goal of this project is to apply foundational AI concepts and algorithms to a real-world warehouse optimization problem. The team designed and implemented an AI-driven assistant that:

Optimizes picking routes in a warehouse setting, minimizing the total travel distance required to collect all items in an order.

Compares multiple algorithms, including Greedy Nearest Neighbor, A* Search, and Conditional Markov Chain Search (CMCS), to demonstrate various AI approaches to route planning.

Incorporates product availability checks and intelligent alternative suggestions to enhance order fulfillment accuracy and customer satisfaction.

Provides an interactive chatbot interface that simulates real-time user engagement for order management, route optimization, and product inquiries.

This project showcases the practical application of classical and data-driven AI techniques within logistics and supply chain domains.

Team Members and Contributions
Arnavee Maltare — Led algorithm design and implementation, integrated core functionalities, developed Greedy and CMCS methods, and managed documentation.

Chandresh Kaushik — Handled data preprocessing, implemented A* Search, developed visualizations, and contributed to the chatbot UI and availability modules.

Laxminag Mamillapalli — Managed dataset curation, designed alternative product recommendation logic, and supported algorithm evaluation and testing.

The team collaborated through iterative development cycles, peer reviews, and regular communication to deliver a comprehensive AI solution.

🚀 Project Objectives
Design and implement AI algorithms to optimize warehouse picking routes efficiently.

Develop a modular framework enabling comparison of different pathfinding methods.

Build product availability checks with confidence-scored alternative recommendations.

Create a user-friendly chatbot interface for interactive order management and assistance.

Visualize routes and algorithm performance to provide actionable insights.

🧩 Features
Multiple Pathfinding Algorithms: Greedy Nearest Neighbor, A* Search, and Conditional Markov Chain Search.

AI Explanations: Clear insights into the rationale behind algorithm decisions.

Interactive Progress Feedback: Visual progress bars and ETA estimates during optimization.

Product Availability & Alternatives: Real-time stock checks and smart recommendations.

Order Management: Amend, cancel, and price orders with or without promotions.

Route Visualization: Graphical display of picking paths and algorithm comparisons.

📂 Project Structure
bash
Copy
Edit
MegaStar_AI_Order_Assistant/
├── data/
│   ├── product_list.csv            # Product catalog with metadata
│   ├── dc_locations.csv            # Distribution center / bin locations
│   └── warehouse_stocks.csv        # Current stock quantities
├── notebooks/
│   └── warehouse_picking_optimization_CMCS.ipynb  # Main notebook with experiments and visualizations
├── src/
│   ├── optimization.py             # Algorithms and route planning logic
│   ├── availability.py             # Product availability & alternative recommendations
│   └── visualization.py            # Plotting and display utilities
├── README.md                       # This file
└── requirements.txt                # Python dependencies
🛠️ Installation & Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/arnavee1112/DataWarehousingproject501.git
cd DataWarehousingproject501
2. Create and Activate a Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate      # On Windows use: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Launch Jupyter Notebook
bash
Copy
Edit
jupyter notebook notebooks/warehouse_picking_optimization_CMCS.ipynb
📊 Algorithm Descriptions
Greedy Nearest Neighbor
Selects the nearest unvisited bin iteratively. Fast but may not find the optimal path.

A* Search
Uses heuristics to evaluate multiple routes and find the shortest path. Balances accuracy and performance.

Conditional Markov Chain Search (CMCS)
Learns from historical data to predict likely next bins for picking, aiming for efficient, adaptive routes.

📈 Results Summary
Method	Total Distance (units)	Steps (Visited Bins)
Greedy Nearest Neighbor	1500	50
A* Search	1450	48
Conditional Markov Chain Search (CMCS)	1400	45

CMCS demonstrated the best balance of route efficiency and adaptability.

🔗 Data Sources
Product List: Detailed information about available products.

Distribution Center Locations: Geographical or coordinate data for warehouse bins.

Warehouse Stocks: Real-time stock counts for each product.

Keep these datasets updated to ensure system accuracy.

🧪 Usage Instructions
Route Optimization: Choose an algorithm to compute efficient bin picking sequences.

Product Availability: Query SKU availability and receive alternative product suggestions.

Order Management: Amend or cancel orders, calculate prices, and apply promotions.

Visualizations: View picking routes and performance comparison graphs in the notebook.

🔮 Future Work
Integrate machine learning models for improved prediction of picking sequences.

Expand product recommendation engine using collaborative filtering.

Enhance chatbot natural language understanding for smoother user interactions.

Deploy as a web app for live warehouse operational use.

🤝 Contribution
Contributions and feedback are welcome! Please fork the repository, implement your improvements, and submit a pull request. Ensure your code follows existing style guidelines and includes adequate tests.

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

📞 Contact
For questions feel free to reach out 

