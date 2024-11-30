body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(to bottom right, #4facfe, #00f2fe);
    color: #333;
}

#game-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    background: #fff;
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
    color: #444;
}

#grid-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 10px;
    margin: 20px 0;
}

.character {
    width: 100%;
    padding: 10px;
    background: #eee;
    border-radius: 5px;
    transition: transform 0.3s;
    cursor: pointer;
}

.character:hover {
    transform: scale(1.1);
    background: #ccc;
}

#chat-container {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

#chat-box {
    width: 100%;
    height: 100px;
    resize: none;
    border-radius: 5px;
    border: 1px solid #ddd;
    padding: 10px;
}

#chat-input {
    flex: 1;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

#send-button {
    background: #4facfe;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s;
}

#send-button:hover {
    background: #3a8bd1;
}
