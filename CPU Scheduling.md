# CPU Scheduling

- **CPU Scheduling**: Ready 상태의 프로세스 중 다음 실행 대상을 선택.
- **CPU Burst / I/O Burst**: CPU 연산 시간과 I/O 대기 시간.
- **Scheduling Criteria**: CPU Utilization, Throughput, Turnaround Time, Waiting Time, Response Time.
- **Preemptive Scheduling**: 실행 중인 프로세스에서 CPU를 강제로 회수할 수 있음.
- **FCFS**: 도착 순서대로 실행. Convoy Effect 발생 가능.
- **SJF**: CPU Burst가 가장 짧은 작업부터 실행.
- **SRTF**: SJF의 선점형 방식.
- **Priority Scheduling**: 우선순위 기반 실행. Starvation 문제 발생 가능.
- **Round Robin**: Time Quantum 단위로 CPU 할당. 짧은 Quantum은 응답성을 높이지만 Context Switch 비용 증가.
- **MLFQ**: 여러 우선순위 Queue를 사용하고, Aging 등을 통해 Starvation 완화.
