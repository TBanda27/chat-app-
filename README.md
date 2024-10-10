# WebSocket Chat Application

This is a simple **WebSocket-based group chat application** built using Spring Boot. The chat allows multiple users to join a real-time group chat session, but **chats are not persisted**. Each user is registered by entering their name before joining the chat room.

## Features

- **User Registration**: Each user enters their name on a landing page to join the chat.
- **Real-time Messaging**: Messages are exchanged between all connected users in real-time using WebSockets.
- **Group Chat**: Multiple users can chat simultaneously in the same chat room.
- **Ephemeral Chats**: Chat messages are not stored; they are only available during the session.
- **Multiple User Simulation**: You can simulate multiple users by opening new browser tabs or windows and joining the chat with different names.

## How It Works

1. **Landing Page**: The app starts with a landing page where the user is prompted to enter their name.
   
2. **Join the Chat**: Once the name is submitted, the user is redirected to the main chat page, where the WebSocket connection is established.
   
3. **Real-time Messaging**: Users can send and receive messages in the chat room in real-time.

4. **Simulate Multiple Users**: To simulate another user, open a new tab or window, navigate to the same URL, and enter a different name. You will be registered as another participant in the chat.

## Usage

1. Clone this repository:
    ```bash
    git clone <https://github.com/TBanda27/chat-app-.git>
    ```

2. Navigate to the project directory:
    ```bash
    cd chat-app
    ```

3. Run the Spring Boot application:
    ```bash
    ./mvnw spring-boot:run
    ```

4. Open your browser and navigate to `http://localhost:8080`.

5. Enter your name on the landing page to join the chat.

6. To simulate another user, open a new tab or window, navigate to `http://localhost:8080`, and enter a different name.

7. Start chatting!

## Example

1. **User 1** enters the name "Alice" and is redirected to the chat room.
2. **User 2** opens another tab, enters the name "Bob," and joins the same chat room.
3. **Alice** and **Bob** can now exchange messages in real-time.



## License

This project is licensed under the MIT License 
