## 1.5: 연습

연습하기는 선택사항이지만 소스코드를 조금 실험해 볼 것을 강력히 권합니다. 연습 중 하나를 완료할 수 있는 경우 소스 코드를 다른 사람과 공유하십시오.

1.  상수 `baud_rate`를 도입하여 이 상수를 사용하여 필요한 Mini UART 레지스터 값을 계산하십시오. 프로그램이 115200 이외의 보레이트를 사용하여 작동할 수 있는지 확인하십시오.
2.  Mini UART 대신 UART 장치를 사용하도록 OS 코드를 변경하십시오. UART 레지스터에 액세스하는 방법과 GPIO 핀을 구성하는 방법을 알아보려면 `BCM2837 ARM Peripherals` 메뉴얼을 사용하십시오.
3.  프로세서 코어 4개를 모두 사용해 보십시오. OS는 모든 코어에 대해 프로세서 <프로세서 인덱스>에서 Hello를 출력해야 합니다. 코어별로 별도의 스택을 설정하고 Mini UART가 한 번만 초기화되었는지 확인하십시오. 동기화에 글로벌 변수와 `delay` 함수의 조합을 사용할 수 있습니다.
4.  qemu에서 실행되도록 레슨 01을 적용하십시오. [이 이슈](https://github.com/s-matyukevich/raspberry-pi-os/issues/8)를 참고해보세요.

##### 이전 페이지

1.4  [Kernel Initialization: Linux startup sequence](./kernel-startup.md)

##### 다음 페이지

2.1  [Processor initialization: RPi OS](../lesson02/rpi-os.md)

##### 추가 사항

이 문서는 훌륭한 오픈소스 운영체제 학습 프로젝트인 Sergey Matyukevich의 문서를 영어에 능숙하지 않은 한국인들이 학습할 수 있도록 번역한 것입니다. 오타 및 오역이 있을 수 있습니다. Sergey Matyukevich는 한국어를 능숙하게 다루지 못합니다. 대신 저에게 elxm6123@gmail.com으로 연락해주세요.
