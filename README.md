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
├── README.md            
├── requirements.txt        
├── data/  Datasets
├── models/trained ml models
├── src/                   
│   ├── asr/  Audio-to-text modules 
│   ├── summarizer/ Text summarization 
│   ├── flashcards/ Q&A generation modules 
│   ├── mindmap/ mind map generation modules
│   └── utils/ Utility functions 
└── backend/   API server
    ├── main.py            
    └── routes/ API route handlers 

