# spin2tetris
spin to tetris
- 컴퓨터 

- 백준 11005 : https://www.acmicpc.net/problem/11005

- 네카라쿠배를 가고싶다?
  - 코드스쿼드, 알고리즘, Http를 공부해라
  - 알고리즘 공부하기싫다? 대기업 못감, 10~20% 밖에 못가는거야
  
- 책 추천
  - 웹 개발자를 위한 웹을 지탱하는 기술 , 야마모토 요헤이 저
    - http://www.yes24.com/Product/Goods/5170353?OzSrank=1
    - 어렵다그랬나?
  <br>
  <br>
  - HTTP 완벽 가이드
    - 수천페이지에 난이도가 높지만 한번쯤은 읽어야할 책
    - http://www.yes24.com/Product/Goods/15381085
  <br>
  <br>
  - 명쾌한 설명과 풍부한 그림으로 배우는 TCP/IP  쉽게 더 쉽게, 리브로웍스 저
    - 그나마 쉬운 책
    - http://www.yes24.com/Product/Goods/32203210
  <br>
  <br>
  - 만화로 쉽게 배우는 CPU, Michio Shibuya 저
    - http://www.yes24.com/Product/Goods/17430978
- 강의
  - 영한님 강의
    - https://www.inflearn.com/course/http-%EC%9B%B9-%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC
  - 책 링크
    
        
# CPU 만들기

## ALU 구현
  1. 기본게이트 AND, OR, NOT 구현
  2. XOR 게이트 구현
  3. ADDR 구현(Half ADDR, Full ADDR) : 덧셈구현
  4. 음수표현 (1의보수, 2의보수)
  5. 뺄셈 표현 ( 덧셈+2의보수)
  6. 곱셈 만들기 : 덧셈 여러번
  7. 이외 사측연산 : 나누기, 
  8. 비트 쉬프터
  9. ALU 성공 : and,or,not,xor,사측연산

## CPU 구성은
  - CPU = ALU + Control Unit(제어장치) + 레지스터(내장의 고속 메모리)
  - 주로 PC(Program Counter)
  - 




```java
class Adder {
    public boolean[] halfadder(boolean bitA, boolean bitB) {
        boolean[] answer = {};
        //boolean[0] : carry
        //boolean[1] : sum
        return answer;
    }


    public boolean[] fulladder(boolean bitA, boolean bitB, boolean carry) {
        boolean[] answer = {};
        //boolean[0] : carry
        //boolean[1] : sum
        return answer;
    }
}
```
# 메모리 영억 4가지 구분
  - 코드
  - 스텍
  - 데이터
  - 힙

# 메모리 계층구조
  - 레지스터 : CPU 내부에 위치, 반도체
  - 캐시메모리 : SR래치 : CPU 내부에 위치함
  - 메인메모리 (주 기억장치) : Dram(캐패시터), SRAM(SR래치)
  - 디스크, 낸드 (보조 기억장치) : Nand Flash, Nor Flash, Hard Disk, Soft disk(플로피)


# 프로그램이 실행되기까지
  
  ## cpu가 불러와서 실행하는 과정
  - 기계여 하나하나를 인스트럭션 실행을 패치,
  - 코드를 컴파일한 결과물(바이너리)가 메모리에 복사되서 올라감,(원래는 디스크, 보조기억장치에 있음)
  
  ## 로드 스토어, 연산
  - r1,r2,에 가져와서 저장
  - 어셈블리 언어 설명
  - CPU에다가 실제로 처리하는 과정!

  # 폰노이만
  - 폰노이만 : 같이 씀
  - 하바드 : 

  - 게임으로 해볼 수 있음
    - http://www.zachtronics.com/shenzhen-io/
    - http://www.zachtronics.com/

# 학습정리
- ADDR만들기 : 릴레이에서 시작해서 (논리게이트) ADDR를 만듬
- ALU가 자라서 CPU
- CPU , GPU, AP, 메모리도 붙이고 하면 컴퓨터
- 버스를 타고 연결됨
- 실행중인 프로그램 : 프로세스, 메모리에 위치한뇨석
- 학습은 두 축인데, CPU를  