## 3.5: 연습

1. 시스템 타이머 대신 로컬 타이머를 사용하여 프로세서 인터럽트를 생성하십시오. 자세한 내용은 [이 문제](https://github.com/s-matyukevich/raspberry-pi-os/issues/70) 를 참조하십시오.
1. MiniUART 인터럽트를 처리하십시오. `kernel_main` 함수의 마지막 루프를 아무것도하지 않는 루프로 교체하십시오. 사용자가 새 문자를 입력하자마자 인터럽트를 생성하도록 MiniUART 장치를 설정하십시오. 새로 도착한 각 문자를 화면에 인쇄하는 인터럽트 처리기를 구현하십시오.
1. qemu에서 실행되도록 Lesson 03을 적용하십시오. [이 문제](https://github.com/s-matyukevich/raspberry-pi-os/issues/8) 를 참조하십시오.

##### 다음 페이지

3.4 [Interrupt handling: Timers](../../docs/lesson03/linux/timer.md)

##### 이전 페이지

4.1 [Process scheduler: RPi OS Scheduler](../lesson03/rpi-os.md)

##### 추가 사항

이 문서는 훌륭한 오픈소스 운영체제 학습 프로젝트인 Sergey Matyukevich의 문서를 영어에 능숙하지 않은 한국인들이 학습할 수 있도록 번역한 것입니다. 오타 및 오역이 있을 수 있습니다. Sergey Matyukevich는 한국어를 능숙하게 다루지 못합니다. 대신 저에게 elxm6123@gmail.com으로 연락해주세요.
