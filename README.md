# CloudSimulate

## Overview

**CloudSimulate** is an innovative tool designed for software engineers, architects, and cloud enthusiasts to simulate cloud architectures using AWS and Google Cloud icons. The application allows users to design cloud systems visually and receive AI-powered insights, such as optimization suggestions, performance analysis, and potential risk identification.

## Features

- **Drag-and-Drop Interface:** Easily design cloud architectures using a user-friendly drag-and-drop interface with pre-defined icons for AWS and Google Cloud services.
- **AI-Powered Analysis:** Leverage the power of AI to analyze your cloud architecture, providing insights and recommendations for optimization.
- **Infrastructure as Code (IaC) Export:** Generate code snippets for your architecture designs, which can be deployed in real cloud environments.
- **Responsive Design:** Works seamlessly on both desktop and mobile devices.

## Technology Stack

- **Backend:** FastAPI (Python)
- **Frontend:** React.js
- **Database:** PostgreSQL
- **AI Integration:** OpenAI's ChatGPT API
- **DevOps:** Docker, GitHub Actions, AWS

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js 14+
- PostgreSQL
- Docker (optional for containerization)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/CloudSimulate.git
    cd CloudSimulate
    ```

2. **Set up the Backend:**

    - Navigate to the backend directory:
    
        ```bash
        cd backend
        ```

    - Create a virtual environment and activate it:

        ```bash
        python3 -m venv env
        source env/bin/activate
        ```

    - Install the dependencies:

        ```bash
        pip install -r requirements.txt
        ```

    - Set up the PostgreSQL database and apply migrations:

        ```bash
        # Update DATABASE_URL in settings.py or equivalent
        python manage.py migrate
        ```

    - Run the backend server:

        ```bash
        uvicorn main:app --reload
        ```

3. **Set up the Frontend:**

    - Navigate to the frontend directory:

        ```bash
        cd ../frontend
        ```

    - Install dependencies:

        ```bash
        npm install
        ```

    - Start the React development server:

        ```bash
        npm start
        ```

4. **Running with Docker (Optional):**

    - Build and run the application using Docker:

        ```bash
        docker-compose up --build
        ```

## Usage

- Access the application at `http://localhost:3000` for the frontend and `http://localhost:8000` for the API backend.
- Begin designing cloud architectures by dragging and dropping AWS and Google Cloud icons onto the canvas.
- Use the AI-powered analysis tool to optimize and simulate the behavior of your architecture.

## Contributing

We welcome contributions! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions, feel free to reach out to the maintainer at [your-email@example.com].

