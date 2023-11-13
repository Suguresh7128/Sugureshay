# Sugureshay
style - .css
Choose ThumbnailUpgrade

Static
Animation
 
 Edit Captions

 Engagement Insights

Video Views
0
Video Downloads
0
Call-to-Action Clicks 
0
Average Completion Rate 
0%
viewers


Someone from Pakistan desktop
Apr 14, 2021

Someone from Pakistan desktop
Apr 14, 2021

Someone from Pakistan desktop
Apr 14, 2021
 Transcription

Engagement Insights

0 Comments

Leave a comment
body {
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: linear-gradient(90deg, rgba(93, 99, 204, 1) 0%, rgba(245, 240, 242, 1) 100%, rgba(0, 212, 255, 1) 100%);
    font-family: monospace, sans-serif;
    color: wheat;
}

.container {
    background: rgba(0, 212, 255, 0.3);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 4px 10px rgba(0, 0, 0, 0.3);
    width: 85%;
    max-width: 800px;
    min-height: 300px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.heading {
    font-size: 64px;
}

.temp-container {
    width: 100%;
    padding: 15px;
    font-weight: bold;
    font-size: 18px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}

input {
    width: 60%;
    font-family: monospace;
    padding: 5px;
    outline: none;
    background: rgba(0, 212, 255, 0.3);
    border-color: rgba(255, 255, 255, 0.6);
    color: lightgreen;
    font-size: 18px;
}

input::placeholder {
    color: black;
}

/* Responsive CSS */
@media (min-width: 600px) {
    .container {
        width: 70%;
    }

    input {
        width: 50%;
    }
}

@media (min-width: 900px) {
    .container {
        width: 60%;
    }

    input {
        width: 40%;
    }
