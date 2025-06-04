# classroom-summarizer-gen-AI
 smart assistant that helps students understand and revise lectures by:
- Converting lecture :audio into text
- Generating: bullet point summaries
- Creating :Q&A flashcards
- Drawing :mind maps of the lecture


# Features
- Audio to Text
- Bullet Point Summarizer
- Flashcard Generator
- Mind Map Visualizer


PROJECT SRUCTURE
│
├── README.md                Project overview and setup instructions
├── requirements.txt         Python dependencies
├── data/                    Datasets: audio files, transcripts, text data
├── models/                  trained machine learning models
├── src/                     Core source code
│   ├── asr/                 Audio-to-text modules 
│   ├── summarizer/          Text summarization modules 
│   ├── flashcards/          Q&A generation modules 
│   ├── mindmap/             Entity extraction and mind map generation modules
│   └── utils/               Utility functions (tokenization, data processing, etc.)
└── backend/                 Backend API server (e.g., FastAPI)
    ├── main.py              API entry point
    └── routes/              API route handlers (summarize, flashcards, mindmap)

