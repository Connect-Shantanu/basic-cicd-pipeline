This is a simple Node.js web application that serves a "Hello, World!" message over HTTP.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Docker](#docker)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone this repository to your local machine:

git clone https://github.com/connect-shantanu/basic-cicd-pipeline.git

2. Navigate to the project directory:

cd my-node-app
//replace my-node-app with actual name of the app

3. Install dependencies:

npm install


## Usage

Start the application by running the following command:

npm start


The application will start and listen for requests on port 3000 by default. Open your web browser and navigate to `http://localhost:3000` to see the "Hello, World!" message.

## Docker

To run the application using Docker, make sure you have Docker installed on your machine. Then, follow these steps:

1. Build the Docker image:

docker build -t my-node-app .

2. Run a container from the built image:

docker run -p 3000:3000 my-node-app

The application will be accessible at `http://localhost:3000` as before.

## Contributing

Contributions are welcome! If you find a bug or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


