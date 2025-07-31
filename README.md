# StopWatch 🕒

A web‑based stopwatch built with **HTML**, **CSS**, and **JavaScript**, featuring start, stop, and reset functionality including hours, minutes, seconds, and milliseconds tracking.

---

## 🚀 Features

- Displays time with **hours**, **minutes**, **seconds**, and **milliseconds**  
- **Start**, **Pause/Stop**, and **Reset** buttons  
- Clean layout and responsive design  
- Built using vanilla JavaScript and DOM manipulation  

---

## ⚙️ How to Use

1. **Clone or download** this repository  
   ```bash
   git clone https://github.com/ashbedi1804/StopWatch.git
   cd StopWatch
   ```

2. **Open** `index.html` in your browser  

3. **Use controls**:
   - Click **Start** to begin timing  
   - Click **Stop** to pause  
   - Click **Reset** to zero out the timer  

---

## 🧠 How It Works

- **index.html**: Contains the display and buttons  
- **style.css**: Provides styling and layout  
- **script.js**:
  - Uses `setInterval` to update the timer every 10 ms  
  - Tracks elapsed time in separate counters (hr, min, sec, count)  
  - Updates display values dynamically  
  - Enables button actions—start, stop/pause, reset  

---

## 🔧 Customization & Development

- Adjust visual styles in `style.css` (colors, fonts, layout)  
- Customize timer logic in `script.js`:
  - Change update interval  
  - Add a **lap** or split-time feature  
  - Format display (leading zeros, decimal precision)  
  - Support keyboard controls or mobile gestures  

---

## 🧪 Testing

- Verify timer accuracy by letting it run for fixed intervals  
- Test edge cases:
  - Pressing **Start** repeatedly  
  - Pressing **Reset** during running or paused state  
- Observe display rollover (e.g., 60 sec → 1 min)

---

## 🌱 Future Enhancements

- Add **lap functionality** to capture intermediate times  
- Store timing history in local storage or a file  
- Support **keyboard shortcuts** or touch gestures  
- Polish UI with animations, themes, or color mode toggle  

---

## 📞 Contact

- GitHub: [@ashbedi1804](https://github.com/ashbedi1804)  
- Feel free to open an issue or pull request to contribute!

Enjoy working with your stopwatch project—happy timing!⏱️
