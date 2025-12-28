# krkr-AI
KRKR AI ONLINE 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>KRKR AI Online</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    min-height: 100vh;
    color: #fff;
}
h1 {
    margin-top: 20px;
    font-size: 2em;
    text-shadow: 2px 2px 5px #000;
}
#chat {
    width: 95%;
    max-width: 450px;
    height: 400px;
    background: rgba(255,255,255,0.05);
    border-radius: 15px;
    padding: 15px;
    overflow-y: scroll;
    margin-bottom: 15px;
    box-shadow: 0 0 20px rgba(0,0,0,0.5);
}
.user { color: #00aaff; margin: 5px 0; word-wrap: break-word; }
.ai { color: #00ff77; margin: 5px 0; word-wrap: break-word; }
.input-area {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    max-width: 450px;
    margin-bottom: 20px;
}
input {
    flex: 1;
    padding: 12px;
    border-radius: 10px;
    border: none;
    font-size: 16px;
    outline: none;
    margin-right: 10px;
}
button {
    padding: 12px 20px;
    border-radius: 10px;
    border: none;
    background:
