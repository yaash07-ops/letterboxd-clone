# letterboxd-clone
# 🎬 CineLog — Movie Diary & Review App

## 📌 Project Overview

**CineLog** is a web-based movie diary and review application inspired by modern movie-tracking platforms.

The application allows users to:

* 🎬 Browse movies
* 🔍 Search for movies
* 🎭 Filter movies by genre
* ⭐ View movie ratings
* 📝 Write and view reviews
* ❤️ Add movies to a watchlist
* 👤 View profile statistics
* 💾 Store reviews and watchlist data using browser LocalStorage

This project was developed as a **6-member team project** using HTML, CSS and JavaScript, with Git and GitHub used for collaborative development.

> **Note:** CineLog is an original educational project inspired by movie diary/review applications. It is not affiliated with or a copy of Letterboxd.

---

# 👥 Team Members & Responsibilities

| Member       | Role                          | Main Responsibility                                | Branch              |
| ------------ | ----------------------------- | -------------------------------------------------- | ------------------- |
| **Member 1** | Team Leader / Integration     | GitHub management, integration and final merging   | `main`              |
| **Member 2** | UI / Frontend Developer       | HTML structure, CSS styling and responsive design  | `feature/ui`        |
| **Member 3** | Movie Developer               | Movie catalogue, search, filters and movie details | `feature/movies`    |
| **Member 4** | Rating & Review Developer     | Ratings, reviews and review storage                | `feature/reviews`   |
| **Member 5** | Watchlist & Profile Developer | Watchlist and profile statistics                   | `feature/watchlist` |
| **Member 6** | Testing & Documentation       | Testing, README and project documentation          | `docs/testing`      |

---

# ✨ Features

## 🎬 Movie Catalogue

Users can browse a collection of movies with:

* Movie title
* Release year
* Genre
* Community rating
* Movie description

---

## 🔍 Movie Search

Users can search movies by:

* Movie title
* Genre

Example:

```text
Interstellar
Action
Drama
Sci-Fi
```

---

## 🎭 Genre Filter

Movies can be filtered according to genre.

Available genres include:

* Sci-Fi
* Drama
* Action
* Comedy
* Thriller

---

## ⭐ Movie Ratings

Each movie displays a community rating.

Example:

```text
★★★★★ 4.6
```

Users can also submit their own star rating when writing a review.

---

## 📝 Reviews

Users can write reviews for movies.

Reviews contain:

* User name
* Star rating
* Review text
* Date

Reviews are stored using browser **LocalStorage**.

---

## ❤️ Watchlist

Users can add movies to their personal watchlist.

They can:

* Add a movie
* Remove a movie
* View saved movies

Watchlist information is stored in LocalStorage.

---

## 👤 Profile

The profile section displays basic statistics such as:

```text
Films reviewed
Number of reviews
```

---

# 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Storage

* Browser LocalStorage

### Development Tools

* Visual Studio Code
* Git
* GitHub

---

# 📁 Project Structure

```text
CineLog/
│
├── index.html
│
├── style.css
│
├── README.md
│
├── js/
│   ├── movies.js
│   ├── reviews.js
│   ├── watchlist.js
│   └── test.js
│
└── images/
```

---

# 📄 File Responsibilities

## `index.html`

Main webpage structure.

Contains:

* Navigation bar
* Home section
* Movie section
* Watchlist section
* Profile section
* Movie details modal

**Responsible Member:** Member 1 / Member 2

---

## `style.css`

Controls the appearance of the application.

Includes:

* Dark theme
* Navigation styling
* Movie cards
* Buttons
* Responsive layout
* Modal styling
* Profile styling

**Responsible Member:** Member 2

---

## `js/movies.js`

Handles movie-related functionality.

Includes:

* Movie data
* Movie cards
* Search
* Genre filtering
* Movie details

**Responsible Member:** Member 3

---

## `js/reviews.js`

Handles the review system.

Includes:

* Adding reviews
* Star ratings
* Displaying reviews
* LocalStorage
* Profile review statistics

**Responsible Member:** Member 4

---

## `js/watchlist.js`

Handles watchlist functionality.

Includes:

* Adding movies
* Removing movies
* Displaying saved movies
* Profile statistics
* LocalStorage

**Responsible Member:** Member 5

---

## `js/test.js`

Contains basic application tests.

Tests include:

* Movie data availability
* Watchlist functionality
* Review functionality

**Responsible Member:** Member 6

---

# 🚀 How to Run the Project

## Method 1 — Open Directly

Download or clone the repository.

Open:

```text
index.html
```

in a web browser.

---

## Method 2 — Using VS Code

Open the project folder in VS Code.

Install the **Live Server** extension if required.

Right-click:

```text
index.html
```

and select:

```text
Open with Live Server
```

The application will open in your browser.

---

# 🔧 GitHub Collaboration Workflow

