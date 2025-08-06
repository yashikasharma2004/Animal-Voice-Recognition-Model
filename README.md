# Animal-Voice-Recognition-Model
# Animal Voice Recognition Model 🐾🎙️
This project uses Teachable Machine (Audio Project) to recognize and classify animal sounds like cat, dog, cow, crow, and peacock. The model was trained using microphone input and exported in TensorFlow.js format for easy use in web applications.

The following classes were included:
- 🔇 Background (silence, fan, keyboard tap)
- 🐱 Cat (meow)
- 🐶 Dog (bark)
- 🐄 Cow (moo)
- 🐦 Crow (caw)
- 🦚 Peacock (call)

Each class contains 10 audio samples of approximately 1 second each, collected using a laptop microphone. Background class was included to help the model differentiate between actual animal sounds and ambient noise.

The files included are:
- `model.json` – Model architecture
- `metadata.json` – Class labels
- `weights.bin` – Trained weights
- `README.md` – Project details

The model can be integrated in a browser using TensorFlow.js. This project was built for educational purposes and can be expanded further with more animal classes and samples.

Created with ❤️ using Teachable Machine
