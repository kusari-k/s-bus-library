s-bus基板
Arduino側3ピン-->通信モジュール
4066側3ピン-->A2XI2
HC04側ピン-->ラズパイ付属シリアルTX
外側2ピン(どちらか1ピンのみ使用)-->ラズパイ26ピン
GNDピン-->電源基板GNDピン
Arduino側3.3Vピン-->電源基板3.3Vピン

teensy基板
3.3Vピン-->電源基盤3.3Vピン
GNDピン-->CAN2ピン
3ピン-->CAN1ピン
4ピン-->CAN4ピン
8ピン-->ラズパイ20ピン
9ピン-->ラズパイ21ピン
10ピン-->ラズパイ16ピン


CANレシーバー基盤
3ピン-->ドローンGPS
CAN1ピン-->teensy3ピン
CAN2ピン-->teencyGNDピン
CAN3ピン-->電源基板5Vピン
CAN4ピン-->teensy4ピン
GNDピン-->電源基板GNDピン

ラズパイ

16ピン-->teensy10ピン
19ピン-->外側2ピン(どちらか1ピンのみ使用)
20ピン-->teensy8ピン
21ピン-->teensy9ピン
26ピン-->sbus基盤外側2ピン(どちらか1ピンのみ使用)


電源基板
GNDピン-->sbus基板GNDピン,ラズパイGNDピン,ドローンGND,CANレシーバー基板GNDピン
3.3Vピン-->Arduino側3.3Vピン,teensy基板3.3Vピン
5Vピン-->ラズパイ5Vピン,ドローン5V,CAN3ピン
外側2ピン(どちらか1ピンのみ使用)-->ラズパイ19ピン

