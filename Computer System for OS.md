# Computer System for OS

- **Computer Components**: CPU, Memory, I/O Device 등이 Bus를 통해 연결.
- **Bottleneck**: 장치 간 속도 차이로 시스템 성능이 제한되는 현상.
- **Hierarchical Bus**: System Bus와 I/O Bus 등을 분리하여 병목 완화.
- **Instruction Execution**: 프로그램을 메모리에 적재한 뒤 CPU가 명령어를 순차적으로 실행.
- **Execution Mode**: User Mode와 Kernel Mode로 구분하여 시스템 보호.
- **Trap**: 실행 중인 명령어에 의해 발생하는 동기적 이벤트. 예: System Call.
- **Interrupt**: 외부 장치 등에 의해 발생하는 비동기적 이벤트. 예: I/O 완료.
- **Event Handler**: 발생한 이벤트를 처리하는 코드. 처리 후 기존 실행 흐름을 재개할 수 있음.
