# Simple Python HTTP Server

This is a basic Python HTTP server built using `socket`. The server handles requests for static files such as `index.html` and `book.json`.

## How It Works

- The server listens on `0.0.0.0:8080` and serves files in the same directory.
- If the client requests the root path `/`, the server responds with the `index.html` file.
- If the client requests `/book`, the server responds with the `book.json` file.
- If the requested file is not found, the server returns a `404 NOT FOUND` error.



## Usage

1. Clone the repository or copy the files to your local machine.
2. Place the `index.html` and `book.json` files in the same directory as the Python script.
3. Run the server:

    ```bash
    python server.py
    ```

4. Open your web browser and go to `http://localhost:8080/` for `index.html`, or `http://localhost:8080/book` for `book.json`.

![Screenshot 2024-09-12 021121](https://github.com/user-attachments/assets/e4be1832-6f6a-4da9-b01a-10d96c33a2ef)
![Screenshot 2024-09-12 021109](https://github.com/user-attachments/assets/d9d66bfa-9f71-43e4-8e10-9e94946df093)
![Screenshot 2024-09-12 020925](https://github.com/user-attachments/assets/1d0c2fbd-9c86-4e2a-91ae-ce82b514869c)


