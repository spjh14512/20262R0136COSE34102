# Trap and Interrupt Summary

- **Trap**: 현재 실행 중인 명령어에 의해 발생하는 Synchronous Event.
- **Interrupt**: Timer 또는 I/O 장치에서 발생하는 Asynchronous Event.
- **Trap Handling**: 프로세스의 실행 상태를 보존하고 Handler 실행 후 결과를 전달.
- **Interrupt Handling**: 현재 프로세스의 상태를 저장하고, 필요하면 다른 프로세스를 실행.
- **Mode Switch**: User Mode와 Kernel Mode 사이의 CPU 실행 모드 전환.
- **Context Switch**: CPU에서 실행할 프로세스를 변경하는 작업.
- **비용 비교**: Context Switch는 실행 문맥 및 주소 공간 정보 변경이 필요하므로 일반적으로 Mode Switch보다 비용이 큼.
