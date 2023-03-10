### 프로세스 간 통신 중 메시지 전달을 하는 방법에는 어떤 것들이 있나요?

### 피터슨 알고리즘이 무엇인가요?

### 뮤텍스와 세마포어의 차이점은 무엇인가요?

- 그렇다면, 이진 세마포어와 뮤텍스의 차이점은 무엇인가요?

### 예상질문

Q. 교착상태에 대해서 간단히 설명해주세요.  
A. 둘 이상의 스레드가 다른 스레드가 점유하고 있는 자원을 서로 기다릴 때 무한 대기에 빠지는 상황  
<br>
Q. 경쟁상태란 무엇인가요?  
A. 여러 프로세스 및 스레드가 공유 자원에 동시 접근 시 그 순서에 따라 결과가 달라지는 문제  
<br>
Q. 상호 배제, 임계구역, 경쟁에 대해 설명해보세요.  
A. 여러 스레드가 임계구역에 대해서 경쟁을 할 때 상호배제가 이루어져야만 스레드 동기화가 보장됨
<br>
Q. 세마포어는 어떤건가요?  
A. 세마포어는 여러개의 프로세스가 접근 가능한 공유자원을 관리하는 방식 중 하나로  
 모든 교착 상태를 해결하지는 못함  
<br>
Q. 임계 구역 문제를 해결하기 위한 3가지 조건은 무엇이고 각각을 설명해주세요  
A. 상호 배제, 한정 대기, 진행의 융통성이 있음  
 상호 배제는 한 프로세스만 임계 구역을 사용해야 한다는 조건이고,  
 한정 대기는 특정 프로세스가 무한히 대기해서는 안된다는 조건이고,  
 진행의 융통성은 임계 구역이 비어있는 경우, 임계 구역을 대기하던 프로세스들만  
 해당 임계 구역으로 진입할 수 있는 결정에 참여 가능하다는 조건

- 바쁜 대기란?
- 임계구역이란?
- 경쟁 조건이란?
- 임계구역문제 해결방법

- 교착상태의 발생 조건 4가지를 설명해주세요.
- 뮤텍스가 뭘까요?
- 이진 세마포어는 왜 이진 세마포어 인가요?

- 파이프를 이용한 통신방식에 대해서 설명해주세요
- 양방향 통신을 할때 왜 파이프를 2개를 써야 하나?

- 익명 파이프와 네임드 파이프는 어떻게 다른가요?

- 소켓이 뭔가요?

- 소켓을 이용한 통신방식에 대해서 설명해주세요

- 임계구역이 뭔가요?
- 임계구역 해결 조건에는 어떤게 있을까요?

- 교착 상태(dead lock)가 뭔가요?

- 교착 상태, 경쟁 상태, 기아상태는 서로 어떤점에서 다른가요?

- 피터슨 알고리즘 & 데커 알고리즘과 세마포어의 차이점이 뭔가요?

- 세마포어의 진행과정을 설명해주세요

- 소켓 통신이 진행되는 과정을 설명해주세요

- 동기와 비동기
