## 1. 리눅스 명령어 

- _top, ps, jobs, kill_ __명령어__ 

|명령어|설명|
|:----:|:-------------------------|
|top|시스템 프로세스/메모리 사용 현황을 실시간으로 출력하는 리눅스 명령어|
|ps|현재 실행중인 프로세스르 보여주는 리눅스 명령어|
|jobs|작업이 중지된 상태나 백그라운드로 진행 중인 상태를 표시하는 리눅스 명령어|
|kill|프로세스에 종료 시그널을 보내는 리눅스 명령어(-9는 강제 종료)|

- ps 명령어 사용 예시

<img src = "https://user-images.githubusercontent.com/104217126/171991912-ac36a91e-0dd7-477c-b120-d11cfc4e7757.png" width ="1000" height = "100" >




---
## 2. vim 명령어 

- 에디터에서 ___매크로___ 사용방법에 대하여 조사하기 (q , @)

|명령어|설명|
|:----:|:-------------------------|
|q|__Vim Macro 기록 & 기록 종료__|
||Normal Mode에서 q를 입력하면, 하단 상태표시줄에 q가 표시되고, 이는 앞으로 기록할 레지스터를 지정해주기를 대기하고 있는 상태이다|
|@|__Vim Macro 실행하기__|
||@로 특정 레지스터에 저장된 매크로를 실행시킬 수 있다|



---
- README.md 파일로 코드 정리하기

```c++
#include <iostrema>
using namepsace std;

class Readme {};

int main () {
  cout << "항상 수고 많으십니다 교수님!" << endl;
}
```
