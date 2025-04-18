# Blaze - Social Media Platform

Blaze is a full-stack Social Media Platform where you can connect with others, share your moments by creating posts, and interact through likes and comments.Follow users to get their posts in your feed, customize your profile, and stay updated with notifications.


## Features

*   **User Authentication:** Secure user signup and login using JWT.
*   **Post Management:** Create, view, and delete posts.
*   **Post Interaction:** Like and comment on posts from other users.
*   **User Profiles:** View user profiles of others, update your own profile information.
*   **Follow System:** Follow and unfollow other users and their posts will show in your feed.
*   **Notifications:** Receive notifications for interactions like new followers, post likes, and comments.


## Tech Stack

*   **Backend:** Node.js, Express.js
*   **Database:** MongoDB
*   **Frontend:** React.js
*   **Authentication:** JWT, bcryptjs
*   **Image Handling:** Cloudinary


## Screenshots

### Login / Signup page
![b1](https://github.com/user-attachments/assets/31f52dc7-6413-4d87-8569-768163179e96)

### Home feed
![b2](https://github.com/user-attachments/assets/4401e9f8-c803-49ad-8f4f-cbfa5cd7c318)

<br>

![b7](https://github.com/user-attachments/assets/6f301e18-a61c-4136-b693-674be2195bd1)

### Your notifications
![b3](https://github.com/user-attachments/assets/993ca3dc-4a42-49db-b94a-d7f04bc6cde1)

### Profile page : edit your profile-photo, banner, and bio. View your posts and likes
![b4](https://github.com/user-attachments/assets/c0a06053-bb6a-41f4-a2fb-34c6a2c5023f)

### Explore others’ profiles 
![b5](https://github.com/user-attachments/assets/5dc9610c-a54e-4478-9d23-2c509ff0699d)


## Getting Started

### Prerequisites

*   Node.js and npm installed
*   MongoDB instance (local or cloud)
*   Cloudinary account (for image uploads)

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd blaze
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
  
3.  **Set up environment variables:**
    Create a [.env] file in the root directory and add the necessary variables:

4.  **Build the frontend (Optional - if needed separately):**
    ```bash
    npm run build --prefix frontend
    ```

5.  **Running the Application**
*   **Development Mode (with hot-reloading for backend):**
    ```bash
    npm run dev
    ```
*   **Production Mode:**
    ```bash
    npm start
    ```
The application should be accessible at `http://localhost:<your_port>`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
