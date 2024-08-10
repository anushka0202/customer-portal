# Customer Portal SPA

Link: [https://video-player-anushka.netlify.app/](https://video-player-anushka.netlify.app/)

This project is a single-page application (SPA) built using React and TypeScript. The application allows users to view a list of customers and see detailed information about a selected customer, including a grid of photos that refresh automatically every 10 seconds.

## Features
- Customer List: A scrollable list of customers displayed on the left side. Selecting a customer highlights the selected item.
- Customer Details: Displays the selected customer's name, title, address, and a 3x3 grid of photos on the right side.
- Photo Grid: Photos are fetched from the Unsplash API and update every 10 seconds. The images are displayed in a square grid format.

## Getting Started
Clone the repository:
```bash
git clone https://github.com/your-username/customer-portal.git
cd customer-portal
```
Installing the dependencies and running the application
```bash
npm i
npm run start
```

## Acknowledgements
- [Lorem Picsum](https://picsum.photos/) for providing free access to high-quality images.
- [Random User](https://randomuser.me/) Generator for the mock customer data.
