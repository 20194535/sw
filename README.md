## 리눅스 명령어
**1) top**
시스템 프로세스/메모리 사용 현황을 실시간으로 출력해준다.

top [옵션]  으로 사용할수 있으며 옵션이 없다면 interval간격으로 화면을 갱신하며 정보를 보여준다.
- 옵션
1) -b : 배치모드로 정보를 출력한다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력한다.
2) -d delay : 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력한다.
3) -i idle : 토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않는다.
4) -n num : 지정한 시간(num)만큼 업데이트 정보를 출력한다.
5) -p pid : 지정한 프로세스 ID(pid)의 정보만을 출력한다.
6) -q : 시간의 간격 없이 계속하여 업데이트 정보를 출력한다.
7) -s : 몇 개의 대화식 명령을 비활성화한다(시큐어 모드).
8) -S : 누적된 정보를 출력한다(cumulative 모드).

- top 단축키 명령어
1) space : 정보를 업데이트한다.
2) ^L : 스크린을 다시 초기화한다.
3) F or f : 필드를 추가나 제거한다. 아래 ‘top 항목에 대한 설명’을 참조한다. 확인하고자 하는 항목의 알파벳을 누를 때마다 선택/취소가 반복된다.
4) O or o : 출력하는 필드의 정렬 순서를 변경한다. 아래 ‘top 항목에 대한 설명’을 참조하자. 대문자로 선택한 항목을 누르면 왼쪽으로 이동하고 소문자를 누르면 오른쪽으로 이동한다.
5) h or ? : 사용 가능한 명령어를 출력한다.
6) k : 프로세스를 종료시킨다.
7) n or # : 출력할 프로세스의 수를 지정한다.
8) s : 출력할 정보의 업데이트 시간을 지정한다.
9) W : ~/.toprc에 설정된 내용을 저장한다.
10) q : top을 종료한다.

- top 보기 수정 단축키
출력되는 메인 정보 창 중에 상단의 정보를 수정한다.
1) S : cumulative 모드(실시간 정보를 누적 데이터로 보여 줌)를 선택/해제한다.
2) i : idle 프로세스 정보를 출력한다/해제한다.
3) I : Irix나 솔라리스 정보를 출력한다/해제한다.
4) c : 명령행에서 실행한 명령어 자체로 출력한다/해제한다.
5) l : 로드 평균 정보를 출력한다/해제한다.
6) m : 메모리 정보를 출력한다/해제한다.
7) t : 요약된 정보만을 출력한다/해제한다.

- top 정렬 단축키
메인 창에서 실행하는 명령으로 현재 정보를 사용자의 요구대로 정렬한다.
1) r : 프로세스의 우선순위를 변경한다.
2) N : pid 정보를 기준으로 정렬한다.
3) A : age 정보를 기준으로 정렬한다.
4) P : CPU 사용량을 기준으로 정렬한다.
5) M : 적재된 메모리 사용량을 기준으로 정렬한다
6) T : 시간/누적시간을 기준으로 정렬한다.
7) u : 지정한 사용자의 정보만을 출력한다.

**2) ps**
프로세스의 현재 상태를 출력한다.

