# Toastmasters Meeting Agenda Generator

A web-based tool to generate and customize meeting agendas for  Toastmasters clubs. This tool allows you to create, edit, and download  agendas in PDF or high-quality image formats.

Demo - https://rahulkg31.github.io/toastmasters-agenda-generator/

![Toastmasters Agenda Generator](https://raw.githubusercontent.com/rahulkg31/toastmasters-agenda-generator/main/logo.png)

## Features

- **Dynamic Agenda Generation**: Automatically generates a meeting agenda based on user input.
- **Editable Fields**: Double-click on any cell to edit its content.
- **Context Menu**: Right-click on rows or sections to duplicate, delete, or move them.
- **Download Options**:
  - Download the agenda as a **PDF**.
  - Download the agenda as a **high-quality image**.
- **Customizable Time Allocation**: Adjust time allocations for each agenda item.
- **Role Player Assignments**: Assign roles to members and automatically populate the agenda.

## How to Use

1. **Input Meeting Details**:

   - Fill in the editable div with your club name, meeting details, and role players.

   - Example format:

     ```yaml
     Club Name: MILLENNIUM CITY TOASTMASTERS CLUB
     Club Address: Division H, Area 3, Club No. 03321031 | Shriram Wonder Years School, Sector 46, Gurgaon
     Meeting Number: 588
     Meeting Date: 09-02-2025
     Meeting Start Time: 10:30 AM
     Meeting End Time: 12:45 PM
     Meeting Theme: Speeches, Table Topics & Evaluations
     
     Sergeant at Arms: TM Open
     Presiding Officer: TM Open
     Toastmaster of The Day: TM Open
     Joke Master: TM Open
     General Evaluator: TM Open
     Table Topics Master: TM Open
     Table Topics Evaluator: TM Open
     Timer: TM Open
     Ah Counter: TM Open
     Grammarian: TM Open
     Speaker: TM Open, TM Open, TM Open
     Evaluator: TM Open, TM Open, TM Open
     ```

2. **Generate Agenda**:

   - Click the **"Generate Agenda"** button to create the agenda.

3. **Edit Agenda**:

   - Double-click any cell to edit its content.
   - Right-click on rows or sections to:
     - Duplicate
     - Delete
     - Move up or down

4. **Download Agenda**:

   - Click **"Download Image"** to save the agenda as a high-quality PNG.
   - Click **"Download PDF"** to save the agenda as a PDF.

## Installation

No installation is required! Simply open the `index.html` file in your browser to use the tool.

Alternatively, you can host it on a web server or use it as a static website.

## Technologies Used

- **HTML5**: Structure of the web page.
- **CSS3**: Styling and layout.
- **JavaScript**: Dynamic functionality and interactivity.
- **html2canvas**: Converts the agenda table to an image.
- **jsPDF**: Generates PDFs from the agenda.

## License

This project is licensed under the MIT License. See the [LICENSE](https://chat.deepseek.com/a/chat/s/LICENSE) file for details.
