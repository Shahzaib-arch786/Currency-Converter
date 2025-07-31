
# Currency Converter App

A modern, responsive **Currency Converter** built with **React.js**, **Tailwind CSS**, and custom hooks. It fetches exchange rates from the FawazAhmed Currency API and offers seamless conversion between currencies.

## 🚀 Features

- Convert between 150+ currencies using up-to-date rates  
- Swap base and target currencies easily  
- Smooth transitions and responsive UI via Tailwind CSS  
- Built with custom React hooks for clean modular architecture  
- No external UI libraries—pure React + Tailwind for flexibility

## 🔧 Tech Stack

- **React.js** – frontend UI with functional components  
- **TailwindCSS** – utility-first styling and responsive design  
- **Custom Hooks** – e.g. `useCurrencyInfo`  
- **API** – Uses the [fawazahmed0 currency API] for daily rates  
- (Optional) **React Query** or other tool for caching/fetching data

## 📁 Project Structure

```

src/
├── components/
│   ├── index.js
│   ├── Input.jsx
│   
├── hooks/
│   ├── useCurrencyInfo.js
│   
├── App.jsx
├── index.jsx
└── tailwind.css

````

## 🚶 How to Run Locally

```bash
git clone https://github.com/Shahzaib‑arch786/Currency‑Converter.git
cd Currency‑Converter
npm install
npm run dev
````

Open `http://localhost:5173` in your browser to use the app.

## 🧪 Usage Examples

### Convert USD to PKR

```js
useConvertCurrency('USD', 'PKR', 100);
// => { result: 27836.00, rate: 278.36 }
```

### Swap Currencies

A `SwapButton` swaps the base and target currencies with a click.

## 📚 API Integration

This app uses API endpoints like:

```
https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies/{base}/{target}.json
```

* **Custom Hook**: `useCurrencyInfo(currency)`
* **Fetches latest daily rates**
* **The currency argument needs to be in the API URl**

## 🧩 Custom Hooks

* `useCurrencyInfo(currency)` – retrieves and caches rates for given base


## ✨ Improvements & Roadmap

* Add **currency favorites** feature
* Enable **historical rate lookup** by date
* Integrate with **React Query** for caching
* Add unit tests and **Cypress** end-to-end testing
* Deploy to a static host (e.g. Vercel, Netlify)

## 📝 License

Distributed under the **MIT License**. See `LICENSE` for details.

## 💬 Contact

Created by **\[Muhammad Ali Shahzaib]**
📧 Email: [shahzaib02122001@gmail.com](mailto:shahzaib02122001@gmail.com)
GitHub: [Shahzaib‑arch786](https://github.com/Shahzaib‑arch786)

```

---

