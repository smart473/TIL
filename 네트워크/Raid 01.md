# Raid system

## 1.JBOD

![download](https://dthumb-phinf.pstatic.net/?src=%22http%3A%2F%2Fwww.seagate.com%2Ffiles%2Fwww-content%2Fmanuals%2Fbusiness-storage-nas-os-manual%2F_shared%2Fimages%2F116a_ill_jbod.png%22&type=w2)

* 데이터 저장 방식: JBOD로 구성된 디스크는 데이터를 순차적으로 저장합니다.
ex) 디스크 1이 꽉차면 디스크 2, 디스코 3 순으로 데이터를 저장합니다.

* 장점: 총 스토리지 용량을 100% 사용할 수 있고 확장이 쉽다

* 단점: 디스크가 1개 라도 고장나면 모든 데이터가 손실됩니다. 

## 2.RAID 0

![download](https://dthumb-phinf.pstatic.net/?src=%22http%3A%2F%2Fwww.seagate.com%2Ffiles%2Fwww-content%2Fmanuals%2Fbusiness-storage-nas-os-manual%2F_shared%2Fimages%2F116b_ill_raid_0.png%22&type=w2)

* 장점: I/O 성능 개선(영상편집할때 주로 사용)

* I/O: I/O는 입력/출력 의 약자로, 컴퓨터 및 주변창치에 대히여 데이터를 전송하는 프로그램, 운영 혹은 장치를 일컫는 말입니다.
대개의 경우 입력에 함께 출력이 발생하게 됩니다. 단, 키보드와 마우스 처럼 입력을 위한 기기, 프린터처럼 출력에만 사용하는 기기도 있습니다.
프로세서와 메모리, 확장슬롯, 마더 보드에서 일어나는 데이터 전송도 I/O라고 일컬어집니다.

## 3.RAID 1
![download](https://dthumb-phinf.pstatic.net/?src=%22http%3A%2F%2Fwww.seagate.com%2Ffiles%2Fwww-content%2Fmanuals%2Fbusiness-storage-nas-os-manual%2F_shared%2Fimages%2F117_ill_raid_1.png%22&type=w2)

* 장점: 디스크에 결함 허용, 물리적인 디스크가 손상되더라고 데이터는 안전하게 복구 가능

* 단점: I/O성능은 더 나빠짐(똑같은 데이터 중복저장)

## RAID 5
![download](https://dthumb-phinf.pstatic.net/?src=%22http%3A%2F%2Fwww.seagate.com%2Ffiles%2Fwww-content%2Fmanuals%2Fbusiness-storage-nas-os-manual%2F_shared%2Fimages%2F118a_ill_raid_5.png%22&type=w2)

* 장점: I/O성능 개선, 디스크 1개에 대해 결함 허용
    * 결함이 있는 디스크를 빼고 디스크를 넣으면 Rebuild 한다.

## RAID 6
![download](https://dthumb-phinf.pstatic.net/?src=%22http%3A%2F%2Fwww.seagate.com%2Ffiles%2Fwww-content%2Fmanuals%2Fbusiness-storage-nas-os-manual%2F_shared%2Fimages%2F118b_ill_raid_6.png%22&type=w2)

* 장점: 디스크 2개에 대해 결함 허용
    * raid 5에 비해 성능이 약간 떨어짐 하지만 우수한 데이터 보호 제공
    
