# Thread

- **Thread**: 프로세스 내부의 독립적인 실행 흐름.
- **Multithreading**: 하나의 프로세스에서 여러 Thread를 실행하여 응답성과 병렬 처리 성능 향상.
- **Shared Resources**: 같은 프로세스의 Thread들은 Code, Data, Heap 등을 공유.
- **Private Resources**: 각 Thread는 개별 Program Counter, Register, Stack 등을 가짐.
- **TCB**: Thread ID와 실행 문맥 등 Thread 관리 정보 저장.
- **User-level Thread**: 사용자 공간의 라이브러리에서 관리.
- **Kernel-level Thread**: 커널이 Thread를 인식하고 직접 스케줄링.
- **Thread Pool**: Thread를 미리 생성하여 반복적인 생성·삭제 비용 감소.
- **Concurrency vs Parallelism**: 작업들의 진행을 번갈아 처리하는 것과 실제 동시에 실행하는 것의 차이.
- **Pthreads**: pthread_create()로 Thread 생성, pthread_join()으로 종료 대기.
