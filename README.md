# 📈 Crypto Sentiment Analysis: Fear & Greed vs. Price

This project explores the relationship between market sentiment and Bitcoin price using **Simple Linear Regression**. It was created as a practical application of the concepts learned in the **Machine Learning Specialization** by Andrew Ng.

## 📝 About The Project
The goal of this mini-project is to determine how much the "market mood" (represented by the Fear & Greed Index) correlates with the actual price of Bitcoin. In light of recent geopolitical tensions in the Middle East, understanding these correlations is more relevant than ever.

## 🛠️ Built With
* **Python** (Core programming)
* **Scikit-Learn** (Linear Regression model)
* **Pandas** (Data manipulation)
* **YFinance API** (Financial market data)
* **Matplotlib** (Data visualization)

## 📊 Key Results
The model calculated a **Weight ($w$)** of approximately **768.63**, suggesting a strong positive correlation:
* As the Fear & Greed Index increases by 1 point, the Bitcoin price tends to increase by ~$768 USD.
* The **Bias ($b$)** was calculated at ~$65,965 USD.

[INSERT YOUR GRAPH IMAGE HERE]

## 🚀 How to Run
1. Open the `.ipynb` file in **Google Colab**.
2. Run all cells to fetch the latest data from the APIs.
3. Observe the trend line and current predictions.

## 🔮 Future Improvements
* Implement **Multiple Linear Regression** by adding Oil prices or Gold as additional features ($X_2, X_3$).
* Explore **Polynomial Regression** to better fit the non-linear market movements.

<img width="778" height="475" alt="btc" src="https://github.com/user-attachments/assets/488d3104-3516-4bd4-bc7a-73e143c8b735" />

