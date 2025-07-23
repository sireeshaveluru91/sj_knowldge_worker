# sj_knowledge_worker

## Overview
The `sj_knowledge_worker` project is designed to create a conversational AI that can answer questions based on a set of text documents. It utilizes vectorization techniques to transform text data into a format suitable for machine learning, enabling the AI to understand and respond to user queries effectively.

## Project Structure
```
sj_knowledge_worker
├── src
│   ├── main.py          # Entry point of the application
│   ├── vectorizer.py    # Handles vectorization of text data
│   ├── chat_ai.py       # Manages conversation logic
│   ├── data_loader.py    # Loads and preprocesses documents
│   └── config.py        # Configuration settings
├── data
│   └── documents        # Directory for text documents
├── vector_store         # Directory for storing vectorized representations
├── requirements.txt     # Project dependencies
├── .env                 # Environment variables
└── README.md            # Project documentation
```

## Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd sj_knowledge_worker
   ```

2. **Install Dependencies**
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare Data**
   Place your text documents in the `data/documents` directory.

4. **Configure Environment Variables**
   Update the `.env` file with any necessary API keys or configuration settings.

## Usage
To run the application, execute the following command:
```bash
python src/main.py
```
This will initialize the vectorizer, load the documents, and start the conversation AI interface.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.