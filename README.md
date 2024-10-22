# HBOARD
## 1. hboard.exe 파일을 다운로드 받는다.
## 2. Microsoft Visual C++ 재배포 가능 패키지 버전을 설치한다. 

    https://learn.microsoft.com/ko-kr/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022

    ![](vc_redist.x64.png)

## 3. "C:\Program Files" 폴더에 hboard 폴더를 생성 후 다운로드 한 파일을 넣는다.
**  주의 : 반드시 "C:\Program Files" 이어야 한다.**

## 4. 인증서를 설치한다. 순서는 다음과 같다.
   - hboard.exe를 마우스 오른쪽 클릭, 팝업 메뉴의 '속성' 선택 후 '디지털서명' 탭으로 이동한다.
   - HBOARD.LOCAL을 선택 후 "자세히" 버튼을 클릭한다. 
   - "인증서 보기" 버튼을 클릭한다.
   - "인증서 설치" 버튼을 클릭한다.
   - 저장소 위치에서 "로컬 컴퓨터" 항목을 선택한다.
   - "다음" 버튼을 클릭한다.
   - "모든 인증서를 다음 장소에 저장" 항목을 선택한다.
   - "찾아보기" 버튼을 클릭 후 "신뢰할 수 있는 루트 인증기관"을 선택한다.
   - "다음" 버튼 클릭, "마침" 버튼을 클릭하여 설치를 완료한다.
  

** 주의: 3과 4의 단계의 과정은 매우 중요하며 Windows Application의 중요 요구사항이다.**

    https://learn.microsoft.com/ko-kr/windows/win32/WinAuto/uiauto-securityoverview#uiaccess-requirements-for-assistive-technology-applications

    ![](uiaccess.png)
