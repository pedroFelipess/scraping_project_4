# scraping_project_4
📊 Brazil ETFs Scraping with Pandas  

This project scrapes the Brazil ETFs table from [Investing.com](https://br.investing.com/etfs/brazil-etfs) using **Pandas** and **Requests**. The extracted data is processed and saved as a **CSV** file for further analysis.  

## 🚀 Technologies Used  

- **Python**  
- **Pandas**  
- **Requests**  

## 📌 How to Use  

1. Clone this repository:  
   ```bash
   git clone git@github.com:pedroFelipess/scraping_project_4.git
   ```  
2. Install the dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the script:  
   ```bash
   python main.py
   ```  
4. The **dados_etfs.csv** file will be generated with the extracted information.  

## 📄 Collected Data  

The table includes the following information:  
- ETF name  
- Last price  
- Daily change (%)  
- Volume  
- Last update time  

## ⚠️ Notes  

- **Investing.com** may block frequent access, so it's recommended to use **headers** and avoid making too many requests in a short time.  
- If the website structure changes, the code may need to be updated to keep it working correctly.  