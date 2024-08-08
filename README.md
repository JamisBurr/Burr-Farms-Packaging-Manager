# Burr Farms Packaging Manager

Burr Farms Packaging Manager is a comprehensive tool designed to help farm managers track and manage their packaging inventory efficiently. The application allows users to add new bag types, adjust inventory levels, set minimum thresholds, and export data to Excel. With support for both light and dark modes, the application is user-friendly and adaptable to various lighting conditions.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Adding a New Bag Type](#adding-a-new-bag-type)
  - [Adjusting Inventory](#adjusting-inventory)
  - [Setting Minimum Thresholds](#setting-minimum-thresholds)
  - [Exporting Data to Excel](#exporting-data-to-excel)
  - [Enabling Dark Mode](#enabling-dark-mode)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Features
- **Add and Remove Bag Types:** Easily manage different types of packaging materials.
- **Adjust Inventory Levels:** Update inventory levels based on usage and new stock.
- **Set and Display Minimum Thresholds:** Ensure inventory levels do not drop below critical levels.
- **Export to Excel:** Generate Excel reports for inventory data.
- **Dark Mode Support:** Switch between light and dark modes for better visibility.

## Installation
1. **Download the Latest Release:**
   - Go to the [GitHub Releases page](https://github.com/yourusername/Burr_Farms_Packaging_Manager/releases).
   - Download the latest release package.

2. **Extract Files:**
   - Extract the downloaded ZIP file to a directory of your choice.

3. **Run the Application:**
   - Navigate to the extracted directory.
   - Run `Burr_Farms_Packaging_Manager.exe`.

## Usage

### Adding a New Bag Type
1. Open the application.
2. In the `New Type` text box, enter the name of the new bag type.
3. Click the `Add Type` button.
4. The new type will appear in the dropdown list of bag types.

### Adjusting Inventory
1. Select a bag type from the dropdown list.
2. To add inventory:
   - Enter the amount in the `Amount Added` text box.
   - Click the `Add` button.
3. To subtract inventory:
   - Enter the amount in the `Amount Used` text box.
   - Click the `Subtract` button.
4. The `Current Inventory` label will update to reflect the changes.

### Setting Minimum Thresholds
1. Select a bag type from the dropdown list.
2. Enter the desired minimum threshold in the `Min Threshold` text box.
3. Click the `Set Min` button.
4. The `Minimum Threshold` label will update to show the new threshold.
5. If the current inventory is below the minimum threshold, the `Current Inventory` label will turn red, and a low inventory notification will be displayed.

### Setting Reorder Amount
1. Select a bag type from the dropdown list.
2. Enter the desired reorder amount in the `Reorder Amount` text box.
3. Click the `Set Reorder` button.
4. The `Reorder Amount` label will update to show the new reorder amount.

### Exporting Data to Excel
1. Click the `Export to Excel` button.
2. In the save dialog, choose a location and file name for the Excel file.
3. Click `Save`.
4. The inventory data will be exported to the specified Excel file.

### Enabling Dark Mode
1. Check the `Dark Mode` checkbox to enable dark mode.
2. Uncheck the `Dark Mode` checkbox to switch back to light mode.

## Contributing
Contributions are welcome! If you have suggestions for improvements, feel free to open an issue or submit a pull request on GitHub.

## License
This program is licensed under the [GNU General Public License v3.0](LICENSE).

## Author
Jamis Burr
