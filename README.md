# DesignMockupForPak

A modern UI mockup for the Goinfo packaging management system, designed for warehouse and inventory operations.

## Overview

This project contains a responsive HTML mockup for a warehouse management interface focused on packaging operations. The interface provides tools for reading, managing, and processing inventory data with an intuitive user experience.

## Features

### User Interface
- **Top Navigation Bar**: User information, company details, and quick access icons
- **Action Toolbar**: Primary action buttons for reading, deleting, and logistics operations
- **Data Table**: Responsive table with column visibility controls
- **Toast Notifications**: Real-time feedback for user actions

### Key Functionalities
- ✅ **Data Operations**: Read, delete, and process inventory items
- 🔍 **Filtering**: Barcode scanning and material type filtering
- 📊 **Column Management**: Toggle visibility of table columns
- 🏢 **Multi-location Support**: Support for different warehouse locations
- 📱 **Responsive Design**: Works on desktop and mobile devices

### Interactive Elements
- Action buttons with hover effects and click animations
- Dropdown menus for processing operations and view options
- Column visibility toggles
- Expandable/collapsible groups
- Move/resize functionality for data elements

## Technology Stack

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with flexbox layouts
- **Bootstrap 5.3.3**: Responsive framework and components
- **Bootstrap Icons 1.10.5**: Icon library
- **JavaScript**: Interactive functionality and DOM manipulation

## File Structure

```
DesignMockupForPak/
├── README.md
└── paste.txt (main HTML file)
```

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/DesignMockupForPak.git
   cd DesignMockupForPak
   ```

2. **Open the mockup**:
   - Simply open `paste.txt` (rename to `index.html` if desired) in your web browser
   - No build process or server required

3. **View the interface**:
   - The mockup will load with a complete warehouse management interface
   - All interactive elements are functional for demonstration purposes

## Interface Sections

### Top Bar
- **User Info**: Current user and company information
- **System Info**: Active company and year
- **Quick Actions**: Messages, help, debug, security, settings, home, and logout

### Toolbar
- **Primary Actions**: Read, Delete, Internal Logistics Review
- **Processing Menu**: Dropdown with unpacking and other operations
- **View Controls**: Column visibility toggles
- **Filters**: Barcode input, material type, and location selectors

### Data Table
- **Column Headers**: Pak/Pos, Quantity Location, Ident, Name
- **Empty State**: Informative message when no data is available
- **Table Controls**: Edit, download, move, and group expansion options

## Customization

### Styling
- Modify CSS variables in the `<style>` section for colors and spacing
- Bootstrap classes can be adjusted for different responsive behaviors
- Icon classes can be changed using Bootstrap Icons documentation

### Functionality
- JavaScript event listeners can be extended for additional features
- Toast notifications can be customized with different messages and colors
- Form validation can be added to input fields

## Browser Support

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

## Language

The interface is designed in Slovenian (Slovene) for local warehouse operations, but can be easily translated by modifying the text content.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is available as a design mockup for educational and demonstration purposes.

## Screenshots

The interface includes:
- Clean, professional warehouse management layout
- Responsive design that works on various screen sizes
- Interactive elements with visual feedback
- Modern Bootstrap-based styling

---

**Note**: This is a UI mockup designed for demonstration purposes. For production use, backend integration and additional security measures would be required.
