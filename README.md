# Hair Analysis WebApp

## Overview

Hair Analysis WebApp is a web-based application designed to analyze hair health and provide personalized recommendations. It leverages advanced algorithms and machine learning to deliver accurate results.

## Features

- Upload and analyze hair images.
- Generate detailed hair health reports.
- Provide personalized hair care recommendations.
- User-friendly interface.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React.js
- **Backend**: Node.js, Express.js
- **Machine Learning**: TensorFlow, OpenCV

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Hair_Analysis_WebApp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Hair_Analysis_WebApp
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   npm install
   ```
4. Run the application:
   ```bash
   python app.py
   npm start
   ```

## API Configuration

This project uses the following APIs:

- **Stripe API**: For payment processing.
- **Clerk API**: For user authentication and management.
- **Google Teachable Machine API**: For machine learning model integration.

Please ensure you obtain the respective API keys and add them to the `.env` file in the following format:

```env
VITE_STRIPE_PUBLISHABLE_KEY= your_stripe_publishable_key

VITE_CLERK_PUBLISHABLE_KEY= your_clerk_publishable_key

VITE_CLERK_FRONTEND_API=your_clerk_frontend_api

MODEL_URL = 'your_teachable_model_uploaded_model_api_key/model.json'

META_DATA_URL = 'your_teachable_model_uploaded_model_api_key/metadata.json'
```

Make sure to use the same constant names (`MODEL_URL` and `META_DATA_URL`) in the codebase as specified above. Ensure that the values for these keys end with the `.json` extension (`model.json` and `metadata.json`).

## Usage

1. Open the web application in your browser.
2. Upload a hair image for analysis.
3. View the generated report and recommendations.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Contact

For any inquiries, please contact [ viswesh.mekala@gmail.com ].
