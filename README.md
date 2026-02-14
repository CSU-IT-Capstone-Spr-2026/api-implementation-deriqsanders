[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zN2AskmG)
# XKCD Comic Viewer

This application is a simple webpage that displays the latest XKCD comic. 
User has the ability to navigate between comics using a "Previous" and "Next" button.
User can click the "Random" button to display a random comic.

## Features Implemented

Check off the features you implemented (must have at least 4 and 2 are implemeted for you already):

- [X] Feature #1: Display the Latest Comic
- [X] Feature #2: Display a Specific Comic by Number
- [X] Feature #3: Random Comic Button
- [X] Feature #4: Navigation (Previous/Next)
- [ ] Feature #5: Search by Comic Number Form
- [ ] Feature #6: Display Multiple Recent Comics

## Technologies Used

- Python 3.8+
- Flask 3.0.0
- Requests 2.31.0
- XKCD API

## Installation and Setup

### Prerequisites
- Python 3.8 or higher installed
- pip (Python package manager)

### Steps to Run

1. Clone or download this repository

2. Navigate to the project directory in your terminal:
   ```
   cd projectName
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

5. Open your web browser and go to:
   ```
   http://localhost:5000
   ```

## Usage

User can click the "Previous" button to go to the previous issue.
User can click the "Random" button to see a random issue.
User can click the "Next" button to go to the next issue.

## Screenshots

<img width="849" height="913" alt="Screenshot 2026-02-13 at 7 09 36 PM" src="https://github.com/user-attachments/assets/98941915-b1cb-40b7-a44a-ef9b3e2161b5" />


## API Endpoints Used

- `GET /info.0.json` - Fetches the latest comic
- `GET /{comic_number}/info.0.json` - Fetches a specific comic by number

## Challenges and Solutions

[Write 2-3 paragraphs about:]

I did not have any previous experience with JSON or APIs.
The challenge I faced was learning how these tools work and implementing them-
to add function to the site. I also haven't been taught about HTTP methods-
and how to utlize them in code.

To solve my challenges I leveraged the interent.
I read documentation on Flask and HTML.
I used forums to help me solve some of the errors I received.
I've never bridged script to html so researched that as well.

I learned APIs are great for adding features to an application.
Theyre efficient as it eliminates having to code everything from scratch.
I learned about how to actully integrate an API into a application, and-
a real word use case.

## Future Improvements

If I had more time, I would add a search comic by number feature.

## Author

D'Eriq Sanders
