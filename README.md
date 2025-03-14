# Static Site

A simple Node.js website for static `index.html` hosting using Express.

## How to Host Keepwork in Your Domain
- https://keepwork.com/official/docs/UserGuide/keepwork/publish_yoursite
- modify Default_url in [index.html](https://github.com/LiXizhi/keepwork_hosting/blob/main/index.html)

## Installation

1. Clone the repository or download the project files.
2. Navigate to the project directory:
    ```sh
    cd /C:/temp/keepwork_hosting
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Running the Server

1. Start the server:
    ```sh
    npm start
    ```
2. Open your browser and go to `http://localhost:3000` to see the static site.

## Project Structure

- `index.html`: The static HTML file to be served.
- `server.js`: The Express server file.
- `package.json`: The project configuration and dependencies.
