📌 Overview

This project applies the ECLAT (Equivalence Class Transformation) algorithm to perform market basket analysis and uncover frequent itemsets from transactional data. The extracted patterns help businesses optimise product placement, cross-selling strategies, and inventory planning.

Unlike Apriori, ECLAT uses a vertical data format, making it faster and more efficient for large datasets.

🎯 Objectives

Identify frequently purchased item combinations

Improve market optimisation and decision-making

Reduce computational overhead compared to Apriori

Generate actionable insights from transaction data

🧠 Algorithm Used
ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal)

Uses TID (Transaction ID) sets

Computes support via set intersection

Efficient for dense datasets

Depth-first search strategy

📂 Project Structure
ECLAT_in_Market-Optimisation/
│
├── data/
│   └── transactions.csv
│
├── src/
│   ├── eclat.py
│   └── preprocessing.py
│
├── results/
│   └── frequent_itemsets.csv
│
├── requirements.txt
└── README.md

🛠️ Technologies Used

Python

Pandas

NumPy

itertools

⚙️ Installation
git clone https://github.com/your-username/ECLAT_in_Market-Optimisation.git
cd ECLAT_in_Market-Optimisation
pip install -r requirements.txt

▶️ Usage
python src/eclat.py


You can modify:

Minimum support threshold

Input dataset

Output format

📊 Output

Frequent itemsets with support values

Insights useful for:

Product bundling

Shelf optimisation

Promotional strategies

🚀 Applications

Retail & E-commerce analytics

Recommendation systems

Customer behaviour analysis

Inventory optimisation

📌 Future Enhancements

Add association rule generation (confidence & lift)

Integrate visual dashboards

Support real-time streaming data

Compare with Apriori & FP-Growth

🤝 Contributing

Contributions are welcome!
Fork the repo, create a branch, and submit a pull request.

📜 License

This project is licensed under the MIT License.
