# F.R.I.D.A.Y. Your personal Assistant

This is a Python-based AI assistant inspired by *Jarvis*, capable of:

- 🔍 Searching the web  
- 🌤️ Weather checking
- 📨 Sending Emails
- 📷 Vision through camera (Web app)
- 🗣️ Speech
- 📝 Chat (Web app)

This agent uses [LiveKit](https://livekit.io/)

- Download or clone the repository

```bash
git clone https://github.com/aaradhy25tiwari/J.A.R.V.I.S.-AI.git
```

---

## Steps to the run the model

1. Create the Virtual Envrionment using

    ```bash
    python -m venv venv
    ```

2. Activate the environment

    ```bash
    .\venv\Scripts\activate
    ```

3. Install all the required libraries mentioned in the requirements.txt file

    ```bash
    pip install -r requirements.txt
    ```

4. In the .ENV - File you should paste your API-Keys and your LiveKit Secret, LiveKit URL.
   If you want to use the Send Email Tool also specify your Gmail Account and App Password.
5. Make sure that your LiveKit Account is set-up correctly.

6. Create a Python environment using

To run the assistant on the terminal

```bash
python .\agent.py console
```

To run the assistant on the [LiveKit Playground](https://agents-playground.livekit.io/)

1. Run the following Command on the terminal

    ```bash
    python .\agent.py dev
    ```

2. Go to the LiveKit Playground and Connect to a project in LiveKit Cloud

Your AI assistance is ready!!

## Happy Coding! 🖥️
