# Creal-Hub

This project is a simple, single-page web application that simulates a touch-screen kiosk for ordering cereal. It was built using plain HTML, Tailwind CSS (via CDN), and JavaScript.

# Features

Bilingual Interface: Supports both Vietnamese (Tiếng Việt) and English.

Responsive Design: Adapts from a portrait (mobile) layout to a landscape (tablet/desktop) layout.

Multi-Step Flow: Guides the user through a logical ordering process:

Start Screen

Language Selection

Cereal Choice

Milk & Topping Selection

Payment Method

Payment/Success Screen

Order Logic:

Calculates the total price in real-time as options are selected.

Toppings are optional.

Milk selection is mandatory. The checkout button is disabled until a milk type is chosen.

Self-Contained: All code (HTML, CSS, JS) is in a single index.html file, making it easy to deploy.

# How to Run

## Locally

Simply download the index.html file and open it in any modern web browser.

With GitHub Pages

Create a new public repository on GitHub.

Upload the index.html and README.md files to this repository.

Go to your repository's Settings tab.

Click on Pages in the left-hand menu.

Under Source, select Deploy from a branch.

Set the Branch to main (or master) and the folder to / (root).

Click Save. Your site will be live at https://<your-username>.github.io/<your-repo-name>/ in a few minutes.
