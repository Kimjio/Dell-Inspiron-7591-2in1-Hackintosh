# Dell Inspiron 7591 2in1
Dell Inspiron 7591 2in1

### System Info
- CPU: Intel(R) Core(TM) i7-10510U CPU @ 1.80GHz
- Graphics: Intel Corporation UHD Graphics [8086:9b41]
- RAM: Samsung DDR4 2666MHz 16GB + Samsung DDR4 2666MHz 32GB -> 48GB
- Audio: Realtek ALC3254 (ALC295)

### UEFI 구성
| 구성 이름 | 값 |
| --- | --- |
| Secure Boot | Disabled |
| Secure Boot Mode | Deploy Mode (Audit Mode는 **OCB: LoadImage failed - Access Denied** 발생시킴) |

### 작동 목록

#### 입/출력
- [ ] Thunderbolt 3 (IOReg에 감지됨) (Intel Corporation JHL7540 Thunderbolt 3)
- [ ] Audio (출력 없음; 영상 재생 불가)
- [ ] Mic (Mic Array - Intel Smart Sount Technology)
- [x] HDMI OUT (소리 제외)
- [ ] microSD (Intel SD Host Controller)

#### 전원
- [x] PD 충전
- [ ] 잠자기 (작동유무 불확실)

#### I2C
- [x] 터치 스크린
- [ ] 터치패드 제스처 (DELL0950:00 04F3:30E3 (KIOXIA Corporation))

#### 네트워크
- [ ] Wi-Fi (Intel Corporation Wireless-AC 9462 [8086:02f0])
- [x] Bluetooth

#### USB
- [x] USB
- [x] Type-C USB (Thunderbolt 3 포트)
- [ ] 웹캠 (감지되지 않음) (Realtek Semiconductor Corp. Integrated_Webcam_HD [0bda:565a])
- [ ] 지문 (Shenzhen Goodix Technology Co.,Ltd. FingerPrint [27c6:538d])
