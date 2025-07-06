🏡 House Price Prediction Using Python & Machine Learning

This project uses Multiple Linear Regression to predict the price of a house based on:

✅ Square Footage (Area)
✅ Number of Bedrooms
✅ Number of Bathrooms

📂 Project Structure

House_Prediction/
├── house_data.csv         # Dataset
├── price_prediction.py    # Main Python code
├── README.md              # Project documentation
📊 Dataset Example (house_data.csv)

Area (sqft),Bedrooms,Bathrooms,Price (in Lakhs)
500,1,1,25
750,2,1,35
1000,2,2,50
1250,3,2,65
1500,3,2,78
...
⚙️ Technologies Used

Python 3
Pandas
Scikit-Learn
Linear Regression (Supervised ML)
🚀 How to Run the Project

1. Install Required Libraries
In terminal:

pip3 install pandas scikit-learn
2. Run the Script
python3 price_prediction.py
3. Provide User Inputs
You'll be asked to enter:

Area in sqft
Number of bedrooms
Number of bathrooms
The script will predict the estimated house price based on these inputs.

✅ Example Output

--- Loaded Data ---
   Area (sqft)  Bedrooms  Bathrooms  Price (in Lakhs)
0          500         1          1               25
1          750         2          1               35
...

Model Accuracy: 0.99

Enter the area of the house in sqft: 1500  
Enter the number of bedrooms: 3  
Enter the number of bathrooms: 2  

Predicted Price: ₹78.00 Lakhs
💡 Future Improvements

Deploy as a web app using Flask or Streamlit
Add more features like Location, Property Age, etc.
Use more advanced ML models (Random Forest, etc.)
Improve dataset for real-world scenarios
