# What is that?
파일을 하나하나 설명을 해주겠다. 그러니 </strong>괜히 다른거 건드리지 말고 이 문서를 읽어 주길 바란다</strong>. </br>

# "result" directory
"result" 라는 디렉토리는 Python 코드를 돌리면 나오는 .xml 파일들을 정리 한 것이다. </br>
"result" 안에 있는 결과들은 지워도 상관은 없다. 하지만 "result" 디렉토리는 지우면 안된다. </br>

# "face_eye_detection.py" code
<strong>🙇‍♂️🙇‍♀️🤝코드를 설명하기 전에 이 코드는 "PythonProgramming.net"을 기반으로 짜여진 코드이다.🤝🙇‍♀️🙇‍♂️</strong> </br>
[오픈 소스 링크](https://pythonprogramming.net/haar-cascade-face-eye-detection-python-opencv-tutorial/) - 오픈소스 파이썬 코드 </br>

주 메인 코드이자 하나 밖에 없는 코드이다. 이 코드를 하나하나 뜯어보면서 설명할 예정이다. </br>
[코드 링크](https://github.com/insung3511/OpenCV_Face_detection_code/blob/master/openCV_EYE/face_eye_detection.py) - Github 코드 링크
</br> </br>
9번째와 10번째 코드를 보자.
<pre>
all_count = 0     #Checking finding count
true_count = 0    #Checking detection count
</pre>
</br>
얼굴을 얼마나 인식율이 확인하기 

<pre>
def mylog(start_time, end_time, count):   #show real-time result
    print ('st:%s, et:%s, cnt:%s', start_time, end_time, count)
</pre>

# 
