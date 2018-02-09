# What is that? 🗂
파일을 하나하나 설명을 해주겠다. 그러니 </strong>괜히 다른거 건드리지 말고 이 문서를 읽어 주길 바란다</strong>. </br>

# "result" directory 📁📂
"result" 라는 디렉토리는 Python 코드를 돌리면 나오는 .xml 파일들을 정리 한 것이다. </br>
"result" 안에 있는 결과들은 지워도 상관은 없다. 하지만 "result" 디렉토리는 지우면 안된다. </br>

# "face_eye_detection.py" code 😂📸
<strong>🙇‍♂️🙇‍♀️🤝코드를 설명하기 전에 이 코드는 "PythonProgramming.net"을 기반으로 짜여진 코드이다.🤝🙇‍♀️🙇‍♂️</strong> </br>
[오픈 소스 링크](https://pythonprogramming.net/haar-cascade-face-eye-detection-python-opencv-tutorial/) - 오픈소스 파이썬 코드 </br>

주 메인 코드이자 하나 밖에 없는 코드이다. 이 코드를 하나하나 뜯어보면서 설명할 예정이다. </br>
[코드 링크](https://github.com/insung3511/OpenCV_Face_detection_code/blob/master/openCV_EYE/face_eye_detection.py) - Github 코드 링크
</br> </br>

9번째와 10번째 코드를 보자.
<pre>
9  all_count = 0     #Checking finding count
10 true_count = 0    #Checking detection count
</pre>
얼굴을 얼마나 인식율이 확인을 위해서 생성한 변수이다. 변수들의 이름을 따로 바꾸면 다른 코드도 수정해야한다.</br>
all_count 변수는 <strong>얼굴을 인식을 시도하는 총 횟수</strong>를 말한다. 
true_count 변수는 <strong>10초 동안 얼굴이 인식이 된 횟수</strong>를 말한다. </br>
</br> 12번째 ~ 16번째 코드 </br>
<pre>
12  def mylog(start_time, end_time, count):   #show real-time result
13      print ('st:%s, et:%s, cnt:%s', start_time, end_time, count)
14    
15  #open result CSV file
16  file = open('./result/res_Insert_name.csv', 'w')
</pre>
(12 ~ 13)
얼굴을 인식한 값들 즉 측정시간, 인식 횟수를 하나의 문자로 바꾸는 코드이다. </br>
이 코드는 나중에 result 디렉토리안에 있는 csv 파일에 넣는데 필요한 코드이다. [(CSV 파일 링크)](https://github.com/insung3511/OpenCV_Face_detection_code/tree/master/openCV_EYE/result) </br>
start_time은 측정을 시작한 초이다. end_time은 누적 시간을 말하는데 총 인식한 시간을 말한다. conut는 얼마나 인식이 되었는지 말한다. </br> </br>
(16)
r
</br> 


<pre>
