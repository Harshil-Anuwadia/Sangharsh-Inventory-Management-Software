# Sangharsh Delivery Challan

![Sangharsh Logo](https://github.com/Harshil-Anuwadia/Sangharsh-Inventory-Management-Software/blob/main/logo.png?raw=true)

An advanced desktop application designed specifically for Sangharsh Machinery to create, manage, and export delivery challans with a modern, user-friendly interface.

## Features

- **Modern UI/UX**: Clean, intuitive interface with Sangharsh's orange brand color theme
- **Offline Operation**: Works completely offline, with no database required
- **JSON Storage**: All data is stored in JSON files for simplicity and portability
- **Dashboard**: View statistics on total challans, pending deliveries, etc.
- **Create Challan**: Comprehensive form for creating new challans
- **View Challans**: Filter, search, and manage existing challans
- **Manage Parties**: Add, edit, and delete parties/clients
- **Inventory Management**: Track items, stock levels, and prices
- **PDF Export**: Generate professional PDF documents from challans
- **Settings**: Configure application preferences, company details, and more
- **Dark/Light Mode**: Toggle between light and dark themes
- **Responsive Design**: Works on various screen resolutions

## System Requirements

- Windows 10 or higher (64-bit recommended)
- 4GB RAM or higher
- 100MB available disk space
- 1280x720 screen resolution or higher

## Installation

### From Installer (Recommended)

1. Download the latest installer from the releases page
2. Run the installer and follow the on-screen instructions
3. Launch the application from the desktop shortcut or Start menu

### From Source

1. Ensure you have Python 3.8 or higher installed
2. Clone this repository:
   ```
   git clone https://github.com/yourusername/sangharsh-delivery-challan.git
   cd sangharsh-delivery-challan
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the application:
   ```
   python main.py
   ```

## Getting Started

1. Launch the application
2. On first run, go to Settings to configure your company details
3. Start creating challans by clicking "Create Challan" in the sidebar

### Key Initial Setup

- Configure your company information in Settings
- Upload your logo for professional-looking challan PDFs
- Set up your preferred challan numbering format
- Create parties/clients you frequently work with

## Data Management

All data is stored locally on your computer:

- Application data: Installation directory
- User data: `data/` directory
- PDF exports: Your Documents folder by default (configurable in Settings)

## Backup & Restore

- Enable automatic backups in Settings > Application Settings
- Configure a backup location in Settings
- Perform manual backups before major updates or periodically

## Keyboard Shortcuts

- Ctrl+N: Create new challan
- Ctrl+S: Save changes
- Ctrl+P: Print/Export challan
- Ctrl+F: Search
- F1: Help

## Building Executable

To create a standalone executable for Windows:

```
python -m pip install -r requirements.txt
python -m PyInstaller --onefile --windowed --icon=logo.ico --name="Sangharsh Delivery Challan" main.py
```

Alternatively, use the included build.bat script:

```
build.bat
```

## Troubleshooting

If you encounter issues with the application, please see the TROUBLESHOOTING.md file for common problems and solutions.

## Support & Contact

For technical support or inquiries, please contact:

- Email: harshilanuwadia97@gmail.com

## License

This software is proprietary and owned by Sangharsh company. Unauthorized copying, distribution, or modification is prohibited. 