The project uses Git branches so that each member can work independently.

```text
                         GitHub Repository
                                │
                              main
                                │
          ┌─────────────┬───────┴────────┬──────────────┐
          ↓             ↓                ↓              ↓
     feature/ui   feature/movies  feature/reviews  feature/watchlist
          │             │                │              │
       Member 2       Member 3         Member 4       Member 5
          │             │                │              │
          └─────────────┴────────────────┴──────────────┘
                                │
                         Pull Requests
                                ↓
                         Member 1 Review
                                ↓
                              Merge
                                ↓
                              main
```

---

# 🌿 Git Branches

The project uses the following branches:

```text
main
feature/ui
feature/movies
feature/reviews
feature/watchlist
docs/testing
```

---

# 👨‍💻 Git Commands

## Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/CineLog.git
```

Move into the project:

```bash
cd CineLog
```

---

## Create a branch

Example for the movie developer:

```bash
git checkout -b feature/movies
```

---

## Check changes

```bash
git status
```

---

## Add files

```bash
git add .
```

---

## Commit changes

```bash
git commit -m "Add movie catalogue and search"
```

---

## Push branch

```bash
git push -u origin feature/movies
```

---

# 🔀 Pull Request Process

After pushing a branch:

1. Open the GitHub repository.
2. Click **Compare & pull request**.
3. Select the feature branch.
4. Set the base branch to `main`.
5. Add a Pull Request title.
6. Describe the changes.
7. Create the Pull Request.
8. Member 1 reviews the code.
9. Member 1 approves the Pull Request.
10. Merge the Pull Request into `main`.

---

# 🧑‍🤝‍🧑 Member Contributions

## Member 1 — Team Leader / Integration

Responsibilities:

* Create GitHub repository
* Add collaborators
* Manage branches
* Review Pull Requests
* Resolve merge conflicts
* Integrate all modules
* Maintain the main branch
* Final project submission

---

## Member 2 — UI / Frontend Developer

Responsibilities:

* Design webpage layout
* Create navigation bar
* Design movie cards
* Create responsive interface
* Implement dark theme
* Style buttons and forms
* Maintain `style.css`

Main files:

```text
index.html
style.css
```

---

## Member 3 — Movie Developer

Responsibilities:

* Create movie dataset
* Display movies
* Implement search
* Implement genre filtering
* Create movie details section

Main file:

```text
js/movies.js
```

---

## Member 4 — Rating & Review Developer

Responsibilities:

* Create review functionality
* Implement star ratings
* Display reviews
* Store reviews
* Calculate review statistics

Main file:

```text
js/reviews.js
```

---

## Member 5 — Watchlist & Profile Developer

Responsibilities:

* Add movies to watchlist
* Remove movies from watchlist
* Display saved movies
* Implement LocalStorage
* Update profile statistics

Main file:

```text
js/watchlist.js
```

---

## Member 6 — Testing & Documentation

Responsibilities:

* Test application features
* Identify bugs
* Verify movie search
* Verify reviews
* Verify watchlist
* Maintain README
* Document project workflow

Main files:

```text
js/test.js
README.md
```

---

# 🧪 Testing

The application performs basic JavaScript checks using:

```javascript
console.assert()
```

The testing file checks that:

* Movie data exists
* Watchlist functions exist
* Review functions exist

Open the browser's developer console to view the test results.

---

# 💾 Data Storage

CineLog uses browser LocalStorage.

The following information can be stored locally:

```text
Reviews
Ratings
Watchlist
```

No external database is required for the current version.

---

# 🔒 Privacy

This educational version stores information only in the user's browser through LocalStorage.

No personal information is sent to an external server.

---

# 📱 Responsive Design

The application is designed to work on:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📱 Tablet

CSS media queries are used to adjust the layout for smaller screens.

---

# 🎯 Project Objectives

The main objectives of CineLog are:

1. Build a functional movie review application.
2. Practice HTML, CSS and JavaScript.
3. Implement client-side data storage.
4. Practice Git and GitHub collaboration.
5. Learn branch-based development.
6. Understand Pull Requests.
7. Practice code integration between multiple developers.
8. Demonstrate individual team contributions.

---

# 📚 Learning Outcomes

After completing this project, students should understand:

* Web page development
* Responsive CSS
* JavaScript DOM manipulation
* JavaScript event handling
* LocalStorage
* Git commands
* Git branches
* GitHub repositories
* Pull Requests
* Code review
* Team-based software development

---

# ⚠️ Project Disclaimer

CineLog is an original educational project inspired by the general concept of movie diary and review applications.

It is **not affiliated with Letterboxd** and does not use Letterboxd's private APIs, user data, proprietary source code, or copyrighted assets.

Movie information included in the demo is for educational purposes.

---

# 📌 Future Enhancements

Possible future improvements include:

* User authentication
* Real movie database API
* Real movie posters
* User-to-use
