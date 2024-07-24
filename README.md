# StudyNotion

StudyNotion is an interactive ed-tech platform built using the MERN stack (MongoDB, Express, React, Node). It enables users to create, consume, and rate educational content, providing a seamless and engaging learning experience.

## Features

- **User Authentication**: Sign up and log in with email and password.
- **Course Management**: Create, read, update, and delete courses. Manage course content and media.
- **Course Rating**: Rate courses to provide feedback.
- **Payment Integration**: Purchase and enroll in courses through a secure payment gateway.
- **Media Handling**: Store and manage course media content such as videos, images, and documents.

## Future Enhancements

- **Gamification Features**: Add badges, points, and leaderboards to boost user engagement.
- **Personalized Learning Paths**: Create custom learning paths based on student interests and learning styles.
- **Social Learning Features**: Introduce group discussions, peer feedback, and collaborative projects.
- **Mobile App**: Develop a mobile app for easier access to course content.
- **Machine Learning Recommendations**: Implement personalized course recommendations using machine learning.
- **VR/AR Integration**: Enhance learning experiences with virtual reality and augmented reality components.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/StudyNotion.git
    cd StudyNotion
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the `server` folder with the following content:
    ```plaintext
    # JWT Secret Key used for signing and verifying JSON Web Tokens
    JWT_SECRET="your_jwt_secret_key"

    # MongoDB connection string for connecting to the database
    MONGODB_URL="your_mongodb_url"

    # Hostname of the mail server used for sending emails
    MAIL_HOST="your_mail_host"

    # Username of the email account used for sending emails
    MAIL_USER="your_mail_user"

    # Password of the email account used for sending emails
    MAIL_PASS="your_mail_password"

    # Razorpay keys for payment integration
    RAZORPAY_KEY="your_razorpay_key"
    RAZORPAY_SECRET="your_razorpay_secret"
    ```

4. Run the development server:
    ```sh
    npm run dev
    ```

## Usage

1. **Frontend**: Open your browser and go to `http://localhost:3000`.
2. **Backend**: The backend server will run on `http://localhost:5000`.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.


---

Happy Learning with StudyNotion!
