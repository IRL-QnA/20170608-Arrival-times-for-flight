<!-- 이 레포지토리는 과거에 받은 질문내용을 정리하여 재 구성한 것입니다. -->

# <2. 공항 도착시간> a program calculates arrival times for flight

졸업후 입사하게 된 항공사.
이 회사는 전산시스템이 아직 도입되지 않아서 모든 비행 도착 일정을 사람이 직접 계산해서 고객들에게 도착 예정 시간표를 제공해야 한다.
항공사에서 운행하는 비행 일정은 하루에서 수십에서 수백건이고, 이 단순 업무로 인해서 매일같이 야근을 하고 있다.
이를 전산화하면 매일같이 반복되는 야근이 없어질 거 같다.

## <요구사항>
- 공항 출발 일정이 저장된 텍스트 형식의 읩력 파일이 제공된다.
- 입력파일에서 "출발지 -> 도착지 : 비행시간" 정보를 읽어서 출력파일의 첫번째 줄에 출력
- 입력파일에서 가져온 비행 출발시간과 비행시간을 계산해서 출력파일에 출력
- 아래에 명시된 입력파일과 출력파일의 format를 준수해야 한다.

## <입력파일>
- 입력 파일의 이름은 input.txt
- 입력 파일의 첫번째 줄에는 "출발지 -> 도착지 / 비행시간" 정보가 있다.
- 시간과 분은 콜론(:)으로 구분
- 시간의 범위는 00 ~ 23, 분의 범위는 00 ~ 59
- 항상 시간 2 자리, 분 2 자리로 입력
- 출발시간 정보에는 공백이 포함되지 않는다.
- 예제 파일 : https://drive.google.com/open?id=0BydeQGarm0qRWGFCUXBSX3JFNGM

## <출력파일>
- 출력 파일의 이름은 output.txt
- 첫번째 줄에는 "출발지 -> 도착지 / 비행시간" 정보가 있다.
- 시간과 분은 콜론(:)으로 구분
- 시간의 범위는 00 ~ 23, 분의 범위는 00 ~ 59
- 항상 시간 2 자리, 분 2 자리로 입력
- 도착시간 정보에는 공백이 포함되지 않는다.
- 예제 파일 : https://drive.google.com/open?id=0BydeQGarm0qRSGdnTk9ybl80Z3M
