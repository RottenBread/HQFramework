1.21.10에서 HQShop 쓰려니까 HQFrameworkCoroutineScope 오류 뜸 <br>
connection.sendPacket(packet); -> connection.send(packet); 으로 바껴서 생긴 오류 <br>
nms V21에서 가져오길래 하위 호환성때매 try 안에 넣어서 해결 <br>

인줄 알았는데 HQFrameworkBukkitMock 에서 오류 뜸 <br>
internal constructor() : super() 아랫줄 오류뜨길래 그냥 지워버림

정식 수정법도 아니고 완전 야매지만 그냥 당장에 돌아가니 만족,,
