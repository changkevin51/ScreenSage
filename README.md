# ScreenSage


## Overview

ScreenSage is a powerful browser extension that tracks and analyzes your web browsing habits, providing insightful data about your screen time usage. This Chrome extension aims to help you understand your digital behavior patterns in order to make informed decisions about your online time management.

## Features

- **Real-time Screen Time Tracking**: Monitor how much time you spend on different websites throughout the day
- **Interactive Dashboard**: View your usage statistics in an intuitive, easy-to-read interface
- **Detailed Analytics**: Break down your browsing habits by website and time periods
- **AI-Powered Insights**: Generate personalized reports using Gemini-1.5 Pro API to get intelligent analysis of your browsing patterns
- **Productivity Score**: Receive a calculated productivity score based on your browsing habits
- **Daily and Weekly Views**: Toggle between daily and weekly statistics to understand your habits over time
- **Visual Charts**: Interactive charts to visualize your usage patterns
- **Website Categories**: Automatic categorization of websites for better understanding of time allocation

## Screenshots

### Dashboard
![Dashboard View](./assets/images/dashboard.png)
*Main dashboard showing total screen time, productivity score, and most used apps*

### Detailed Stats
![Detailed Statistics](./assets/images/detailed-stats.png)
*Detailed breakdown of website usage with interactive charts*

### Insights & Reports
![Insights View](./assets/images/insights.png)
*AI-generated insights about your browsing patterns*

## Installation

### From Chrome Web Store
1. Visit the [Chrome Web Store](https://chrome.google.com/webstore)
2. Search for "ScreenSage"
3. Click "Add to Chrome"

### Manual Installation
1. Download this repository as a ZIP file or clone it using Git:
   ```
   git clone https://github.com/changkevin51/screen-sage.git
   ```
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top-right corner
4. Click "Load unpacked" and select the ScreenSage directory
5. The extension should now appear in your Chrome toolbar

## Usage

1. **View Dashboard**: Click on the ScreenSage icon in your Chrome toolbar to view your dashboard
2. **Toggle View Mode**: Switch between daily and weekly views using the toggle switch
3. **Generate Reports**: Click the "Generate Report" button to receive AI-powered analysis of your browsing habits
4. **View Detailed Stats**: Click on any website in your list to see detailed usage charts
5. **Check Insights**: Navigate to the Insights tab to see personalized recommendations
6. **Reset Data**: Use the "Reset Data" button in the dashboard to clear all stored tracking data (use with caution)

## Technical Details

- **Storage**: All data is stored locally in your browser using Chrome's storage API
- **Privacy**: Your browsing data never leaves your device, except when generating reports (sent securely to Google's Gemini API)
- **Performance**: The extension is designed to be lightweight and use minimal resources
- **Data Structure**:
  - Daily data is stored with ISO date strings as keys
  - Website data includes domain name and milliseconds spent
  - Reports and insights are cached to minimize API usage

## Development

### Technologies Used
- JavaScript
- HTML/CSS
- Chrome Extension API
- Chart.js for data visualization
- Google's Gemini-1.5 Pro API for AI insights

### File Structure
```
ScreenSage/
├── manifest.json      # Extension configuration
├── popup.html         # Main UI structure
├── popup.js           # UI interaction logic
├── background.js      # Background tracking service
├── details.js         # Detailed view logic
├── style.css          # Styling
├── chart.min.js       # Chart library
└── assets/            # Images and icons
```

### Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## Privacy Policy

ScreenSage respects your privacy:
- All browsing data is stored locally in your browser
- When you generate reports, your data is sent to Google's Gemini API for analysis
- No personal information is collected or shared with third parties
- You can delete all stored data at any time using the "Reset Data" button

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Kevin Chang - [GitHub](https://github.com/changkevin51)

Project Link: [https://github.com/changkevin51/screen-sage](https://github.com/changkevin51/screen-sage)
