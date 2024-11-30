# Overview

This project integrates avatars with responsive animations triggered by prompts. When a prompt is provided, the avatar responds with animations such as talking (lip-syncing) to enhance the interactive experience. The project consists of two parts: frontend and backend, and uses `yarn` for package management and running the development servers.

## Features

- Avatars respond to prompts with appropriate animations.
- Talking animations include realistic lip-syncing.
- Modular frontend and backend structure for scalability.
- Built using modern JavaScript frameworks and libraries.

## Prerequisites

Ensure you have the following installed on your system:

- Node.js (version 14 or later recommended)
- Yarn (latest version recommended)
- A modern web browser (e.g., Chrome, Firefox)

## Setup

Clone the repository to your local machine:

```bash
git clone https://github.com/muhammadsaadkhankor/InteractiveAIAvatar.git
```

Navigate to the project directory:

```bash
cd InteractiveAIAvatar
```

Install dependencies for both the frontend and backend:

```bash
yarn install
```

## Running the Project

Start the backend server:

```bash
cd backend
yarn run dev
```

Start the frontend server:

```bash
cd frontend
yarn run dev
```

The application will be accessible at [http://localhost:3000/](http://localhost:3000/) or another port specified in your terminal.

## How to Use

1. Open the application in your browser.
2. Provide a prompt in the input field.
3. The avatar will respond with animations, such as talking with lip-syncing, in real-time.

## Folder Structure

- `frontend/`: Contains the code for the user interface.
- `backend/`: Handles prompt processing and animation logic.

## Key Technologies

- **Frontend**: Modern JavaScript frameworks (e.g., React, Vue, or similar).
- **Backend**: Node.js and Express.js.
- **Lip-syncing Animations**: Custom animations and synchronization logic.
- **Yarn**: For dependency management and running scripts.

## Customization

- Add new animations to the `assets/` directory.
- Modify the backend logic to support additional prompt types.
- Update the frontend UI to enhance user interactions.

## Troubleshooting

- Ensure all dependencies are installed by running `yarn install` in both `frontend/` and `backend/` directories.
- Check the console for any runtime errors.
- Verify that animation files are correctly placed in the `assets/` directory.

## License

This project is licensed under [Your License Here].

## Acknowledgments

- Developers and contributors of animation libraries.
- Avatar and prompt generation frameworks.
