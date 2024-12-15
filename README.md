# Airline Revenue Optimization Project

## **Problem Statement**

Our company operates a diverse fleet of aircraft, ranging from small business jets to medium-sized planes, delivering high-quality air transportation services. However, we face challenges that are impacting profitability, including:

1. Stricter environmental regulations.
2. Higher flight taxes.
3. Tight labor market and rising labor costs.
4. Increased fuel prices.
5. Escalating interest rates.

To address these challenges, we aim to analyze our database and identify actionable strategies to improve occupancy rates and enhance average profit per seat.

---

## **Main Challenges**

1. **Stricter Environmental Regulations**:  
   Rising operational expenses due to increasing pressure on the aviation industry to reduce its carbon footprint.

2. **Higher Flight Taxes**:  
   Heavier taxes on air travel are affecting operational costs and reducing passenger demand.

3. **Tight Labor Market**:  
   A shortage of skilled professionals has led to rising labor costs and high employee turnover.

---

## **Objectives**

1. Boost occupancy rates to maximize profitability.  
2. Develop a dynamic pricing strategy to attract customers and retain loyalty.  
3. Enhance customer experience to stand out in a competitive market.  

---

## **Steps and Methodology**

### **1. Data Exploration**
Connected to the `travel.sqlite` database and explored the following tables:
- **aircrafts_data**
- **airports_data**
- **boarding_passes**
- **bookings**
- **flights**
- **seats**
- **ticket_flights**
- **tickets**

### **2. Data Cleaning**
Ensured clean and accurate data for analysis by reviewing column information for all tables.

### **3. Basic Analysis**
- **Number of planes with more than 100 seats:** Identified using SQL queries.
- **Trends in ticket bookings and revenue:** Visualized trends over time using `Matplotlib`.
- **Average charges by aircraft and fare condition:** Analyzed average revenue using `Seaborn` bar plots.

### **4. Advanced Analysis**
- **Occupancy Rate Analysis**:  
   Calculated the average occupancy per aircraft and revenue impact from a 10% increase in occupancy.  

- **Annual Turnover Increase**:  
   Estimated how much annual turnover could increase with improved occupancy rates.

---

## **Key Insights**

1. **Revenue Metrics**:
   - Analyzed total yearly revenue, average ticket revenue, and occupancy rates to identify underperforming areas.
   - Higher occupancy rates significantly increase profits by minimizing expenses for unoccupied seats.

2. **Dynamic Pricing Strategy**:
   - Adjusting ticket prices based on fare conditions and aircraft quality can enhance customer appeal.

3. **Balanced Approach**:
   - Focusing on increasing occupancy without compromising customer satisfaction and safety is critical for sustainable growth.

---

## **Tools and Technologies**

- **Python Libraries**:
  - `sqlite3`: For database connection and querying.
  - `pandas`: For data manipulation and analysis.
  - `matplotlib` and `seaborn`: For data visualization.

- **Database**:
  - SQLite (`travel.sqlite`)

---

## **Conclusion**

This project demonstrates how airlines can leverage data to enhance profitability by:  
- Maximizing occupancy rates.
- Refining pricing strategies.  
- Maintaining high standards of safety and customer satisfaction.  

By implementing data-driven strategies, airlines can effectively address industry challenges while ensuring long-term sustainability.

---

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/airline-revenue-optimization.git
2. Install Dependencies
To install the required Python packages, run the following command in your terminal:

```bash
pip install -r requirements.txt

# Steps to Connect SQLite Database and Run Analysis Script

## 1. Ensure the SQLite Database is Available
- Confirm that the `travel.sqlite` file is located in the project directory.

## 2. Run the Analysis Script
- Use the following command to execute the script:

```bash
python analysis.py
