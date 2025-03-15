# DDOS-attack-detection
DDoS Attack Detection using Machine Learning is a project that applies various ML algorithms (Random Forest, SVM, Decision Trees, etc.) to detect and classify DDoS attacks in Software-Defined Networks (SDNs). It utilizes a cleaned dataset, feature selection techniques, and real-time classification for robust network security.

📌 Project Overview  
DDoS (Distributed Denial of Service) attacks pose a significant threat to network security, often disrupting services and causing financial losses. This project leverages **Machine Learning (ML) algorithms** to detect and classify DDoS attacks in **Software-Defined Networks (SDNs)**.  

The project evaluates different ML models, including **Random Forest, SVM, KNN, Decision Trees, and Neural Networks**, to determine the most effective approach for real-time attack detection.  
##  Features  
✔ **Preprocessing & Cleaning** - Handles missing values, removes duplicates, and extracts relevant network traffic features.  
✔ **Feature Selection** - Identifies key attributes for efficient attack detection.  
✔ **Machine Learning Models** - Implements and compares multiple ML classifiers.  
✔ **Real-Time Detection** - Integrates the best-performing model for live attack classification.  

## Tech Stack  
- **Programming Language**: Python  
- **Libraries Used**: Pandas, NumPy, Scikit-Learn, Matplotlib  
- **Tools**: Jupyter Notebook  

## Project Structure  
📁 DDoS-Attack-Detection │── 📄 README.md │── 📄 DataCleaning.ipynb # Data preprocessing and feature extraction │── 📄 DDOSPrediction.ipynb # ML model training and evaluation │── 📂 dataset/ # Raw and cleaned network traffic data │── 📄 requirements.txt # List of dependencies

##  Results  
Among all evaluated models, **Random Forest** was found to be the most effective, offering high accuracy and robustness for detecting DDoS attacks in SDNs.  
 **Performance Metrics:**  
- **Accuracy:** 95%  
- **Precision:** 93%  
- **Recall:** 96%  

##  Installation & Usage  
1️⃣ Clone the repository  
  git clone https://github.com/01Praneeth/DDOS-attack-detection.git
2️⃣ Install dependencies
  pip install -r requirements.txt
3️⃣ Run the Jupyter notebooks
  jupyter notebook
License
This project is for educational and research purposes only.

Contributors
Praneeth (https://github.com/01Praneeth))
Open-source contributions are welcome! Contact
For questions, feel free to reach out: praneethnaik01@gmail.com

This README provides a clean, structured explanation of your project while making it easy for others to understand and use.
