# iot-automatic-recycling-bin

# arduino.ino

- 푸시버튼과 금속센서를 연결시킨 아두이노에 입력시킨 코드
- 비금속이면 '0' 출력, 금속이면 '1' 출력

# push_client_ras.py

- 시리얼 통신을 통해 아두이노 파일과 통신
- all.py와 소켓을 통해 통신

# all.py

1. 소켓을 통해 비금속/금속 확인
2. 비금속일 경우 종료
3. 금속일 경우 카메라로 쓰레기 촬영
4. 서버에 유리인지 플라스틱인지 분석 Http 요청

# 영상 링크
https://youtu.be/bhTwaFPkd2s
