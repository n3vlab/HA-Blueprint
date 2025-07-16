# 🏠 HA-Blueprint  
*My Personal Home Assistant Blueprint Repository*

## 🌬️ Auto Dry Mode After AC Shutdown

After the selected **air conditioner** has been running for a configured minimum duration,  
this automation triggers **when it turns off**. After a short delay, it switches the AC to  
**fan-only mode** at high speed for a configured time, then turns it off automatically.  

선택한 **에어컨이 설정된 최소 시간 이상** 동작한 후 꺼지면,  
약간의 지연 후 **송풍 강풍 모드로 전환**되고, 지정된 시간 동안 작동한 뒤 자동으로 꺼집니다.

### ⚙️ Features

- ⏱️ Minimum runtime check (최소 동작 시간 체크)
- ⏳ Delay after shutdown (종료 후 지연)
- 🌪️ Fan-only mode with high speed (송풍 + 강풍 모드)
- ⌛ Auto stop after duration (시간 경과 후 자동 꺼짐)
- ✅ 마지막 상태 확인 후 종료 (fan_only 상태일 때만 종료)
