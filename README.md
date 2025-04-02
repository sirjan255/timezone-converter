# 🌐 Advanced Timezone Converter  

A timezone conversion tool with automatic Daylight Saving Time (DST) handling.  

## ✨ Features  

### Precision Time Conversion  
- Supports **600+ IANA timezones**  
- **Real-time conversion** updates  
- Displays **UTC offset** and **timezone abbreviation**  

### Intelligent DST Handling  
- **Automatic detection** and correction of DST transitions  
- **Visual warnings** for adjusted times  
- DST **active/inactive indicators**  

### Professional UI  
- **Modern gradient design**  
- **Fully responsive** for mobile and desktop  

## 🛠 Technical Details  

- **Moment-Timezone** for precise calculations  
- **Vanilla JavaScript** (no frameworks)  
- **CSS3 Variables** for theming  

## ⚙️ Setup  

1. Download `index.html`  
2. Open in a modern browser **(requires internet for initial load)**  

## 💡 Usage  

1. Select **source** and **target** timezones  
2. Enter a custom time **(optional)**  
3. View the **converted time** in real-time  

## 🌍 Browser Support  

| Browser        | Support Level  | Notes |  
|---------------|---------------|-------------------------------|  
| **Chrome**    | ✅ Full        | Best performance |  
| **Firefox**   | ✅ Full        | May have issues with `datetime-local` input |  
| **Edge**      | ✅ Full        | No known issues |  
| **Safari**    | ⚠️ Partial     | Older versions may not support `datetime-local` |  
| **Mobile Chrome** | ✅ Optimized  | Works well |  
| **Mobile Safari** | ⚠️ Partial   | DST adjustments may behave unexpectedly |  

## ⚠ Limitations  

- Requires **internet connection** for initial load (Moment.js from CDN)  
- **Automatically adjusts** invalid DST transition times  
