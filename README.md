🎨 Universal Color Palette & WCAG Contrast Tester


<img width="806" height="608" alt="image" src="https://github.com/user-attachments/assets/6c640ca3-fe8a-443c-9580-c2fd9269af33" />

This is a portable, single-file web application built with Vanilla JavaScript and HTML that functions as a tool for designers and developers. It allows users to generate harmonious color palettes from a base color and instantly test the contrast ratio of any color pair against WCAG (Web Content Accessibility Guidelines) standards.

✨ Key Features

Palette Generation: Instantly generates a five-color palette based on standard color theory principles:

Analogous (Harmonious)

Complementary (High Contrast)

Triadic (Balanced)

Shades (Monochromatic Tints/Shades)

Drag-and-Drop Testing: Users can drag any generated color swatch directly into the dedicated Foreground or Background slots in the tester panel.

Real-time WCAG Compliance: Calculates and displays the precise Contrast Ratio (e.g., 4.5:1) and immediately checks against required WCAG thresholds:

AA (Normal Text): Requires a ratio of 4.5:1 or higher.

AAA (Normal Text): Requires a ratio of 7.0:1 or higher.

Color Conversion Utility: Uses core JavaScript functions for robust color conversions between HEX, RGB, and HSL to ensure accurate palette generation and luminance calculations.

▶️ How to Use

The application is entirely self-contained within the HTML file.

Enter Base Color: In the Base Color Input panel, enter a HEX code (e.g., #3b82f6) or use the color preview box.

Generate Palette: Select a method (Analogous, Complementary, etc.) and click Generate Palette. The swatches will appear in the visualization panel.

Test Contrast:

Drag a color swatch from the Generated Palette into the desired Foreground Color slot.

Drag a second color swatch into the Background Color slot.

Review Results: The WCAG Contrast Tester area updates instantly, showing the calculated ratio and a clear PASS/FAIL status for WCAG AA and AAA compliance.

⚙️ Technology Stack

HTML5 & CSS: Core application structure and custom styling for controls.

Vanilla JavaScript (ES6): All functional logic, including color theory math (hslToRgb, rgbToHsl), luminance calculation (getLuminance), and drag-and-drop handlers.

Tailwind CSS (CDN): Utility-first framework used for clean layout, responsiveness, and aesthetic styling.
