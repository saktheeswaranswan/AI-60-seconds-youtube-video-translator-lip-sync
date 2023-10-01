# Video-Translation
A simple Google Colab notebook which can translate an original video into multiple languages along with lip sync.

How it works?

1: Upload video
2: Extract audio and get text from the video (OpenAI Whisper)
3: Translate the text (Google Translate)
4: Synthesize the translated text with the original voice (coqui-ai TTS)
5: Lip sync the synthesized audio with the original video clip (OpenTalker video-retalking || Wav2Lip)

The links for the repos mentioned above are given in the notebook itself.