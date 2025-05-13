202111302 백진률 Computer Graphics Assignment 6

구현 세부 사항  
1.1 Assignment.cpp 구현한 클래스 및 코드들은 Assignment.cpp 안에 존재하고, 구현되었습니다.  
삼각형 메쉬로 구성된 구체(sphere)를 모델링 및 렌더링합니다.  
각 정점에서 조명을 계산한 뒤, 내부 픽셀은 정점 색상을 보간하여 표현하는 Gouraud shading을 구현하였습니다.

![image](https://github.com/user-attachments/assets/607b916e-840e-4a2f-8a06-e9ea84f25a2b)


컴파일 및 실행 방법  
3.1 필요 라이브러리  
본 프로젝트는 다음 라이브러리를 필요로 합니다:  
• GLFW: 창 관리  
• GLEW: OpenGL 확장 기능 처리  
• GLM: 벡터 및 행렬 연산  
• OpenGL / GLUT: 최종 이미지 렌더링

3.2 컴파일 및 실행 방법

Visual Studio에서 프로젝트 솔루션 파일을 엽니다.  
필요한 라이브러리(GLFW, GLEW, OpenGL, GLUT)가 포함되어 있는지 확인합니다.  
프로젝트를 빌드하고 실행합니다.
