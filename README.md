# 🎙️ 음성 비서 프로그램

> AI 기반 음성 인식 챗봇 서비스

🔗 **서비스 바로가기**: [https://voicebot-ftudatsgedhwadz5be3pzt.streamlit.app/](https://voicebot-ftudatsgedhwadz5be3pzt.streamlit.app/)

---

## 📌 소개

마이크로 질문하면 AI가 음성으로 답변해주는 **음성 비서 프로그램**입니다.

- **UI**: [Streamlit](https://streamlit.io/)
- **STT** (Speech-To-Text): OpenAI Whisper AI
- **답변 생성**: OpenAI GPT 모델 (gpt-4 / gpt-3.5-turbo)
- **TTS** (Text-To-Speech): Google Translate TTS (gTTS)

---

## 🚀 사용 방법

1. 사이드바에 **OpenAI API 키** 입력
2. 사용할 **GPT 모델** 선택 (gpt-4 또는 gpt-3.5-turbo)
3. **"클릭하여 녹음하기"** 버튼으로 질문 녹음
4. AI의 텍스트 + 음성 답변 확인

---

## 🛠️ 기술 스택

| 구분 | 기술 |
|------|------|
| Frontend | Streamlit |
| STT | OpenAI Whisper |
| LLM | OpenAI GPT-4 / GPT-3.5-turbo |
| TTS | gTTS (Google Text-to-Speech) |
| 음성 녹음 | audiorecorder |

---

## ⚙️ 로컬 실행

```bash
pip install -r requirements.txt
streamlit run ch03_voicebot.py
```

