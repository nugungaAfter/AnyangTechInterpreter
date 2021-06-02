# 인터프리터 readme 파일. 

이 프로젝트는 만들면서 배우는 인터프리터를 참고하여 제작되었습니다.




기본 지원 기능

*변수 - 전역 변수, 배열(1차) 가능

*조건문(if-else), 반복문(for, while) 가능

*함수 사용 가능

*좁은 연산자 사용 가능

*do ~ end 구조임




* 아직 추가 기능을 만들지 못했고

# 언어 컴파일 사양

Compiler : GNU Compiler C 9.3.0

Compile OS : Ubuntu 20.04.1 LTS



*Test

Windows 10

Ubuntu 20.04.1 LTS



# 사용법

 1. cmd (유저모드)
 2. 프로그램이 있는 위치까지 이동 (exsample cd c:\\~\Download)
 3. 소스 파일 실행 (exsample 폴더 안에 예제 있습니다, .\qi.exe target.source)
 4. 결과 확인

# 문제 발생하는 경우
 1. 글자가 깨집니다.

    글자가 깨질경우 cmd가 기본으로 cp-949나 한글 인코딩(enc-kor)을 사용하고 있을 텐데
    chcp를 통해 유니코드로 변경합니다.
    
    chcp 65001  # 유니코드로 현재 인코딩을 변경
 
 2. end가 없다고 뜨는 경우 (리눅스에 경우)

    리눅스에서는 파일에서 줄을 인식할 때 약간의 차이가 존재하는 데
    소스코드에 엔터 한줄을 치면됩니다.
