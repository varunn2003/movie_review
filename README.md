![react_front1](https://github.com/sarankumar007/Movie_Frontend_React/assets/93342856/e9e1b9a4-3da6-4be2-b145-0504568cb22f)
![react_front3](https://github.com/sarankumar007/Movie_Frontend_React/assets/93342856/53d49c81-5bb1-4acb-8601-50465800ff35)
![react_front2](https://github.com/sarankumar007/Movie_Frontend_React/assets/93342856/dddf3b90-48bf-4cd6-a139-027005392a40)

# Movie Review Frontend

This repository contains the frontend code for a React application that connects to a backend API for retrieving movie details. The backend API is provided by the "MovieApi_Backend_Springboot" repository.

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/sarankumar007/Movie_Frontend_React.git
   ```

2. Navigate to the project directory:

   ```
   cd movie-review-frontend
   ```

3. Install the dependencies:

   ```
   npm install
   ```

### Configuration

Update the API endpoint in the application to connect with the backend API. Follow the steps below:

1. Open the `src/api/api.js` file.
2. Locate the `API_BASE_URL` constant.
3. Update the `API_BASE_URL` to point to the backend API endpoint.
   ```
   const API_BASE_URL = 'https://your-backend-api.com';
   ```

### Usage

1. Start the application:

   ```
   npm start
   ```

   The application should now be running on `http://localhost:3000`.

2. Open a web browser and navigate to `http://localhost:3000` to view the application.

## Backend API

This frontend application relies on the backend API provided by the "MovieApi_Backend_Springboot" repository. Make sure to set up and run the backend API before using this frontend application. You can find the backend API repository at [MovieApi_Backend_Springboot](https://github.com/sarankumar007/MovieApi_Backend_Springboot).

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push the branch to your forked repository.
5. Submit a pull request.



## Acknowledgments

This project was developed with the goal of creating a movie review application using React and a Spring Boot backend API. Special thanks to the contributors who made this project possible.
