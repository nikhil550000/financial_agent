# Simple Financial Agent

A **Simple Financial Agent** leveraging AI to perform financial analysis and web searches.

## Features
- Fetch stock prices, analyst recommendations, stock fundamentals, and company news.
- Perform web searches with relevant sources.
- Interactive playground for agent interaction.

## Prerequisites
- Python 3.8 or above
- API keys:
  - **PHI_API_KEY**: Your Phi API key
  - **GROQ_API_KEY**: Your Groq API key

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file with your API keys:
   ```env
   PHI_API_KEY=your_phi_api_key
   GROQ_API_KEY=your_groq_api_key
   ```

## Usage
Run the application using:
```bash
python playground.py
```
Open the provided URL in your browser to interact with the financial and web search agents.

## Technologies Used
- **Programming Language:** Python
- **AI Models:** Groq (LLaMA3)
- **APIs and Tools:**
  - YFinance
  - DuckDuckGo
  - OpenAI
  - Phi Playground

## License
This project is licensed under the MIT License.
