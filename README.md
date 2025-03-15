# 💰 Tip Calculator

This is a simple JavaScript program that calculates the tip based on the bill amount. 💵✨

## 🚀 Features
- Calculates the tip based on the bill amount.
- Uses a ternary operator for conditional logic.
- Logs the bill, tip, and total amount to the console.

## 📜 Code Overview
```javascript
const bill = 275;
const tip = bill >= 50 && bill <= 300 ? bill * 15/100 : bill * 20/100;

console.log(`The bill was ${bill}, the tip was ${tip}, and the total value ${bill + tip}`);
```

## 🛠️ How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/tip-calculator.git
   ```
2. Open `script.js` in your favorite code editor.
3. Run the script in the browser console or Node.js.

## 📢 Output Example
```
The bill was 275, the tip was 41.25, and the total value 316.25
```

## 📌 Notes
- If the bill is between **50 and 300**, a **15%** tip is applied.
- Otherwise, a **20%** tip is applied.

## 🎯 Future Enhancements
- ✅ Accept user input for dynamic bill values.
- ✅ Create a web-based interface for easy use.
- ✅ Add currency selection options.

## 📜 License
This project is open-source and available under the MIT License.

---

⭐ Feel free to contribute, fork, or give a star! 🌟
