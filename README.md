# Multi-Modal AI Assitant

A Python-based application utilizing OpenAI, Gradio, and other libraries for AI-driven functionalities.

## Installation

1. **Clone the Repository:**  
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2. **Set Up a Virtual Environment:**  
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`
    ```

3. **Install Dependencies:**  
    ```bash
    pip install -r requirements.txt
    ```

### Dependencies
- Pillow
- dotenv
- gradio
- json
- openai
- os
- pydub

## Environment Variables

Ensure you have a `.env` file in the root directory with the following content:
    ```env
    OPENAI_API_KEY=your_openai_api_key_here
    ```
Replace `your_openai_api_key_here` with your actual OpenAI API key.

## Usage

To start the application, run:
    ```bash
    python app.py
    ```

## File Structure
- `app.py`: Main application script.
- `requirements.txt`: List of required Python packages.

## License

This project is licensed under the MIT License.
