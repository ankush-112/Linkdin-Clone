# LinkedIn Clone

A simplified LinkedIn profile clone that enables users to view, edit, and update their professional profile information. This project focuses on user interactivity and data persistence within the browser.

## Features

- **Responsive Design:** Replicates LinkedIn’s profile page layout for a familiar user experience.
- **Profile Management:** Users can edit core profile details like name, headline, location, and about section.
- **Dynamic Sections:** Add, edit, or remove entries in experience, education, and skills.
- **Profile Photo Upload:** Supports profile photo uploads.
- **Data Persistence:** Changes are automatically saved using `localStorage` and persist across sessions.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/ankush-112/Linkdin-Clone
   ```
2. Navigate into the project directory:
   ```bash
   cd linkedin-clone
   ```
3. Open the `index.html` file in your preferred web browser.

## Usage

- Click the edit icons next to profile sections to update information.
- Add new entries in the Experience, Education, or Skills sections using the "+" buttons.
- Upload a new profile image by clicking on the existing photo.
- All changes are automatically saved in `localStorage` for persistence across browser sessions.

## Project Structure

- **index.html**: Contains the structure and content of the profile page.
- **CSS**: Inline styles are used in the HTML, with plans to modularize it in future updates.
- **JavaScript**: All interactive functionality is written in vanilla JavaScript within the HTML’s `<script>` tag.

## Future Improvements

- Separate CSS and JavaScript into external files for improved maintainability.
- Add a backend server for secure data storage.
- Implement authentication to support multiple users.
- Expand the feature set to include connections, posts, and messaging.
- Improve design responsiveness and accessibility across all devices.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for new features or bug fixes.
