# 역사 인물 AI 인터뷰 — 무료 API 버전

## 사용 API
- 답변 생성: Groq Free Plan — `qwen/qwen3.8-27b`
- 음성 생성: Google Gemini 3.8 Flash TTS — `gemini-3.8-flash-tts`
- 학생 음성 입력: Chrome Web Speech API — 별도 API 키 없음

현재 Google 공식 가격표에서 Gemini 3.8 Flash TTS는 Standard 기준 Free Tier가 표시되어 있습니다. 무료 한도와 모델 정책은 변경될 수 있습니다.

## 사용
1. Groq에서 API Key 발급
2. Google AI Studio에서 Gemini API Key 발급
3. `index.html`을 Chrome에서 실행
4. 두 키 입력 → 마이크 권한 → API 연결 테스트 → 시작

## 주의
이 프로토타입은 브라우저에서 API를 직접 호출하므로 API 키가 브라우저에 노출될 수 있습니다. 여러 교사에게 최종 배포할 때는 서버리스 백엔드/프록시로 API 키를 보호하는 방식을 권장합니다.
