# AI Rassoi - Smart Calorie Tracker

Welcome to **AI Rassoi**, a responsive web application designed to help you track the calorie content of food items using image analysis. Built with HTML, CSS, and JavaScript, this app offers a beautiful UI with modern features to manage your dietary intake effortlessly.

## Features
- **Image Analysis**: Upload a photo or use your camera to analyze food items. The app integrates with APIs to detect and calculate nutritional data.
- **Calorie Tracking**: Displays detailed calorie, protein, carb, and fat content for each item, with a running total for the day.
- **Progress Indicators**: Includes a progress bar and circular loading indicator for each food item card.
- **History Log**: View your recent entries in a collapsible history section.
- **Theme Toggle**: Switch between light and dark themes for a personalized experience.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices.

## Current Data
The app uses a Groq API (llama-3.2-90b-vision-preview model) to analyze images and returns nutritional data in JSON format, e.g., `{items:[{item_name:"Puri", total_calories:300.5, total_protein:4.6, total_carbs:54.6, total_fats:12.2},...]}`, based on the uploaded image.

## How to Use
1. Clone the repository: `git clone <repository-url>`
2. Open `index.html` in a modern web browser.
3. Upload an image or use the camera to analyze food items. Ensure you have an internet connection for API calls.

## Installation
- No additional dependencies required; the app runs in the browser.
- Replace the ImgBB API key (`caa9e987e52508e76795ed3edebc273a`) and Groq API key (`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`) with your own credentials.

## Future Improvements
- Enhance search functionality with API integration.
- Add user authentication and data persistence.
- Expand API support for a broader range of food items.
- Improve error handling and UI feedback.

## Contributions
Feel free to fork this repository, submit issues, or create pull requests. All contributions are welcome!

## License
[MIT License] - Please add a `LICENSE` file to the repository.

## Credits
- ImgBB API for image hosting.
- Groq API for vision-based nutritional analysis.
