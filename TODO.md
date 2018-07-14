### Info
PTS-Files are PNG files with the first 4byte beeing lengt of the data.

### TODO 
- input muisc/-folder, generate music_data.bin
- speed up / speed down key patch
- song selection delay
- initialize song selection page
- red box disappearing after song selection
- store pw as bcrypt
- remove data? encrypt data? / data updates?
- Adjust header for eading big packets (255 byes) from client! / incoming packets not fixed yet
- Document packet Ids:

[Packet ID]

  0 = 로그인(Login)?
-
  1 = 로그인(Login)?
-
  2 = 닉네임 생성(CreateAccount)
-
  3 = 채널 바꾸기(ChangeChannel)
-
  4 = 게임종료(ExitGame)
-
  5 = 방 만들기(Create a room)
-
  6 = 초대 수락 방 이동(Move invitation accept room)
-
  7 = 채널 서버 선택(SelectChannelServer)
-
  8 = 뒤로가기 버튼(BackButton)
-
  9 = Login Server 모드 선택(SelectMode)
-
  0A = Login Server 채널 선택 버튼(SelectChannelButton) 
-
  0B = x님이 입장 하셧습니다.
-
  0C = x님이 퇴장했습니다.
-
  0D = Play Room List
-
  0E =
-
  0F = 방장 넘겨주기(master Permissions)
-
  10 = ?
-
  11 = 멀티플레이 방 옵션 적용(Apply multiplayer options)
-
  12 = 일반 채팅,게임오버(GameOver)
-
  13 =
-
  14 = 귓속말
-
  15 = GM공지사항(GM NOTICE)
-
  16 = 강제퇴장(Forced out) []님이 강퇴하였습니다.
-
  17 = 아이템 버리기,곡 로딩 정보(Song loading information)
-
  18 =
-
  19 =
-
  1A =
-
  1B = 상대방 정보보기,결과창(Result)
-
  1C = 결과창 끝나고 대기실로 이동(ResultBack)
-
  1D = 아이템 구입(Purchase Item)
-
  1E = 아이템 적용(Apply Item)
-
  1F = (SendTCPXTrapData) XTrap data server packet
-
  20 =
-
  21 =
-
  23 =
-
  24 = 내가방 창 열기(Open my bag)
-
  25 = ?
-
  26 = 친구 추가
-
  27 = 게임 로딩 시작(Start loading games)
-
  28 = 다른사람이 0번 방으로 초대 메세지(Invite message)
-
  29 = 초대하기(Invite)
-
  2A =
-
  2B = 곡 디스크 포인트(Music DJpoint)
-
  2C = 디스크 1포인트 지급
-
  2D = 옵션적용(Send Apply options)
-
  2E =
-
  2F =