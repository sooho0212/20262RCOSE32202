# 20262RCOSE32202
Process: 실행 중인 프로그램, 자원 할당의 단위
PCB (Process Control Block): process 정보를 담는 커널 자료구조 (Linux: task_struct)
Context switch: PCB에 상태 저장 후 다른 process 상태 복원
Mode switch: user mode ↔ kernel mode 전환
System call: user mode에서 kernel mode로 들어가는 통로
Trap vs Interrupt: 동기(내 명령어) vs 비동기(외부 장치)
fork(): process 복제, parent는 child PID / child는 0 반환
exec(): 현재 process를 새 프로그램으로 교체
