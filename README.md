
# Labeling

## Download VoTT
라벨링에 하는 방법에 대해 설명 드리겠습니다.

라벨링 툴은 마이크로소프트 사의 VoTT를 사용합니다.<br>
링크: https://github.com/Microsoft/VoTT/releases
<br>
<br>
<img src="http://localhost:8888/files/jjnn/ds/img/release.PNG" alt="Drawing" style="width: 1000px;"/>
자신의 OS에 맞는 버전을 다운 받으시면 되겠습니다.<br>
<br>

## Create Project 
먼저 처음 화면은 이렇습니다.<br>

<img src="http://localhost:8888/files/jjnn/ds/img/initial%20Screen.PNG" alt="Drawing" style="width: 800px;"/>

1. new Project를 선택

<img src="ds/img/project_setting.PNG" alt="Drawing" style="width: 800px;"/>
2. `Sorce Connection*` 옆에 `ADD Connection` 클릭 -> 경로는 라벨링할 비디오가 있는 폴더로 설정!



<img src="http://localhost:8888/files/jjnn/ds/img/add_connection.PNG" alt="Drawing" style="width: 800px;"/>
3. `Target Connection*` 클릭 -> `DreamShake` 선택
4. `Video Setting*` 을 3으로 설정 -> 초당 3프레임씩 라벨링 해줄것입니다
5. `Tags`에 'sports ball', 'person', 'goal' 이렇게 세개만 일단 추가해줍니다. (추가 Enter)

6. 마지막 화면이 이렇게 되어 있어야 합니다.(확대해서 보시길 ctrl+마우스휠)
<img src="http://localhost:8888/files/jjnn/ds/img/final_screen.PNG" alt="Drawing" style="width: 1000px;"/>
7. 오른쪽 목록에 자신이 만든 프로젝트 선택


## Labeling! (like a machine)


1. Editor Shortcuts
기계처럼 해야 하는 작업이므로 shortcut 숙지는 필수 입미다!

마우스 드래그 - 라벨링!!!!

- V - Pointer/Select
- R - Draw Rectangle

- W or ArrowUp - Previous Asset
- S or ArrowDown - Next Asset
- When the video playback bar is present, it allows the following shortcuts to select frames:

- A or ArrowLeft - Previous Frame
- D or ArrowRight - Next Frame
- Q - Previous Tagged Frame
- E - Next Tagged Frame

- Mouse Controls
    - Two-point mode - Hold down Ctrl while creating a region
    - Square mode - Hold down Shift while creating a region
    - Multi-select - Hold down Shift while selecting regions
    - Exclusive Tracking mode - Ctrl + N to block frame UI allowing a user to create a region on top of existing regions
    
reference: https://github.com/microsoft/VoTT#keyboard-shortcuts

2. labeling tip
- 선수들은 타이트하게 박스안에 넣어주기!
- 완전히 겹치지만 않으면 라벨링 해주기 (그림 참조)
- 공도 빼먹지 말고!
- 골장면도 빼먹지 말고!
<img src="http://localhost:8888/files/jjnn/ds/img/ex1.PNG" alt="Drawing" style="width: 1000px;"/>
<img src="http://localhost:8888/files/jjnn/ds/img/ex1.1.PNG" alt="Drawing" style="width: 1000px;"/><br><br>
보시면 박스하나에 여려개의 라벨링을 달아줄수 있습니다. 다음과 같이 골들어갈때 goal과 ball 두개의 라벨을 달아줍니다.
<img src="http://localhost:8888/files/jjnn/ds/img/ex2.PNG" alt="Drawing" style="width: 1000px;"/>
<img src="http://localhost:8888/files/jjnn/ds/img/ex2.1.PNG" alt="Drawing" style="width: 1000px;"/>

그럼 저는 20000<br>
모두 Shak'it! Shak'it! DreamShake!!!!


```python

```
