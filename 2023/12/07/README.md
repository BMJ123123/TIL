# 📅 2023/12/07

* 코리아IT류빈쌤 수요일 과제

문제 코드

    public class Assignment1
    {
        public static void main(String[] args) {
            // 1. Hello Java를 출력하는 코드를 작성하세요.
        
        
            // 2. 식별자 이름 규칙 5개를 각각 만족하는 변수를 int형으로 5개 작성하세요.
        
        
            // 3. 파이 (3.14) 값을 저장하는 상수 변수를 작성하세요.
        
        
            // 4. false 값을 저장하는 변수를 작성하세요.
        
        
            // 5. 200000 을 저장하는 변수를 두 개의 다른 자료형을 이용해 작성하세요.
        
        
            // 6. 10.24 를 저장한은 실수 변수를 두 개의 다른 자료형을 이용해 작성하세요.
        
        
            // 7. 출력 했을 때 40이 나오도록 16진수 리터럴 정수 변수를 작성하세요.
        
        
        }
    }

풀이 코드

    public class Naming {
        public static void main(String[] args) {
            // 1. Hello Java를 출력하는 코드를 작성하세요.
            System.out.println("Hello Java");
        
            // 2. 식별자 이름 규칙 5개를 각각 만족하는 변수를 int형으로 5개 작성하세요.
            int A = 1;
            int a = 1;
            int a7 = 1;
            int a_ = 1;
            int a$ = 1;
            
            // 3. 파이 (3.14) 값을 저장하는 상수 변수를 작성하세요.
        float PI = 3.14f;
        
            // 4. false 값을 저장하는 변수를 작성하세요.
            boolean T_F = false;
            System.out.println(T_F);
        
            // 5. 200000 을 저장하는 변수를 두 개의 다른 자료형을 이용해 작성하세요.
            int a1 = 200000;
            long a2 = 200000L;
            System.out.println(a1);
            System.out.println(a2);

            // 6. 10.24 를 저장한은 실수 변수를 두 개의 다른 자료형을 이용해 작성하세요.
            float a3 = 10.24f;
            double a4 = 10.24d;
            System.out.println(a3);
            System.out.println(a4);

            // 7. 출력 했을 때 40이 나오도록 16진수 리터럴 정수 변수를 작성하세요.
            int a5 = 0x28;
            System.out.println(a5);

        }
    }

* * *

자바의 자료형 구조를 복습하는 시간을 가졌다.

논리 타입, 정수타입을 포함한 여러 기본 타입의 사용방법에 대해서 복습했다.

파이썬, C++ 에서도 마찬가지일 수도 모르겠으나, 그때 배울 때는 이렇게 디테일한 내용은 모르고 있었다.

16진수는 0x를 붙인다거나, float은 숫자 뒤에 f를 붙이는 것 과 같이 기본적인 내용을 배웠다.