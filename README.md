**WCAG Theme Inspector**

**💡 Overview**

The WCAG Theme Inspector is a single-file, interactive web application designed to help designers and developers test and refine color palettes against WCAG (Web Content Accessibility Guidelines) 2.x Contrast Requirements.

It allows users to adjust core theme colors in real-time and immediately see the resulting visual appearance and accessibility compliance status (AA/AAA Pass or Fail). This ensures high legibility and contrast for end-users, especially those with visual impairments.

**✨ Key Features**

This tool provides granular control and real-time feedback for critical design components:

7-Point Color Control: Simultaneously tune seven fundamental theme colors, including Page Background, Card Background, Body Text, Headings, Links, Button Accents, and Card Borders.

Live WCAG Contrast Checks: Displays the contrast ratio and compliance status (AA/AAA) in real-time for the two most critical pairs:

Body Text vs. Card Background

Link Color vs. Card Background

Compliance Indicators: Clearly shows whether the current color combination achieves the AA Pass (4.5:1 minimum ratio) or the AAA Pass (7.0:1 minimum ratio).

Color Presets: Quickly apply professional, pre-tested color schemes (e.g., Midnight Glow, Solar Flare) to rapidly switch between dark and light themes.

Font Selector: Test the legibility of content using different typefaces (e.g., Sans-serif, Serif, Monospace).

**🚀 How to Use**

Since the entire application is self-contained within one HTML file, usage is extremely simple:

Save the file: Save the index.html content to your local computer.

Open in Browser: Drag and drop the index.html file into any modern web browser (Chrome, Firefox, Edge, etc.).

Start Inspecting: Use the color pickers in the fixed header bar to adjust the theme. Observe how the components below and the WCAG status indicators change instantly.

**WCAG Theme Inspector**

The tool primarily verifies compliance with WCAG 2.x Success Criterion 1.4.3 (Contrast Minimum), which applies to normal-sized text:

Level

Minimum Contrast Ratio

Purpose

AA

4.5:1

The industry standard for legal and general web accessibility compliance.

AAA

7.0:1

Enhanced contrast, often used for content aimed at users with low vision.

**Note:** The contrast check automatically calculates the optimal text color (white or black) for the Primary Button Accent color to ensure maximum button contrast.

**📄 File Structure**
The project consists of a single file, utilizing Tailwind CSS for styling and vanilla JavaScript for logic and theme application.


index.html: Contains all the HTML structure, CSS styling (including variable definitions), and JavaScript logic.


