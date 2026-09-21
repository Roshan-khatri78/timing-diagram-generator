# Timing Diagram Generator

A web-based tool for visualizing digital signal encoding modes used in communication systems.

## Features

- 13 encoding modes:
  - Unipolar NRZ
  - Polar NRZ-L, NRZ-I
  - Bipolar AMI, Pseudoternary, NRZ
  - 2B1Q, Manchester, Differential Manchester
  - Polar RZ, MLT-3, HDB3, B8ZS

- **Interactive visualization** with:
  - 🔴 Red signal waveform
  - 🔵 Cyan zero reference line
  - 🟡 Yellow bit labels

- Perfect square waves (true digital signals)
- Responsive dark theme design

## How to Use

1. Open [timing-diagram-generator](https://yourusername.github.io/timing-diagram-generator/)
2. Enter your binary sequence (e.g., `10110000100000000`)
3. Select an encoding mode
4. Click "Generate Diagram" or change mode to auto-update
5. View the timing diagram instantly

## Example

Input: `10110000`  
Mode: Polar NRZ-L  
Output: Clean square wave diagram showing signal transitions

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- SVG-based graphics for crisp rendering
- Works in all modern browsers
- Fully offline - no server needed

## Author

Created for digital communications coursework

## License

MIT License - Free to use and modify
