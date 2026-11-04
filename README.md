# 20262RCOSE32202
Process: 실행 중인 프로그램, 자원 할당의 단위
PCB (Process Control Block): process 정보를 담는 커널 자료구조 (Linux: task_struct)
Context switch: PCB에 상태 저장 후 다른 process 상태 복원
Mode switch: user mode ↔ kernel mode 전환
System call: user mode에서 kernel mode로 들어가는 통로
