# Race Time Predictor

A web application that helps athletes predict their potential finish times for upcoming races by comparing results of athletes who have completed both races.

## Purpose

When training for a race, it's often helpful to estimate your potential finish time. This tool helps you do this by:

1. Finding athletes who have completed a race you've done
2. Comparing their times to a race you're planning to do
3. Using this data to get a sense of relative performance between the two races

For example, if you completed Race A in 4 hours, and you find that other runners who completed Race A in 4 hours typically complete Race B in 8 hours, this gives you a data-driven estimate for your potential Race B finish time.

## Features

- Support for multiple race result websites:
  - UltraSignup
  - Pacific Multisports
- Automatic name matching across different result formats
- Display of all matched athletes and their respective times
- Complete listing of athletes from both races for verification

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/race-compare.git
cd race-compare
```

2. Install dependencies:
```bash
npm install
```

3. Start the application:
```bash
npm start
```

4. Open your browser and navigate to \`http://localhost:3000\`

## How to Use

1. Find the results page URL for a race you've completed
2. Find the results page URL for the race you want to predict
3. Paste both URLs into the respective input fields
4. Click "Compare Races"
5. Review the results:
   - Matched athletes will be shown at the top
   - Complete lists of athletes from both races are shown below for verification

## Supported Race Result Websites

### UltraSignup
- Format: \`https://ultrasignup.com/results_event.aspx?did=XXXXX\`
- Example: \`https://ultrasignup.com/results_event.aspx?did=103984\`

### Pacific Multisports
- Format: \`https://register.pacificmultisports.com/Events/Results/XXXX\`
- Example: \`https://register.pacificmultisports.com/Events/Results/1171\`

## Technical Details

- Built with Node.js and Express
- Uses Puppeteer for web scraping
- EJS templating for the frontend
- Bootstrap for styling

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the ISC License.

## Acknowledgments

- Thanks to UltraSignup and Pacific Multisports for providing race results
- Built with support from the trail and ultra running community

## Support

If you encounter any issues or have questions, please open an issue on GitHub. 