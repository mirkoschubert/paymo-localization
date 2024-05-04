# Missing Strings

## In General

Some of the localization strings are automatically capitalized in the UI. In some languages (like German) it would be wrong to do this.

*It may be a lack of localization in the code, as some of the stings are actually in the JSON files. Some of the strings may also be case sensitive.

## Home

### My Day

- My Day
- Have a look at your day, {name}
- Tasks due today
- Display*
- Awesome job! No more tasks due today.
- Today's timesheet

### My Tasks & Team's Tasks

- List*
- Table*
- Board*
- Calendar*

### Dashboard

The translated months are missing in the `Time` and `Finance` graphs.

## Clients

### Client Settings

- Default Project Color

### Overview

The translated months are missing in the invoices chart.

- Invoice Number*
- There are no invoices for this client yet.

### Contacts

### Projects

- Add Project*
- Select Numer Interval (Filter)
- Worked From Total*
- Created on*
- More Settings
- Columns*
- Density

### Timesheet

The abbreviations of the days of the week in German have only two characters. I don't know about other languages, but you might want to consider setting separate localization strings for abbreviated weekdays.

- Add Time Entry
- Select Project*
- Select Task*
- Active timers*


### Invoices

- More Settings
- Columns*
- Density

## Projects

- Add Project*

### Project Settings

- Threshold

### Overview

The string "open" has two meanings in this application:

1. "öffnen" as a verb, like "open something".
2. "offen" as an adjective like "an outstanding bill or task".

For the translation I suggest to use the single "open" only as an adjective like in "open tasks" in the project overview. If you use "open" as a verb, you should define what the user will open, like "open file". I didn't changed the translation yet.

The month translation is missing in the chart.

- There are no milestones for this project yet.
- Reserve
- Active*
- Proposal*
- On-hold*
- Cancelled*
- Completed*
- Archived*
- Archive Project*

### Tasks

Note: The strings of the view selection are only translated in the Gantt view.

- Est. Billable Amount
- Est. Cost
- List*
- Table*
- Board*
- Calendar*
- Gantt*
- Plan your project in advance
- Set up dependencies between tasks and identify which are the most critical ones for your project with the Gantt Chart view.
- Upgrade Plan

New Task:

- Create a new Task*
- Upload From
- Start - End Dates
- Select Date Interval
- Create Task*





### Milestones

### Timesheet

### Finances

### Files

### Discussion

### Activity Feed


## People

## Accounting

### Invoices

Create invoice:

- Add empty row*
- Invoice notes*
- Created using
- Internal notes*

Single Invoice:

- Total Payments
- Add new Payment*
- Link with Projects
- More Settings
- Columns*
- Density
- paid (on the invoice)
- Attached timesheet reports*

Timesheet Report:

- Report for Invoice
- Created by {name}
- Clients:
- Projects:
- Users:
- Time interval:
- Total
- Hours




