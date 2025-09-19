# multimodal-parsing-demo

This demo shows how to parse **audio + video data** into a structured dataset for downstream **LLM and multimodal tasks**.

### Idea
- Extract **spectrograms** and **MFCCs** from audio 
- Transcribe audio with **OpenAI Whisper-small**
- Sample video frames with **OpenCV**
- Store results in a **pandas DataFrame** linking transcript, audio features, and image frame paths
