# Whether?

Welcome to **[whether?](https://ak-2045.github.io/JavaScript-Project-1-Weather-App/)**, the weather app that answers the question: *whether* or not you'll need an umbrella today! 🌧️🌞

This delightful little app will fetch the current weather conditions for any city you desire. All you have to do is type in the city name and click the search button! Let's dive into how it all works, step by step.

## Inspiration

This project is heavily inspired by GreatStack. Check out their awesome tutorial video here: [GreatStack Tutorial.](https://youtu.be/MIYQR-Ybrn4?list=PLjwm_8O3suyOgDS_Z8AWbbq3zpCmR-WE9)

## Features

- **Real-time weather**: Get the current temperature, humidity, and wind speed for your chosen city.
- **Iconic weather icons**: Clear skies, clouds, rain, snow—whatever the weather, we've got an icon for that!
- **Responsive design**: Whether you're on a desktop, tablet, or mobile, our app will look fab!

## How It Works

### Frontend (HTML & CSS)
- **HTML structure**: 
  - The main page is structured with a charming card design that contains a search box and the weather info. You’ll enter the city name, and voilà, weather at your fingertips!
  
- **CSS styling**: 
  - The background is a nice shade of dark (#222). The card has a gradient background (from #00feba to #5b548a) that’s *chef’s kiss* worthy. It's responsive and centered on the page, with rounded corners to give it a soft, welcoming feel. The search box and button are styled to look modern, with a clean white background and a satisfying click experience.

### Functionality (JavaScript)
- **API connection**: 
  - We’re using OpenWeather’s API to fetch real-time weather data. Don't worry, we’ve got it covered with our API key (`5ab65b97a0103ab6e69e94bcc83a6e4f`), so all the magic happens behind the scenes. 🌐

- **Search button**:
  - When you click the search button, the app takes the city name you entered and fetches the weather data for that city using the OpenWeather API. If the city doesn’t exist (because *where even is Wakanda?*), an error message will pop up politely suggesting you try again.

- **Weather display**:
  - Once we get the data, we display it in a beautiful format:
    - **Temperature**: Shown in Celsius, because we're sophisticated like that. 🌡️
    - **Humidity**: Because we all need to know how frizzy our hair will get. 💧
    - **Wind speed**: Is it kite-flying weather? Let's find out! 🪁

- **Weather icons**:
  - Depending on the forecast (Clear, Clouds, Rain, etc.), we display a cute weather icon. So, you’ll know if it’s rainy without even reading the text!

### Error Handling
- We’ve got you covered! If you enter an invalid city (like Atlantis), a friendly alert will let you know that city data isn’t available and to try again. No crashing, no confusion, just smooth sailing.

## Installation

To run this app locally, follow these steps:

1. Clone this repo: 
   ```bash
   git clone https://github.com/ak-2045/JavaScript-Project-1-Weather-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd whether-app
   ```
3. Open `index.html` in your browser.
   ```bash
   open index.html
   ```

And you’re all set! Now go ahead and check whether or not you’ll need a jacket today. 🧥

## Contribution

Found a bug? Or maybe you know *whether* it’ll rain next Tuesday and you want to improve this app? Feel free to fork the repo, make your changes, and submit a pull request. We're all about collaborative weather forecasting!

## License

This project is for personal use only and is not licensed for public distribution. Feel free to explore and learn from the code, but please do not distribute or use it for commercial purposes without permission. So you're free to use it, improve it, or even give it a snazzy new name (though "whether?" is pretty hard to beat 😉).

Enjoy using **whether?**—because knowing the weather shouldn't be so serious!
