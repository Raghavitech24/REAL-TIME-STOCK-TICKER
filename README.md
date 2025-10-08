# 📈Real-Time Stock Ticker (HTML + JavaScript)

A simple and interactive **Real-Time Stock Ticker** built using **HTML, CSS, and JavaScript**.  
This project simulates live stock price updates for popular companies and displays them in a dynamic, real-time updating table — perfect for learning DOM manipulation, table rendering, and front-end interactivity.

---
## 🚀 Features
- 🔄 Real-time updates every **2 seconds**
- 📊 Simulated stock prices and percentage changes
- ✅ Automatic color indication:
  - 🟢 **Green** – Positive price change
  - 🔴 **Red** – Negative price change
  - 🟡 **Yellow** – No change (neutral)
- 📱 Responsive and minimal design with dark theme
- 🧠 Simple, clean code — great for learning or customizing
---
## 📁 Project Structure
real-time-stock-ticker/
├── index.html # Main HTML file containing structure, style, and JS
---
## 🛠️ How It Works
The stock ticker simulates data for 10 major tech companies (`AAPL`, `TSLA`, `MSFT`, `GOOG`, `AMZN`, `NFLX`, `NVDA`, `META`, `IBM`, `ORCL`).  
Every **2 seconds**, random stock price and percentage change values are generated, and the HTML tables update dynamically.

Key logic:
- JavaScript `setInterval()` updates the data every 2000ms.
- `getRandomStockData()` simulates stock price & percentage change.
- Tables are re-rendered dynamically using DOM manipulation.
---
## 📸 Preview
| Positive | Negative | Neutral |
|----------|----------|----------|
| 🟢 +1.23% | 🔴 -0.87% | 🟡 0.00% |

The table updates automatically without refreshing the page:
                      Symbol	      Change	        Last	         Time
                        AAPL	      +1.23%	     154.23	            10:25:42
                       TSLA	      -0.87%	     872.12	            10:25:42
                       MSFT	       0.00%	     312.00	            10:25:42
