# Riteshai
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Interact with [RITESH] AI Chatbot, your personal assistant powered by AI.">
    <meta name="keywords" content="AI, chatbot, Botpress, RITESH, assistant">
    <title>[RITESH] AI Chatbot</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>
    <script async src="https://cdn.botpress.cloud/webchat/v2/inject.js"></script>
    <script>
        window.botpressWebChat.init({
            hostUrl: "https://media-files.botpress.cloud/8c837592-9fd3-4d6c-8885-33f3234b6d9",
            botId: "12345abcde",
        }).catch(error => {
            console.error('Failed to load chatbot:', error);
            alert('Sorry, the chatbot is currently unavailable.');
        });
    </script>
    <noscript>
        Please enable JavaScript to interact with the AI Chatbot.
    </noscript>
</body>
</html>
