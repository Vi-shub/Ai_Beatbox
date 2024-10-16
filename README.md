# 🎤 BeatBox AI

BeatBox AI is an innovative AI-driven web application that analyzes and generates drum sequences using cutting-edge deep learning techniques. The application leverages Convolutional Neural Networks (CNNs) to classify drum sounds based on audio spectrograms and Recurrent Neural Networks (RNNs) for generating rhythmic drum sequences in real time.

## 🌐 Live Demo

Check out the live version of the project here: [BeatBox AI](https://ai-beatbox.vercel.app/)

## 🚀 How It Works

1. **Audio Classification**:
   - **Convolutional Neural Networks (CNNs)** are employed to analyze and classify audio segments, specifically identifying different drum kit sounds (e.g., Kick, Snare, Hi-hat) based on their spectrograms.
   - The model is trained to recognize key drum sounds using labeled data and outputs the identified drum class.

2. **Rhythm Generation**:
   - **Recurrent Neural Networks (RNNs)**, specifically LSTM (Long Short-Term Memory) layers, are used to generate coherent drum patterns based on a sequence of beats.
   - This AI-generated sequence can be played back or exported, allowing users to create unique drum beats automatically.

3. **Technology Stack**:
   - Built with **Magenta.js**, **TensorFlow.js**, and **p5.js** to bring interactive AI music generation to the browser.

## 🎶 Key Features

- **Audio Analysis**: Uses a pre-trained CNN model to classify various drum sounds such as Kick, Snare, Hi-hat, Tom, Clap, and Rim.
- **Real-time Drum Sequence Generation**: Leverages an LSTM-based RNN to generate drum rhythms based on user input or pre-defined patterns.
- **User-friendly Interface**: Simple, intuitive web interface for users to record, analyze, and play back their drum sequences.
- **Browser-based**: No need to install additional software. Everything runs in the browser using JavaScript libraries like Magenta.js and TensorFlow.js.

## 🛠️ Technologies Used

- **Magenta.js**: A JavaScript API for music and art generation using machine learning.
- **TensorFlow.js**: Enables the use of pre-trained TensorFlow models for classification and rhythm generation directly in the browser.
- **p5.js**: A JavaScript library for creating visual art and interactive experiences in the browser.
- **HTML/CSS/JavaScript**: For building the web interface and connecting frontend interactions to the AI backend.

## 🥁 Drum Kit Classes

The model classifies the following drum sounds:
- Kick
- Snare
- Hi-hat (closed)
- Hi-hat (open)
- Tom (low, mid, high)
- Clap
- Rim

## 🔥 Getting Started

### Prerequisites

- A modern web browser with WebGL support.
- A basic understanding of machine learning models (helpful but not required).

### Installation

**Clone the Repository**:
   ```bash
   git clone https://github.com/Vi-shub/Ai-beatbox.git
   cd beatbox-ai
   run index.html
   ```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
