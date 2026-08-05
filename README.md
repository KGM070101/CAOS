# CAOS

## 목차

- [메모리 구조와 저장방식 정리](CAOS.md)
    - [프로그램 메모리 구조](CAOS.md#프로그램-메모리-구조)
    - [저장 방식](CAOS.md#저장-방식-automatic-static-dynamic)
    - [Static 동작 방식](CAOS.md#static-변수의-동작-방식)
    - [IL/JIT](CAOS.md#il과-jit)

---

# 키워드 정리

## 목차

### 소프트웨어 공학 / 객체지향
- [해시코드](./키워드%20정리.md#해시코드)
- [소프트웨어 정의](./키워드%20정리.md#소프트웨어-정의)
- [소프트웨어 특성](./키워드%20정리.md#소프트웨어-특성)
- [소프트웨어 위기](./키워드%20정리.md#소프트웨어-위기)
- [SDLC](./키워드%20정리.md#sdlc)
- [다형성](./키워드%20정리.md#다형성)
- [가상화](./키워드%20정리.md#가상화)
- [추상화](./키워드%20정리.md#추상화)
- [CBD(Component Based Development)](./키워드%20정리.md#cbdcomponent-based-development)
- [결합도](./키워드%20정리.md#결합도)
- [코드 스멜](./키워드%20정리.md#코드-스멜)
- [리팩토링](./키워드%20정리.md#리팩토링)
- [Validation](./키워드%20정리.md#validation)
- [Verification](./키워드%20정리.md#verification)
- [추상클래스](./키워드%20정리.md#추상클래스)
- [인터페이스](./키워드%20정리.md#인터페이스)

### UML / 설계 문서
- [UML](./키워드%20정리.md#umlunified-modeling-language)
- [유즈케이스 다이어그램](./키워드%20정리.md#유즈케이스-다이어그램)
- [클래스 다이어그램](./키워드%20정리.md#클래스-다이어그램)
- [시퀀스 다이어그램](./키워드%20정리.md#시퀀스-다이어그램)

### 라이브러리 / 실행 파일 구조
- [.lib](./키워드%20정리.md#lib)
- [DLL](./키워드%20정리.md#dll)
- [컴파일러](./키워드%20정리.md#컴파일러)
- [인터프리터](./키워드%20정리.md#인터프리터)
- [컴파일러 vs 인터프리터](./키워드%20정리.md#컴파일러-vs-인터프리터)

### CPU 구조 / 레지스터 / 버스
- [PC(Program Counter)](./키워드%20정리.md#pcprogram-counter)
- [IR(Instruction Register)](./키워드%20정리.md#irinstruction-register)
- [AC(Accumulator)](./키워드%20정리.md#acaccumulator)
- [MAR(Memory Address Register)](./키워드%20정리.md#marmemory-address-register)
- [MBR(Memory Buffer Register)](./키워드%20정리.md#mbrmemory-buffer-register)
- [ALU](./키워드%20정리.md#alu)
- [Decoder](./키워드%20정리.md#decoder)
- [Shifter](./키워드%20정리.md#shifter)
- [Address Bus](./키워드%20정리.md#address-bus)
- [Data Bus](./키워드%20정리.md#data-bus)
- [Control Bus](./키워드%20정리.md#control-bus)
- [CPU register](./키워드%20정리.md#cpu-register)
- [CPU Register - PC(Program Counter)](./키워드%20정리.md#cpu-register---pcprogram-counter)
- [CPU Register - IR](./키워드%20정리.md#cpu-register---ir)
- [CPU Register - MAR](./키워드%20정리.md#cpu-register---mar)
- [CPU Register - MBR](./키워드%20정리.md#cpu-register---mbr)
- [CPU Register - GPR](./키워드%20정리.md#cpu-register---gpr)
- [CPU Register - AC](./키워드%20정리.md#cpu-register---ac)
- [CPU Register(Flag Register)](./키워드%20정리.md#cpu-registerflag-register)
- [CPU Register - SP(Stack Pointer)](./키워드%20정리.md#cpu-register---spstack-pointer)
- [CPU - 제어장치](./키워드%20정리.md#cpu---제어장치)
- [CPU - 연산장치](./키워드%20정리.md#cpu---연산장치)
- [CPU 연산장치 - 가산기](./키워드%20정리.md#cpu-연산장치---가산기)
- [CPU 연산장치 - 누산기](./키워드%20정리.md#cpu-연산장치---누산기)
- [CPU 연산장치 - 보수기](./키워드%20정리.md#cpu-연산장치---보수기)
- [CPU 시스템 버스](./키워드%20정리.md#cpu-시스템-버스)

### 명령어 처리 과정
- [명령어 사이클](./키워드%20정리.md#명령어-사이클)
- [인출 사이클](./키워드%20정리.md#인출-사이클)
- [간접 사이클](./키워드%20정리.md#간접-사이클)
- [실행 사이클](./키워드%20정리.md#실행-사이클)
- [인터럽트 사이클](./키워드%20정리.md#인터럽트-사이클)

### 메모리 / 캐시 / 가상메모리
- [캐시 메모리](./키워드%20정리.md#캐시-메모리)
- [캐시 메모리 지역성](./키워드%20정리.md#캐시-메모리-지역성)
- [캐시메모리 일관성](./키워드%20정리.md#캐시메모리-일관성)
- [캐시메모리 매핑](./키워드%20정리.md#캐시메모리-매핑)
- [가상메모리](./키워드%20정리.md#가상메모리)
- [가상메모리 관리정책](./키워드%20정리.md#가상메모리-관리정책)
- [가상메모리 페이징](./키워드%20정리.md#가상메모리-페이징)
- [가상메모리 세그먼테이션](./키워드%20정리.md#가상메모리-세그먼테이션)
- [가상메모리 페이지드 세그멘테이션](./키워드%20정리.md#가상메모리-페이지드-세그멘테이션)
- [Thrashing](./키워드%20정리.md#thrashing)
- [메모리 인터리빙](./키워드%20정리.md#메모리-인터리빙)
- [메모리 단편화](./키워드%20정리.md#메모리-단편화)
- [메모리 단편화 - 내부](./키워드%20정리.md#메모리-단편화---내부)
- [메모리 단편화 - 외부](./키워드%20정리.md#메모리-단편화---외부)
- [메모리 단편화 - 압축](./키워드%20정리.md#메모리-단편화---압축)
- [메모리 단편화 - 메모리 풀](./키워드%20정리.md#메모리-단편화---메모리-풀)
- [가비지 컬렉션](./키워드%20정리.md#가비지-컬렉션)

### GPU / 병렬 처리
- [CPU와 GPU의 차이](./키워드%20정리.md#cpu와-gpu의-차이)
- [GPU](./키워드%20정리.md#gpu)
- [GPGPU](./키워드%20정리.md#gpgpu)
- [CPU vs GPU](./키워드%20정리.md#cpu-vs-gpu)
- [CUDA](./키워드%20정리.md#cuda)
- [RAM vs VRAM](./키워드%20정리.md#ram-vs-vram)
- [Compute Shader](./키워드%20정리.md#compute-shader)

### 프로세스 / 스레드 / 운영체제
- [프로세스](./키워드%20정리.md#프로세스)
- [프로세스 메모리 영역](./키워드%20정리.md#프로세스-메모리-영역)
- [코드 영역](./키워드%20정리.md#코드-영역)
- [데이터 영역](./키워드%20정리.md#데이터-영역)
- [힙 영역](./키워드%20정리.md#힙-영역)
- [스택 영역](./키워드%20정리.md#스택-영역)
- [Thread](./키워드%20정리.md#thread)
- [Process](./키워드%20정리.md#process)
- [Process vs Thread](./키워드%20정리.md#process-vs-thread)
- [PCB(Process Control Block)](./키워드%20정리.md#pcbprocess-control-block)
- [TCB(Thread Control Block)](./키워드%20정리.md#tcbthread-control-block)
- [PCB - Process id](./키워드%20정리.md#pcb---process-id)
- [TCB - Thread Id](./키워드%20정리.md#tcb---thread-id)
- [PCB - Process Status](./키워드%20정리.md#pcb---process-status)
- [TCB - Thread Status](./키워드%20정리.md#tcb---thread-status)
- [PCB - PC](./키워드%20정리.md#pcb---pc)
- [TCB - PC](./키워드%20정리.md#tcb---pc)

### 파일 포맷
- [파일 포맷](./키워드%20정리.md#파일-포맷)
- [Jpg](./키워드%20정리.md#jpg)
- [Bmp](./키워드%20정리.md#bmp)
- [Tga](./키워드%20정리.md#tga)
- [PNG](./키워드%20정리.md#png)
- [Wav](./키워드%20정리.md#wav)
- [Avi](./키워드%20정리.md#avi)
    