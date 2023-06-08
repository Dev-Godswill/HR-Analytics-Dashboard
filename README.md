# <a name="hr-dashboard"></a> HR-Analytics-Dashboard

## Table of Contents
- [HR Dashboard](#hr-dashboard)
- [Project Description](#project-description) 
- [How to Use](#how-to-use)
- [Prerequisites](#prerequisites)
- [Wireframe](#wireframe)
- [Screenshots](#screenshots)
- [Dataset](#dataset)
- [Usage](#usage)
- [Contributing](#contributing)

## <a name="project-description"></a> Project Description
This project is an HR Analytics Dashboard built using Excel. It provides insights and visualizations based on a dataset using various Excel features and functions such as Power Query, DAX, VLookup, Macro, VBA, IF, IFERROR, and Pivot Tables.

<img width="722" alt="HR Analytics Excel Dashboard" src="https://github.com/Dev-Godswill/HR-Analytics-Dashboard/assets/99620725/78965f7d-7f23-4c82-830e-e2af53115a85">

**Functions Used:**
1. **Merged Dataset:** The dataset provided was merged into a single file using Power Query. This consolidation simplifies data management and enhances the performance of the dashboard.
2. **DAX (Data Analysis Expressions):** DAX is a formula language used in Power Pivot, Power BI, and Analysis Services to create custom calculations and expressions. In the context of this project, DAX was useful for performing complex calculations, creating calculated columns and measures, and generating meaningful insights from the data.
3. **VLOOKUP:** VLOOKUP is an Excel function that allows you to search for a value in a specific column of a dataset and retrieve a corresponding value from another column. It is commonly used for data lookup and retrieval tasks. In this context, VLOOKUP was utilized to search for employee information based on their ID and retrieve relevant details.
4. **Macro and VBA (Visual Basic for Applications):** Macros and VBA are used to automate repetitive tasks in Excel and add custom functionality to your spreadsheet. In the context of this dashboard, macros and VBA were used to automate certain processes, such as _Clear Filters_ which aided in resetting the dashboard when clicked. 
5. **IF and IFERROR:** The IF function in Excel allows you to perform logical tests and return different values based on the results. IFERROR is a function that captures errors and provides alternative values or actions. In this dashboard, this functions were used to handle error messages when invalid or non-existent employee IDs are entered or to conditionally display certain information based on specific criteria.
6. **Pivot Tables:** Pivot Tables are powerful tools in Excel for summarizing and analyzing large datasets. They allow you to quickly create cross-tabulations, perform calculations, and generate interactive reports. In this HR Analytics Dashboard, Pivot Tables were used to provide aggregated insights, perform data exploration, and create dynamic visualizations based on various dimensions and measures.

**Features:**
1. **Real-time Date/Time:** The dashboard displays the current date and time, ensuring that the information is always up to date. 
2. **Employee Search:** The dashboard includes a search bar where users can search for an employee using their Employee ID. If an Employee ID that doesn't exist is entered, an error message ("Employee ID not found, retry") is displayed. Although the dataset primarily contains Employee IDs, the same search functionality can extended for users to search for an employee by their name.

## How to Use
1. Download the Excel file from this repository. 
2. Open the Excel file using Microsoft Excel. 
3. Ensure that macros are enabled to fully utilize the dashboard's features. 
4. Navigate to the dashboard worksheet. 
5. Use the search bar to find an employee by entering their Employee ID or name. 
6. Explore the various visualizations and insights provided on the dashboard. 
7. Enjoy using the HR Analytics Dashboard!

## Prerequisites
To successfully run the HR Analytics Dashboard, you need:
1. Microsoft Excel (version 2016 or above) 
2. Macros enabled in Excel

## Wireframe
[Wireframe Link](https://excalidraw.com/#json=B8vH0U3qIr6CYTxXPqFYs,U77Qt4PPl_tKWaaEavTayg)

## Screenshots
![ezgif com-video-to-gif](https://github.com/Dev-Godswill/HR-Analytics-Dashboard/assets/99620725/203fb66f-2322-4af1-99df-e3e54b6d3f10)

## Dataset
The Dataset used contained employee data from 2015-2018.

## Contributing
Contributions to the HR Analytics Dashboard project are welcome! If you'd like to contribute, please follow these steps:
- Fork the project repository. 
- Create a new branch: git checkout -b feature/your-feature-name. 
- Make your changes and commit them: git commit -am 'Add your commit message'. 
- Push the changes to your branch: git push origin feature/your-feature-name. 
- Submit a pull request detailing your changes.

*Feel free to modify and adapt the project to your needs. If you have any questions or suggestions, please feel free to contact me: GodswillTheAnalyst@gmail.com*.
