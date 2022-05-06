# (h1)안녕하세요! 반갑습니다!

## **(h3)목차**
  * 자기소개
    * 저는 이런 사람이에요
  * 어린이날 한 일
  * 오늘 일정


**자기소개**
  
저는 전북대학교 소프트웨어공학과 19학번 김규호입니다.

**어제 한 일**

어제는 백트래킹으로 스도쿠를 푸는 과정이랑 자바 스택을 구현하는 연습을 했어요.

 _스도쿠를 푸는 과정은 아직 미완성이어서 자바 스택만 보여드릴게요._

    package kyuho;

    public class StringStack implements Stack {

        private static final int capacity = 10;
        public int size;
        public String[] s1 = new String[capacity];
        protected String[] array = new String[capacity];

        public StringStack() {
        }

        public int length() {
            return capacity;
        }

        public Object pop() {

            String s1[] = array.clone();

            array[size - 1] = null;

            size--;

            return s1[size];


        }

        public boolean push(Object s) {
            array[size] = (String) s;
            size++;
            return (size <= capacity);
        }
    }

**오늘일정**

* 1시 공대 체전 축구 예선전
    * 12시 40분까지 대운동장에서 집결





  


