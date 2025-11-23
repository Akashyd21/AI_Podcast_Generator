🎧 AI Podcast Generator

Generate a 2-person AI podcast (Host & Guest) using GPT, gTTS, and Gradio.

✅ Requirements

Install dependencies:

pip install openai gradio pydub gTTS


Install FFmpeg (needed for pydub):

Colab/Linux:

apt-get install ffmpeg


Windows:
Download FFmpeg → add to PATH.

Add your OpenAI API key in the code:

os.environ["OPENAI_API_KEY"] = "YOUR_API_KEY"

▶️ Run the App

Launch:

app.launch()


This opens the Gradio interface where you can generate the podcast script + MP3.
