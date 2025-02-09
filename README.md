### **React-weather-app**  

- 🌦️ **React Weather App**  
  - A simple weather app built with React and Vite that fetches real-time weather data from an API.  
  - Displays city name, humidity, and wind speed.  

### **🌟 Features**  
- 🌍 Fetches real-time weather data  
- 📍 Displays city name, humidity, and wind speed  
- ⚡ Fast and lightweight using Vite  
- 🎨 Responsive and user-friendly UI  

### **🛠️ Technologies Used**  
- ⚛️ **React** - Frontend library  
- 🚀 **Vite** - Fast build tool  
- 🌐 **Fetch API / Axios** - API requests  
- 🎨 **CSS** - Basic styling  

### **🚀 Getting Started**  

#### **✅ Prerequisites**  
- Make sure you have **Node.js** and **npm** installed.  

#### **📥 Installation**  
- Clone the repository:  
  ```sh
  git clone https://github.com/ShashankKumar2160/React-weather-app.git
  ```
- Navigate to the project directory:  
  ```sh
  cd react-weather-app
  ```
- Install dependencies:  
  ```sh
  npm install
  ```
- Get an API key from **OpenWeatherMap** or any weather API provider.  
- In the given `.env` file in the root directory, add:  
  ```sh
  VITE_WEATHER_API_KEY=your_api_key_here
  ```

### **▶️ Running the App**  
- Start the development server:  
  ```sh
  npm run dev
  ```
- The app will be available at: **http://localhost:5173/**  

### **🎯 Usage**  
- 🔍 Enter the **city name** in the input field.  
- 🔄 Click the **"Search"** button to fetch weather data.  
- 🌡️ View **humidity, wind speed, and city name** displayed on the screen.  

### **📊 API Response Example**  
```json
{
  "name": "New York",
  "main": {
    "humidity": 75
  },
  "wind": {
    "speed": 5.7
  }
}
```

### **🚀 Deployment**  
- To build for production:  
  ```sh
  npm run build
  ```
- This will create an optimized `dist/` folder.  

### **🤝 Contributing**  
- Feel free to **fork** and contribute by opening a **pull request**.  

### **👨‍💻 Author**  
- Developed by **Shashank Kumar**. Follow me on **GitHub**. 🚀  
