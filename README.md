# 💹 ForexPro - Real-Time Currency Converter

**ForexPro** is a professional, real-time currency converter built with **Streamlit**.  
It fetches **accurate exchange rates**, allows multiple currency conversions, maintains conversion history, and provides quick selections for popular currency groups.

---

## 🔹 Features

- Real-time exchange rates from [ExchangeRate.host](https://exchangerate.host/)
- Convert **any amount** between multiple currencies
- Quick selection buttons for **major currencies**, **Asian markets**, and **common pairs**
- Save favorite target currencies for faster access
- Conversion history with timestamps (recent 3 conversions shown)
- Clean, modern, **glassmorphic UI** with gradient backgrounds
- Accurate conversion calculations with visual rate display
- Footer with source data and professional branding

---

## 🖼️ Project Preview

Below are screenshots of the **ForexPro Currency Converter** in action:

<img width="1891" height="606" alt="Screenshot 2025-11-30 130014" src="https://github.com/user-attachments/assets/37ac794f-68e3-4682-9a72-24edc144e407" />
<img width="1859" height="670" alt="Screenshot 2025-11-30 130031" src="https://github.com/user-attachments/assets/0fe2f3cc-5bd5-4997-b5dd-9ba49dba8c5c" />
<img width="1829" height="574" alt="Screenshot 2025-11-30 130044" src="https://github.com/user-attachments/assets/599b7fe9-2ab3-4f35-960b-a3efdd54bae6" />


## 🛠️ Technologies Used

- **Python 3.11**
- **Streamlit** for frontend and UI components
- **Requests** for API calls
- **Pandas** for data handling
- **Plotly** for charts (planned for historical trends)
- **HTML & CSS** for custom styling


## 📦 Installation

1. Clone the repository:
git clone <your-repo-link>
cd CurrencyConverter
Create a virtual environment (recommended):

python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
Install dependencies:

pip install -r requirements.txt
🚀 How to Run

streamlit run app.py
This will open the ForexPro Currency Converter in your default browser.

- Usage
Conversion Input:

Enter the amount you want to convert.

Select a source currency (FROM CURRENCY).

Target Currencies:

Select one or more target currencies.

Save selections as favorites for future use.

Quick Selections:

Use buttons to select major currencies, Asian markets, common pairs, or clear selection.

Convert Now:

Press Convert Now to get real-time conversion results.

Conversion results display each currency, converted amount, and exchange rate.

Conversion History:

Shows last 3 conversions.

Can be cleared with Clear History button.

- UI / Styling
Glassmorphic Cards: Modern blurred-background cards for inputs, conversion results, and stats.

Gradient Buttons: For quick actions and conversion buttons.

Currency Flags: Quick visual recognition of currencies.

Responsive layout: Two-column conversion results and stats row.

🔗 API
Data provided by ExchangeRate.host

Real-time exchange rates update every 5 minutes.

Historical data fetched for plotting trends (future implementation).

- Session State
Favorites: User-selected currencies persist across session.

Conversion History: Stores recent conversions.

Last Update: Timestamp of last fetched exchange rates.

📁 File Structure

CurrencyConverter/
│
├── app.py                # Main Streamlit app
├── requirements.txt      # Dependencies
├── README.md             # Project documentation

- Future Improvements
Plot historical trends using Plotly charts

Add automatic refresh of exchange rates

Export conversion history as CSV

Support for cryptocurrency conversion

📞 Contact
 Developer: Sumit Lohar
 📧 Email:sumitlohar063@gmail.com
 🐙 GitHub: https://github.com/YOUR-USERNAME
 🔗 LinkedIn:https://www.linkedin.com/in/sumit-lohar-498341317/
