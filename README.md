# CSV Fetcher and Viewer

## Description
This Ruby program allows you to fetch all CSV files from a specific directory, select one to display, and view its contents in a neatly formatted table. The program utilizes several classes, each responsible for specific functionality, such as fetching, selecting, reading, and displaying CSV files.

## Features
- **CSV File Fetcher**: Fetches all CSV files from a given directory.
- **File Selector**: Allows the user to select which CSV file to display.
- **CSV Reader**: Reads and parses the selected CSV file.
- **Table Displayer**: Displays the CSV content in a table format.

## Dependencies

This project requires the following Ruby gems:

- `tty-prompt`: For creating interactive prompts.
- `csv`: For reading and processing CSV files.
- `pry`: For debugging purposes.
- `terminal-table`: For displaying the CSV data in a table format.

### Install the required gems:
To install the necessary dependencies, run the following command:

```bash
gem install tty-prompt csv pry terminal-table
