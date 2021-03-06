# 파이썬의 특징

## 1.파이썬은 인간다운 언어이다.
>파이썬은 사람이 생각하는 방식을 그대로 표현할수 있는 언어이다.
>따라서 프로그래머는 굳이 컴퓨터의 사고 체계에 맞추어서 프로그래밍을 하려고 애쓸필요가 없다.

>예제
>if 4 in [1,2,3,4]: print("4가 있습니다.")
>위의 예제는 <만약 4가 1,2,3,4 중에 있으면 "4가 있습니다"를 출력한다>는 뜻이다.

## 2.파이썬은 문법이 쉬워 빠르게 배울수 있다.
>파이썬은 문법자체가 아주 쉽고 간결하며 사람의 사고 체계와 매우 닮아 있다.
>유명한 프로그래머 에릭 레이먼드는 파이썬을 공부한지 단 하루만에 자신이 원하는 프로그램을 작성할수 있었다고 한다.

## 3.파이썬은 무료이지만 강력하다.
>오픈 소스인 파이썬은 당연히 무료이다. 사용료 걱정없이 언제 어디서든 파이썬을 다운로드하여 사용할수 있다.
>또한 프로그래머는 만들고자 하는 프로그램의 대부분을 파이썬으로 만들수 있다. 물론 시스템프로그래밍이나 하드웨어 제어와 같은 매우 복잡하고 반복 연산이 많은 프로그램은 파이썬과 어울리지 않는다. 하지만 파이썬은 이러한 약점을 극복할수 있게끔 다른 언어로 만든 프로그램을 파이썬 프로그램에 포함 시킬수 있다.

## 4.파이썬은 간결하다.
>귀도는 파이썬을 의도적으로 간결하게 만들었다.만약 펄과 같은 프로그래밍 언어가 100가지 방법으로 하나의 일을 처리할수 있다면 파이썬은 가장 좋은 방법 1가지만 사용하는 것을 선호한다. 이 간결함의 철학은 파이썬 문법에도 그대로 적용되어 파이썬 프로그래밍을 하는 사람들은 잘 정리되어 있는 소스코드를 볼 수 있다. 다른 사람이 작업한 소스 코드도 한눈에 들어와 이해하기 쉽기 때문에 공동 작업과 유지 보수가 아주 쉽고 편하다.

>#simple.py
languages = ['python', 'perl', 'c', 'java']
>
>for lang in languages:
    if lang in ['python', 'perl']:
        print("%6s need interpreter" % lang)
    elif lang in ['c', 'java']:
        print("%6s need compiler" % lang)
    else:
        print("should not reach here")
> 위 옞제는 프로그래밍 언어를 판별하여 그에 맞는 문장을 출력하는  파이썬 프로그램예제이다. 다른 언어에서 늘 보게 되는 단락을 구분하는 괄호({}) 문자가 보이지 않는 것을 확인할수 있다. 또한 줄을 참 잘맞춘 코드라느 것도 알수 있다. 파이썬 프로그램은 줄을 맞추지 않으면 실행되지 않는다. 코드를 예쁘게 작성하려고 줄을 맞추는 것이 아니라 프로그램이 실행되게 하려면 꼭 줄을 맞추어야 하는 것이다. 이렇듯 줄을 맞이 아니라 프로그램이 실행되게 하려면 꼭 줄을 맞추어야 하는 것이다. 이렇듯 줄을 맞추어 코드를 작성하는 행위는 가독성에 크게 도움이 된다.

## 5.파이썬은 프로그래밍을 즐기게 해준다
>파이썬 만큼 프로그래밍을 즐기게 해 준 언어는 없었다. 파이썬은 다른것에 신경 쓸 필요가 없이 내가 하고자 하는 부분에만 집중할수 있게 해준다. 파이썬을 배우고 나면 다른 언어로 프로그래밍하는 것에 지루함을 느끼게 될지도 모른다.

## 6.파이썬은 개발 속도가 빠르다.
>파이썬의 엄청나게 빠른 개발 속도를 두고 유행처럼 퍼진 말이다.