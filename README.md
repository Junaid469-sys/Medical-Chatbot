# Medical-Chatbot
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>AI Medical Chatbot - Project Description</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 40px; line-height: 1.6; }
        h1, h2 { color: #2C3E50; }
        h1 { border-bottom: 2px solid #2C3E50; padding-bottom: 5px; }
        ul { margin: 0; padding-left: 20px; }
        .section { margin-bottom: 20px; }
    </style>
</head>
<body>
    <h1>AI Medical Chatbot using RAG (MediBot)</h1>
    
    <div class="section">
        <h2>Description:</h2>
        <p>Developed an AI-powered medical chatbot using <strong>Retrieval-Augmented Generation (RAG)</strong> to provide instant medical assistance by querying large medical documents.</p>
    </div>
    
    <div class="section">
        <h2>Key Responsibilities:</h2>
        <ul>
            <li><strong>Implemented a 3-phase pipeline:</strong>
                <ul>
                    <li><strong>Memory Setup:</strong> Loaded raw PDFs, created text chunks, generated vector embeddings, and stored them in <strong>FAISS</strong>.</li>
                    <li><strong>LLM Integration:</strong> Connected <strong>Mistral (LLM)</strong> with FAISS using <strong>LangChain</strong> to enable memory retrieval.</li>
                    <li><strong>User Interface:</strong> Built a responsive chatbot UI using <strong>Streamlit</strong> for real-time medical query resolution.</li>
                </ul>
            </li>
            <li>Utilized <strong>HuggingFace</strong> for accessing pre-trained models and integrated a full RAG pipeline for enhanced response accuracy.</li>
            <li>Ensured modular architecture, simplifying future improvements like multi-document support and authentication.</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Tools & Technologies:</h2>
        <p><strong>LangChain</strong> | <strong>HuggingFace</strong> | <strong>Mistral (LLM)</strong> | <strong>FAISS</strong> | <strong>Streamlit</strong> | <strong>Python</strong> | <strong>VS Code</strong></p>
    </div>
    
    <div class="section">
        <h2>Impact:</h2>
        <ul>
            <li>Improved accuracy of medical responses with contextual knowledge retrieval from large medical texts.</li>
            <li>Designed a scalable solution with modular phases, paving the way for future enhancements such as multi-document embeddings and user authentication.</li>
        </ul>
    </div>
</body>
</html>
