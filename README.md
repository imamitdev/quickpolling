# Quick Polling App

This is a simple polling application built using Django that allows users to create, view, and participate in polls. The app implements user authentication, poll creation with choices, poll listing, participation, and result display with AJAX for a smoother user experience.

<video width="320" height="240" src="https://github.com/imamitdev/quickpolling/blob/main/www_screencapture_com_2024-4-11_16_52.mp4" controls>
  <source src="https://github.com/imamitdev/quickpolling/blob/main/www_screencapture_com_2024-4-11_16_52.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Features

- **User Authentication**
  - Sign up, log in, and log out functionality for users.
  - Only authenticated users can create, view, and participate in polls.

- **Poll Creation**
  - Authenticated users can create new polls with a question and multiple choices.
  - Optional deadline setting for polls.

- **Poll Listing**
  - All users can view a list of available polls displaying the question, choices, and deadline (if set).
  - Pagination for better usability with a large number of polls.

- **Poll Participation**
  - Authenticated users can select a choice and submit their vote for a poll.
  - Users cannot vote on polls after the deadline (if set).

- **Results Display**
  - After voting, users can view the results of the poll including the percentage of votes for each choice.

- **Admin Interface**
  - Admin users have access to manage polls and user accounts via Django's built-in admin interface.

## Installation

1. Clone the repository:

   ```bash
     git clone https://github.com/yourusername/quick-polling-app.git
   ```

2. Navigate into the project directory:
  
  ```bash
    cd quick-polling-app
  ```

3. Create a virtual environment:

  ```bash
    python3 -m venv venv
  ```
