# 얼굴 인식 

실행결과

![결과1](https://user-images.githubusercontent.com/114050357/229764460-40ec5171-9079-4c15-93de-ccf5d7b67e0a.jpg)


현 사진은 여성일 확률이 높고 상태는 웃고 있다는 것과 15~19살의 연령대일 확률이 높다는 결과가 나왔다.

![결과2](https://user-images.githubusercontent.com/114050357/229764760-54230609-1d1a-4dd2-9388-ca64b552953c.jpg)

이미 유명한 사람의 사진을 사용하였지만, 닮은사람의 결과로 ’김태연‘이 나왔다.


개요
import에서 requests는 웹서버에 HTTP 요청을 보내기 위해 사용하고,
matplotlib.pyplot와 matplotlib.patches는 시각화를 생성하고 사용자 정의하는 데 사용하고,
json은 JSON 데이터를 처리하기 위해 사용되고, 
matplotlib.image는 이미지를 로드하고 표시하기 위해 사용된다. 

이 코드는 네이버의 얼굴 감지 API를 사용하여 "testImage.jpg"라는 이미지 파일에서 얼굴을 감지하고 분석하는 Python 코드이다. 코드 내 변수 client_id와 client_secret 변수를 사용하여 네이버 API에 인증 정보를 제공한다. 그런 다음 requests.post 함수를 사용하여 이미지 파일을 네이버의 얼굴 감지 API에 전송하고, 응답으로 얼굴 감지 결과가 반환되며, 이 결과는 json.loads 함수를 사용하여 파싱된다. 
이 코드는 그래서 얼굴의 위치, 성별, 감정 및 나이 정보를 추출하고 matplotlib을 사용하여 이미지 위에 얼굴의 위치와 정보를 표시한다













