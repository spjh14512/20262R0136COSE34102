# Virtual Memory (1)

- **Virtual Memory**: 각 프로세스에 독립적인 주소 공간을 제공하는 메모리 추상화. 투명성, 효율성, 보호 기능 제공.
- **Virtual Address / Physical Address**: 프로그램이 사용하는 주소와 실제 RAM의 주소.
- **MMU**: Virtual Address를 Physical Address로 변환하는 하드웨어.
- **Contiguous Allocation**: 프로세스의 주소 공간을 연속된 물리 메모리에 배치. Base Register로 주소 변환.
- **Fragmentation**: 메모리 할당 과정에서 발생하는 낭비. External / Internal Fragmentation.
- **Segmentation**: Code, Heap, Stack 등의 논리적 Segment 단위로 메모리 할당.
- **Paging**: 가상 메모리를 Page, 물리 메모리를 Frame으로 분할하여 할당.
- **Address Translation**: Virtual Page Number(VPN)를 Physical Frame Number(PFN)로 변환하고 Offset 유지.
- **Page Table**: VPN과 PFN의 매핑 저장. PTE에는 PFN과 상태 플래그 포함.
- **TLB**: 최근 주소 변환 결과를 캐싱하여 메모리 접근 속도 향상.
- **Multi-level Page Table**: 계층적 구조로 Page Table의 메모리 낭비 감소.
- **Inverted Page Table**: 물리 Frame을 기준으로 매핑 정보를 관리.
