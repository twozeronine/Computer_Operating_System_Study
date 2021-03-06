# 운영체제의 개념

## 1. 운영체제의 정의

-   운영체제(OS, Operating System )는 컴퓨터 시스템의 자원들을 효율적으로 관리 하며, 사용자가 컴퓨터를 편리하고 효과적으로 사용할 수 있도록 환경을 제공하는 여러 프로그램의 모임으로 Windows 98, XP 등이 여기에 속한다.
-   컴퓨터 사용자와 컴퓨터 하드웨어 간의 인터페이스로서 동작하는 시스템 소프트웨어의 일종으로, 다른 응용 프로그램이 유용한 작업을 할 수 있도록 환경을 제공해 준다.

## 2. 운영체제의 목적

운영체제의 목적에는 처리 능력 향상, 사용 가능도 향상, 신뢰도 향상, 반환 시간 단축등이 있다. 처리 능력, 반환 시간, 사용 가능도, 신뢰도는 운영체제의 성능을 평가하는 기준이 된다.

-   처리 능력 ( Throughput ) : 일정 시간 내에 시스템이 처리하는 일의 양
-   반환 시간 ( Turn Around Time ) : 시스템에 작업을 의뢰한 시간부터 처리가 완료될 때까지 걸린 시간
-   사용 가능도 ( Availability ) : 시스템을 사용할 필요가 있을 때 즉시 사용 가능한 정도
-   신뢰도 ( Reliability ) : 시스템이 주어진 문제를 정확하게 해결하는 정도

## 3. 운영체제의 기능

-   프로세서 (처리기, Processor), 기억장치(주기억장치, 보조기억장치), 입출력장치, 파일 및 정보 등의 자원을 관리한다.
-   자원을 효율적으로 관리하기 위해 자원의 스케줄링 기능을 제공한다.
-   사용자와 시스템 간의 편리한 인터페이스를 제공한다.
-   시스템의 각종 하드웨어와 네트워크를 관리 제어 한다.
-   데이터를 관리하고, 데이터 및 자원의 공유 기능을 제공한다.
-   시스템의 오류를 검사하고 복구한다.
-   자원 보호 기능을 제공한다.
-   입출력에 대한 보조 기능을 제공한다.
-   가상 계산기 기능을 제공한다.

## 4. 운영체제의 주요 자원 관리

운영체제에서는 다음과 같은 자원의 관리 기능을 수행한다.

| 자 원         | 기 능                                                                                                         |
| ------------- | ------------------------------------------------------------------------------------------------------------- |
| 프로세스 관리 | - 프로세스 스케줄링 및 동기화 관리 담당 </br> - 프로세스 생성과 제거, 시작과 정지, 메시지 전달 등의 기능 담당 |
| 기억장치 관리 | 프로세스에게 메모리 할당 및 회수 관리 담당                                                                    |
| 주변장치 관리 | 입출력장치 스케줄링 및 전반적인 관리 담당                                                                     |
| 파일 관리     | 파일의 생성과 삭제, 변경, 유지 등의 관리 담당                                                                 |

## 5. 운영체제의 종류

-   운영체제의 종류에는 Windows98, WindowsXP, UNIX, LINUX, MS-DOS 등이 있다.
-   단일 작업 처리 시스템에는 DOS, 다중 작업 처리 시스템에는 Windows 98, Windows NT, UNIX, LINUX 등이 사용된다.
-   Windows 98, Windows XP는 개인용, Windows NT, UNIX, LINUX는 서버용 운영체제이다.

> 단일 작업 처리 시스템 ( Single Tasking System ) : 컴퓨터 시스템을 한 개의 작업이 독점하여 사용하는 방식으로, 예를 들어 DOS에서 워드 작업을 하다가 PC 통신을 하려면 워드 작업을 종료해야 하는 것을 의미한다.
> 다중 작업 처리 시스템 ( Multi-Tasking System ) : 여러 개의 프로그램을 열어 두고 다양한 작업을 동시에 진행하는 방식으로, 예를 들어 Windows에서 워드 작업을 하고 있는 상태에서 음악을 들으며 엑셀, 그림판 등의 프로그램을 실행시켜 놓고, 필요할 때마다 해당 프로그램으로 바로 바로 전환하여 사용할 수 있는 것을 의미합니다.
