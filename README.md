# jetbot
-------------------------------------------------------------------------------------------------------------
## STEP0

1. SD card formet
- 용량 확보 및 불필요한 데이터 제거
2. flash meomory
-Jetbot image 굽기
- 링크: https://drive.google.com/file/d/1G5nw0o3Q6E08xZM99ZfzQAe7-qAXxzHN/view
- Balena Etcher 설치
-  메모리 플래시 하기

![image](https://user-images.githubusercontent.com/102523600/200292038-0411aabb-7f87-48e1-b243-d774ea1abed1.png)
- 다음과 같은 창이 뜬다.
3. put SD card in jetbot
--------------------------------------------------------------------------------------------------------------
## STEP1

1. jetbot 전원 켜기
2. jupyter lab 연결(주소창에 'jetbot 주소:8888') ex)172.16.60.253:8888
3. Basic Motion 실행

![image](https://user-images.githubusercontent.com/102523600/203035577-c80fdf0e-6722-402b-a601-946d7011e8c8.png)
![image](https://user-images.githubusercontent.com/102523600/203035624-cff094a4-bacc-4f16-a794-df8071bf316a.png)
- 위와 같은 과정을 거친다면 다음과 같은 창이 뜬다
![image](https://user-images.githubusercontent.com/102523600/203035922-5199290c-1327-46aa-8716-565b95d6c164.png)
![image](https://user-images.githubusercontent.com/102523600/203038165-8e479a74-edc9-41b1-b6da-23a72dc95e2a.png)

- 다음과 같이 셀 클릭 후 실행

4.robot.py를 통한 수정하기

![image](https://user-images.githubusercontent.com/102523600/203036950-f1d48876-0c9a-4b0f-93c1-b5852ae58af7.png)
![image](https://user-images.githubusercontent.com/102523600/203037056-c8e29445-1222-4195-92cc-791e8cb42c55.png)
![image](https://user-images.githubusercontent.com/102523600/203037158-75620e76-ecb3-49a3-9cd4-629e75448656.png)
![image](https://user-images.githubusercontent.com/102523600/203037268-b16e1949-46ab-4800-b2c4-a7f230f41119.png)
![image](https://user-images.githubusercontent.com/102523600/203037356-632f85be-e6dd-43e4-aa0e-8c5791c5adf4.png)
- 위의 부분을 통해 수정가능 (-)를 붙이면 모터 방향 반대
 
![image](https://user-images.githubusercontent.com/102523600/203039023-e6f761f5-6635-43d1-8877-eb2b952aa863.png)
![image](https://user-images.githubusercontent.com/102523600/203039216-9181db82-ae4f-4d9a-a590-c660aca48225.png)
![image](https://user-images.githubusercontent.com/102523600/203039351-2700eb9e-e17f-4036-b6f4-52d162e41fc8.png)

- 다음 과정을 통해 명령어 수정 가능


-------------------------------------------------------------------------------------------------------
# 문제점
- 명령어를 수정했음에도 불구하고 동작이 바뀌지 않았다
## 해결방법

![image](https://user-images.githubusercontent.com/102523600/203040310-ede9a0e2-2acf-45a8-855e-73c794c97374.png)

- 다음과 같이 위젯의 위치를 바꿈으로써 해결할 수 있다(그러나 특정 위젯에서 밖에 허용되지 않는다)
