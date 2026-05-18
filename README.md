# Weather Alert

매일 아침 실행하면 오늘의 날씨를 알려주는 **간단한 Python 스크립트**입니다.  
OpenWeather API를 사용하여 원하는 도시의 현재 날씨를 확인할 수 있습니다.

---

## 기능
- 현재 날씨 확인
- 기온 표시 (섭씨)
- 간단한 CLI 인터페이스 제공

---

## 설치 및 실행 방법

1. 레포지토리 클론
   ```bash
   git clone https://github.com/username/WeatherAlert.git
   cd WeatherAlert
2. 스크립트 실행 Bash셸 -> python weather_alert.py
3. 입력값
- 도시 이름 (예: Seoul)
- OpenWeather API 키

사용예시:
- 날씨 알림 스크립트 시작
- 도시 이름을 입력하세요 (예: Seoul): Seoul
- OpenWeather API 키를 입력하세요: YOUR_API_KEY

결과:
- 🌤️ Seoul의 현재 날씨: 맑음, 온도: 22°C

요구사항
- Python 3.x
- requests 라이브러리(pip install requests)
