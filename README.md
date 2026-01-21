# audio_task
# TTS Script Prompt for ElevenLabs

You are a friendly AI narrator.
Read the following text clearly and naturally.
Tone: Inspiring, calm, professional
Speed: Medium
Emotion: Positive

Script:
"Welcome to AI tutorials! Today we explore how artificial intelligence can create voice and music.
With modern tools, you can turn any text into natural speech in just a few seconds.
You can also generate background music for videos, podcasts, and social media.
AI makes content creation faster, easier, and more creative.
Let’s start learning and building with AI today!"

# Voice Cloning Script Prompt

Voice Style:
Natural, friendly, neutral accent
Emotion: Calm and confident

Script:
"Hello! This is a demo of voice cloning using artificial intelligence.
With just a short voice sample, AI can recreate a natural-sounding voice.
This technology is useful for videos, audiobooks, and virtual assistants.
Welcome to the future of digital voice!"

# Wedding Invitation Video 🎬💍

Кинематографиялық вертикаль видео-приглашение жасауға арналған дайын сюжет пен prompt.  
Text-to-Video құралдарына (Pika Labs, Luma, т.б.) қолдануға болады.

---

## 📱 Видео форматы
- Ұзақтығы: 12–15 секунд  
- Формат: Vertical (9:16)  
- Стиль: Cinematic / Reels  

---

## 🎥 Video Prompt (Russian)

from gtts import gTTS

text = """
Сегодня искусственный интеллект меняет способ создания контента.
Он может писать сценарии,
превращать текст в реалистичный голос,
создавать музыку без музыкантов
и собирать видео за считанные минуты.

То, что раньше занимало часы,
теперь делается автоматически.

AI — это не будущее.
Это уже реальность.
"""

tts = gTTS(text=text, lang="ru")
tts.save("voice.mp3")

print("Озвучка готова")
