# Date Table Query Repository

This repository contains an M-query script to generate a Date table in Power Query. The Date table provides a comprehensive set of date attributes that can be used for analysis and reporting purposes in Power BI.

## Date Table Query

The `DateTableQuery.m` file contains the M-query code for generating the Date table. The script takes a start date and end date as parameters and creates a table with various date attributes such as year, quarter, week number, month number, month name, day of the week, and national holiday.

### Usage

To incorporate this Date table query into Power BI from the Blank Query on Power Query Editor, follow these steps:

1. In Power BI Desktop, open the Power Query Editor by selecting "Edit Queries" from the "Home" tab.

2. In the Power Query Editor, click on "New Source" and select "Blank Query" to create a new blank query.

3. Open the Advanced Editor for the blank query by clicking on the "Advanced Editor" button in the "Home" tab.

4. Copy the content of the `DateTableQuery.m` file and paste it into the Advanced Editor.

5. Modify the parameters `StartDate` and `EndDate` in the script to specify the desired date range for the Date table. For example:

let
StartDate = #date(2010, 1, 1),
EndDate = #date(2023, 12, 31)
in
...

6. Click "Done" to close the Advanced Editor.

7. Power Query will process the script and generate the Date table.

8. Rename the query to something like "Date" for easy reference.

9. Close the Power Query Editor, and the Date table will be available in your Power BI report.

### Customization

Feel free to customize the script to fit your specific requirements. You can modify the date attributes, add additional columns, or incorporate data from external sources to enhance the Date table functionality.

### This M-Query was inspired by Kevin Knight
## License

This project is licensed under the [MIT License](LICENSE).
