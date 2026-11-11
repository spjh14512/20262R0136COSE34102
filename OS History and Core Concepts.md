# OS History and Core Concepts

- **Batch System**: 여러 작업을 순서대로 자동 실행하는 방식. I/O 작업 중 CPU가 유휴 상태가 되는 문제가 있음.
- **Spooling**: I/O 요청을 버퍼에 저장하여 CPU 연산과 I/O를 병행.
- **Multiprogramming**: 여러 프로그램을 메모리에 적재하고, I/O 대기 중 다른 프로그램을 실행하여 CPU 활용률 향상.
- **Time-sharing**: CPU 시간을 Time Slice로 나누어 여러 프로그램에 할당. 공정성과 응답성 향상.
- **Multitasking**: 여러 프로그램이 CPU 등의 자원을 공유하며 실행.
- **Concurrency**: 여러 작업이 번갈아 실행되며 진행되는 것. 실제 동시 실행인 Parallelism과 구분.
- **Linux**: Linux Kernel은 OS의 핵심이며, Linux Distribution은 커널과 라이브러리, 응용 소프트웨어 등을 포함.
