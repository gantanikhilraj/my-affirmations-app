# My Affirmations App

Welcome to the **My Affirmations App** project! This web application is designed to provide personalized, uplifting affirmations using Amazon Bedrock's Converse API. The project combines modern cloud technology with mindfulness to create a soothing digital experience.

## Overview

This project was developed during the AWS Hyderabad User Group September Meetup. The app is built using Vite and leverages Amazon Bedrock's language models to generate affirmations inspired by Indian cinema, incorporating themes of love, culture, and adventure.

## Features

- **Dynamic Affirmations**: Generates personalized affirmations using Amazon Bedrock's Converse API.
- **User-Friendly Interface**: Simple and intuitive design for easy interaction.
- **Mindfulness Focus**: Provides uplifting and positive messages to enhance user well-being.

## Prerequisites

Before you begin, ensure you have the following:

- A laptop with internet access.
- An active AWS account.
- Basic familiarity with HTML, CSS, JavaScript, and Vite.
- Familiarity with the Node.js ecosystem (npm for package management).
- General understanding of cloud computing principles and AWS services (beneficial but not required).
- Awareness of JSON data structure.
- Experience with a code editor (ideally VS Code).
- General awareness of large language models and an interest in generative AI applications.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd my-affirmations-app
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Environment Variables**:
    - Create a .env.local file in the root directory.
    - Add your AWS credentials prefixed with VITE_:

    ```bash
    VITE_AWS_ACCESS_KEY_ID=<your-access-key-id>
    VITE_AWS_SECRET_ACCESS_KEY=<your-secret-access-key>
    VITE_AWS_SESSION_TOKEN=<your-session-token>
    ```

4. **Start the Development Server**:
    ```bash
    npm run dev
    ```

5. **Access the Application**:
    - Open your browser and navigate to `http://localhost:portnumber` to view the app.

## Troubleshooting
    - Ensure your AWS credentials are correctly set in the .env.local file.
    - Verify that your AWS account has the necessary permissions to access Amazon Bedrock services.
    - Check the console for any error messages if the app fails to fetch affirmations.

## Contributing
    - Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Acknowledgments
- Special thanks to Stephen Howell, Developer Advocate at Amazon Web Services, for leading the workshop and providing valuable insights into AI technology. We hope you find this project both educational and relaxing. Enjoy your journey into coding mindfulness!