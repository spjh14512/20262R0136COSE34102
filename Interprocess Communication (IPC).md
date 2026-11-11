# Interprocess Communication (IPC)

- **IPC**: 독립된 프로세스들이 데이터를 교환하고 협력하기 위한 메커니즘.
- **Shared Memory**: 여러 프로세스가 같은 메모리 영역을 공유. 빠르지만 Synchronization 필요.
- **Message Passing**: Kernel을 통해 메시지를 전송. send()와 receive() 사용.
- **Signal**: 특정 프로세스에 이벤트를 통지.
- **Pipe**: 프로세스 사이에서 데이터를 단방향으로 전달.
- **Message Queue**: Queue에 메시지를 저장하고 수신 프로세스가 가져가는 방식.
- **Socket**: 프로세스 간 통신을 위한 Endpoint. IP Address와 Port를 이용해 네트워크 통신 가능.
- **IPC APIs**: shm_open(), mmap(), mq_open() 등의 인터페이스 제공.
