# Constellation Star Map 🌟

A Python application that generates and visualizes random constellations on a star map. This project creates an interactive astronomy-themed visualization by plotting random stars and connecting them with constellation lines.

## Features

- **Random Star Generation**: Creates a field of randomly positioned stars
- **Constellation Linking**: Automatically connects random stars to form constellation patterns
- **Dark Sky Visualization**: Displays stars against a dark background for authentic night sky appearance
- **Interactive Display**: Uses matplotlib for visualization

## Prerequisites

- Python 3.7+
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/abuhanif254/Constellation-Star-Map-Using-Python.git
cd Constellation-Star-Map
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

Or install manually:
```bash
pip install matplotlib numpy
```

## Usage

Run the application:
```bash
python main.py
```

This will generate a random constellation map with:
- 30 randomly positioned stars
- 10 random constellation connections
- A dark background for realistic sky appearance

## Project Structure

```
Constellation Star Map/
├── main.py              # Main application script
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
```

## Dependencies

- **matplotlib**: Visualization and plotting library
- **numpy**: Numerical computing library for random star generation

## How It Works

1. Generates 30 random star coordinates within a 100x100 space
2. Creates 10 random constellation lines by connecting pairs of stars
3. Displays the result with white stars and yellow constellation lines on a black background

## Customization

You can modify the following in `main.py`:
- Number of stars: Change `np.random.rand(30)`
- Number of constellation lines: Change `range(10)`
- Star color: Modify `color="white"`
- Line color: Modify `"yellow"`
- Background color: Modify `set_facecolor("black")`

## Future Enhancements

- [ ] Load real constellation data
- [ ] Add interactive mouse features
- [ ] Implement zoom and pan capabilities
- [ ] Save generated maps as images
- [ ] Add constellation naming system
- [ ] Performance improvements for larger star counts

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Author

Created with ✨ for astronomy enthusiasts

## Support

For issues, questions, or suggestions, please open an [Issue](https://github.com/yourusername/Constellation-Star-Map/issues) on GitHub.

---

**Enjoy exploring your random constellations!** 🌙✨
