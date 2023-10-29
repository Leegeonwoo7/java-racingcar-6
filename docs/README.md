##우테코 프리코스 2주차 racingcar

###1. Controller - 사용자로부터 요청을 입력받아 처리할 목록
   StartRace: 사용자의 요청에 의해 레이스 게임 시작. [void]
   TurnCount: 사용자에 의해 입력될 주어질 횟수. [int]
   NewCar: 사용자에 의해 입력되어 생성할 자동차 수, 자동차 이름 [String]

###2. View - 사용자에게 표시될 정보
   InputPlayerMessage: "경주할 자동차 이름을 입력하세요. (이름은 쉼표(,) 기준으로 구분)
   InputTurnCountMessage: 시도할 회수는 몇회인가요?
   RaceResult: "실행 결과"
               User1 : --
               User2 : -----
               User3 : -
   ShowWinner: "최종 우승자: user,user"

###3. Model - 핵심 기능과 데이터
   ValidateNameLenth: CarName의 길이 검사
   AdvanceCar: 자동차 이동
   PickRandomNumber: 랜덤 수가 0~3이면 Advance하지않고, 4~9이면 Advance
   AdvanceCount: 최종 우승자를 알아내기 위한 자동차가 이동한 횟수만큼 Count한 변수
   
