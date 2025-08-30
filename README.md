# Taxigo App - A Modern Taxi Booking Application

This is a full-stack taxi booking application built with Next.js, React, and TypeScript. The app allows users to book rides, track their trips in real-time, and handle secure payments.

## Features

* **User Authentication:** Secure user registration and login.
* **Real-time Mapping:** Integration with Mapbox for live location tracking and route visualization.
* **Ride Booking:** Users can easily book a taxi by selecting pickup and drop-off locations.
* **Fare Calculation:** Calculates ride fares based on distance.
* **Secure Payments:** Handles payments through a secure payment gateway.

## Tech Stack

* **Frontend Framework:** Next.js 13, React
* **Language:** TypeScript
* **Styling:** Tailwind CSS
* **Mapping:** Mapbox
* **Authentication:** Clerk
* **Payments:** Stripe

## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/rrs301/taxi-booking-nextjs.git](https://github.com/rrs301/taxi-booking-nextjs.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd taxi-booking-nextjs
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

### Running the Development Server

1.  Start the development server:
    ```bash
    npm run dev
    ```
2.  Open your browser and visit:
    ```
    http://localhost:3000
    ```

## Usage

* **Sign up/Login:** Create a new account or log in with existing credentials.
* **Book a Ride:** Enter your pickup and drop-off locations on the map.
* **View Trip Details:** The app will calculate the fare and show the trip details.
* **Make Payment:** Complete the payment using the integrated payment system.
