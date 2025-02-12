# UiPath Web Scraper for Coursera Course Listings

## Project Description
This project automates web scraping of **Coursera course listings** related to UiPath using **UiPath Studio**. The extracted data is saved in an **Excel file** for further analysis. The automation navigates to the Coursera search results page, extracts table data, and writes it to an Excel spreadsheet.

## Features
- **Automated Web Scraping**: Extracts UiPath-related course listings from Coursera.
- **Data Storage**: Saves extracted data in an Excel workbook.
- **UiPath Activities Used**:
  - `Use Application/Browser` – Opens Coursera and searches for courses.
  - `Extract Table Data` – Retrieves structured course information.
  - `Write Range Workbook` – Saves the extracted data into an Excel file.

## Project Structure
```
📂 UiPath-Coursera-Scraper
│── 📂 Main
│   │── Main.xaml  # UiPath workflow file
│   │── project.json  # UiPath project configuration
│── 📂 Screenshots
│   │── workflow_screenshot.png  # Example screenshot of UiPath project
│── README.md  # Project documentation
│── LICENSE  # License information
```

## Installation & Setup
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/UiPath-Coursera-Scraper.git
   ```
2. **Open in UiPath Studio**:
   - Launch UiPath Studio.
   - Open the **Main.xaml** file.
3. **Run the Automation**:
   - Ensure you have a stable internet connection.
   - Click **Run** to start scraping Coursera for UiPath courses.
4. **View the Extracted Data**:
   - The data will be saved in an Excel file at:
     ```
     C:\Users\Mike\OneDrive\Documents\UiPath Courses.xlsx
     ```

## Potential Enhancements
- Expand scraping to **other online course platforms**.
- Implement **error handling** and logging.
- Schedule automation using **UiPath Orchestrator**.
- Convert extracted data into **a structured database** for better analysis.

## License
This project is licensed under the **MIT License**.

## Contribution
Feel free to fork this repository, submit issues, or contribute to its improvement by submitting pull requests.
