# Anime Time Limit Calculator

A magical, anime-themed countdown timer web application that brings the spirit of your favorite shows to time management. Whether you're tracking episode runtimes, study sessions, or just want a stylish way to count down, this tool has you covered.

![Anime Time Limit Calculator Preview](https://via.placeholder.com/800x400/1a1f3a/bd93f9?text=Anime+Time+Limit+Calculator)

## Features

- **Dual Time Input**: Set minutes and seconds independently for precise countdowns
- **Real-time Countdown**: Live updating display with hours, minutes, and seconds
- **Dynamic Messages**: Context-aware anime quotes and messages that change as time runs out
- **Immersive Design**: 
  - Gradient backgrounds with floating sparkle animations
  - Glowing neon effects and soft shadows
  - Anime-inspired corner decorations
  - Responsive layout that works on all devices
- **Easy Controls**: Start and reset functionality with smooth animations
- **Interactive Feedback**: Visual and textual cues as the countdown progresses

## Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/anime-time-limit-calculator.git
```

2. **Open the application**
- Simply open `index.html` in your favorite web browser
- No build process or dependencies required

3. **Start counting down**
- Enter your desired time in minutes (and optional seconds)
- Click "START COUNTDOWN" to begin
- Watch the magical countdown unfold

## How to Use

1. **Set Your Time Limit**
   - **Minutes**: Enter the main duration (e.g., 24 for a typical anime episode)
   - **Seconds**: Add extra seconds (0-59) for precision

2. **Control the Timer**
   - **START COUNTDOWN**: Begins the countdown with your entered time
   - **RESET**: Stops current timer and returns to the original set time

3. **Watch the Magic Happen**
   - The display shows hours, minutes, and seconds remaining
   - Messages and quotes change based on remaining time:
     - "TIME'S UP" when countdown finishes
     - "FINAL COUNTDOWN" for last minute
     - "less than 5 minutes left" for urgency
     - Various encouraging messages throughout

## Technical Details

### Built With
- **HTML5** - Structure and semantics
- **CSS3** - Animations, gradients, and responsive design
- **Vanilla JavaScript** - No frameworks, pure functionality

### Key Features Implementation
- **Countdown Logic**: Precise second-by-second updates with clear interval management
- **Input Validation**: Automatic clamping of seconds (0-59) and non-negative minutes
- **Dynamic UI**: Real-time updates to display and messages based on remaining time
- **Responsive Design**: Flexbox layouts that adapt to any screen size

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Customization

### Adding Your Own Anime Quotes
Find the `quotes` array in the JavaScript section (around line 250) and add your favorites:

```javascript
const quotes = [
    "Your custom quote here.",
    "Another inspiring line.",
    // Add more quotes...
];
```

### Modifying Colors
The color scheme uses CSS variables and gradients. Key colors can be adjusted in the `:root` or directly in the styles:

```css
background: linear-gradient(145deg, #0b0c1e 0%, #1a1f3a 100%); /* Main gradient */
border-color: #c2a2ff; /* Accent color */
box-shadow: 0 0 25px #b87cf7; /* Glow effect */
```

## Responsive Design

The calculator is fully responsive and optimized for:
- **Desktop**: Full experience with all visual effects
- **Tablet**: Adjusted spacing and font sizes
- **Mobile**: Compact layout with readable typography

## Contributing

Contributions are welcome. Feel free to:
- Add more anime quotes
- Enhance animations
- Improve accessibility
- Fix bugs or optimize performance

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Inspired by the magical world of anime and its sense of urgency and adventure
- Font thanks to Google Fonts (Poppins)
- Special thanks to all anime creators who inspire us daily

## Future Enhancements

Planned features for future releases:
- Save favorite time presets
- Multiple timer instances
- Sound effects at critical moments
- Theme customization (different anime genres)
- Pause functionality
- Share countdowns with friends
