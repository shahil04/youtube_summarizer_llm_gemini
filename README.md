first create folder 
- open in vscode 
- create venv
    conda create -p venv python==3.10 -y
- create .env to store gemini api key private
- create requirements.py and add necessary libraries and framework
        youtube_transcript_api # use to extract yt subtitle as a text 
        streamlit  # for create frontend 
        google-generativeai # use gemini pro 
        python-dotenv # api load seceratly
        pathlib # for define path 
        