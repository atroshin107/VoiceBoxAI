# VoiceBox AI for Blender

VoiceBox AI is a voice-controlled Blender add-on that allows you to create meshes, curves, and light objects using simple spoken commands. Designed to streamline scene creation and eliminate menu diving.

---

## Installation and Activation

### 1. Installation
1. In Blender, go to Edit > Preferences > Add-ons.
2. Click Install... and select the VoiceBoxAI.zip file.
3. Enable the checkbox next to "Interface: VoiceBox AI".

### 2. License Activation
The add-on requires a unique license key provided upon purchase via SellAuth:
1. Copy the key from your confirmation email.
2. In the add-on Preferences, locate the License field.
3. Paste your key and click Verify License.
4. A checkmark will appear once validated, unlocking the AI configuration.

---

## AI Configuration (API Key)

To process commands, the add-on requires an API Key from your preferred AI service provider.

> **Privacy Note:** Keep your API key private. 

### How to set up:
1. **Select Service:** Choose from Gemini, Groq, OpenAI, DeepSeek, or Anthropic in the dropdown.
2. **Input Key:** Paste your API Key into the corresponding field.
3. **Select Model:** Choose a specific model (e.g., gpt-4o, llama-3.3-70b, or claude-3-5-sonnet) directly in the UI.

---

## How to Use (Push-to-Talk)

VoiceBox AI uses a Push-to-Talk workflow for maximum accuracy:

1. Press N in the 3D Viewport to open the sidebar.
2. Open the VoiceBox AI tab.
3. Click Load Voice Model (Initialization may take a few seconds as the model loads into memory).
4. **Press and hold the 'V' key.**
5. Speak your command clearly (e.g., "Add a subdivided cube").
6. **Release the 'V' key** when you finish speaking.

The command will execute immediately at the location of your 3D cursor.

---

## Example Commands

| Category | Examples |
| :--- | :--- |
| **Meshes** | "Add cube", "Add UV sphere", "Add Suzanne", "Add torus" |
| **Lights** | "Add point light", "Add sun", "Add area light" |
| **Curves** | "Add path", "Add Bézier curve", "Add circle" |
| **Complex** | "Scatter 10 cubes with random scale", "Create a gold material and apply to selection" |

---

## Requirements
* **Blender:** Version 4.2+
* **Microphone:** Must be set as the default input device in your OS.
* **Internet:** Required for AI processing and license verification.

---

## Troubleshooting
* **No Response:** Ensure your microphone is active. Check Window > Toggle System Console for detailed error logs.
* **API Errors:** Verify your API key is correct and your service provider account has an active balance/quota.
* **Initialization Hang:** The first time you click "Load Voice Model", Blender may freeze for a moment—this is normal.
