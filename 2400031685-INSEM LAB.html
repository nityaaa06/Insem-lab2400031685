import React, { useState } from "react";

function App() {
  const [city, setCity] = useState("");
  const [weather, setWeather] = useState(null);
  const [error, setError] = useState("");

  const handleSubmit = async (e) => {
    e.preventDefault();
    setError("");
    setWeather(null);

    // OpenWeatherMap API endpoint
    const apiKey = "YOUR_API_KEY"; // <-- Replace this with your own key!
    const url = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&units=metric`;

    try {
      const res = await fetch(url);
      if (!res.ok) throw new Error("City not found");
      const data = await res.json();
      setWeather({
        temperature: data.main.temp,
        humidity: data.main.humidity,
        condition: data.weather[0].main,
      });
    } catch (err) {
      setError(err.message);
    }
  };

  return (
    <div style={{ maxWidth: 350, margin: "auto", padding: 20 }}>
      <h2>Weather Checker</h2>
      <form onSubmit={handleSubmit}>
        <input
          type="text"
          placeholder="Enter city name"
          value={city}
          onChange={(e) => setCity(e.target.value)}
          style={{ width: "65%", marginRight: 10, padding: "8px" }}
        />
        <button type="submit" style={{ padding: "8px 12px" }}>Get Weather</button>
      </form>
      {error && <p style={{ color: "red" }}>{error}</p>}
      {weather && (
        <div style={{ marginTop: 20 }}>
          <p><strong>Temperature:</strong> {weather.temperature} °C</p>
          <p><strong>Humidity:</strong> {weather.humidity} %</p>
          <p><strong>Condition:</strong> {weather.condition}</p>
        </div>
      )}
    </div>
  );
}

export default App;
