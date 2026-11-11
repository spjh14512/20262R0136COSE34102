# OS Structure

- **OS Design Goals**: Fairness, Performance, Scalability, Reliability, Security 등. 목표 사이에 Trade-off 존재.
- **Policy**: 무엇을 할 것인지 결정.
- **Mechanism**: 결정한 정책을 어떻게 구현할지 결정.
- **Layering**: 계층별 인터페이스를 정의하여 복잡성 감소.
- **Modularity**: 기능을 독립적인 모듈로 분리하여 유지보수성과 확장성 향상.
- **User Mode**: Privileged Instruction 실행 및 보호 자원 접근 제한.
- **Kernel Mode**: 커널이 높은 권한으로 시스템 자원을 관리.
- **System Call**: 사용자 프로그램이 커널 서비스를 요청하는 인터페이스. 번호에 따라 Handler를 선택하여 실행.
- **POSIX**: 운영체제 간 호환성을 위한 표준 인터페이스.
