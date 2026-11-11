# Process

- **Process**: 실행 중인 프로그램. OS가 CPU와 메모리 등의 자원을 관리하는 단위.
- **Address Space**: Text, Data, Heap, Stack 등으로 구성. 프로세스 간 메모리 접근은 보호됨.
- **Program Execution**: Source Code → Compiler → Object File → Linker → Executable → Loader → Process.
- **PCB**: PID, Process State, Program Counter, Register 등 프로세스 관리 정보 저장. Linux에서는 task_struct 사용.
- **Process States**: New, Ready, Running, Waiting, Terminated.
- **Context Switch**: 기존 프로세스의 문맥을 저장하고 다음 프로세스의 문맥을 복원.
- **fork()**: 부모 프로세스를 복제하여 자식 프로세스 생성.
- **exec()**: 현재 프로세스의 프로그램을 새로운 프로그램으로 교체.
- **wait()**: 자식 프로세스의 종료를 기다림.
