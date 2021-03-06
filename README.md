# aiffel-exp3

![image](https://user-images.githubusercontent.com/31565895/148874749-81322978-21c9-4b9b-8957-732743ba588b.png)
![image](https://user-images.githubusercontent.com/31565895/148874784-6025f8b9-8b95-4139-8a9e-f9a5509556cc.png)
![image](https://user-images.githubusercontent.com/31565895/148874791-654578d8-fa2d-4bcc-af84-692ad19361ae.png)
![image](https://user-images.githubusercontent.com/31565895/148874795-29a1e162-f1c3-46fe-b285-1aa638d4385c.png)
![image](https://user-images.githubusercontent.com/31565895/148874772-73569aae-30ee-4203-8e31-cbd124141843.png)

Q. 얼굴 각도에 따라 스티커가 어떻게 변해야할까요?
- A. 얼굴 각도에 따라 스티커의 X, Y Scale이 바뀌어야 하며, 그 외에도 원근감에 맞도록 이미지가 변형되어야 한다.

Q. 멀리서 촬영하면 왜 안될까요? 옆으로 누워서 촬영하면 왜 안될까요?
- A. 멀리서 촬영하면 정밀한 Face Detection이 어려울 뿐더러, Sticker의 사이즈도 변화해야 한다. 옆으로 누워서 촬영해도 마찬가지로 Face Detection과 스티커를 합성하는 과정에서 Rotation 과정이 필요하다.

Q. 실행 속도가 중요할까요?
- A. 단순히 단일 이미지 합성이라면 실행 속도는 크게 중요하지 않을듯 하다. 그러나, 이미지가 실시간으로 변화하는 서비스(ex, 스티커 카메라 앱)을 만드는 경우 실행속도는 중요하다.

Q. 스티커앱을 만들 때 정확도가 얼마나 중요할까요?
- A. 정확도가 높을수록 스티커의 위치가 자연스러워지므로 결과 이미지의 퀄리티가 높아진다. 스티커 앱의 경우 결과 이미지의 품질이 서비스 만족도의 대부분을 차지한다. 그만큼 정확도의 중요도가 높은 편이다.

