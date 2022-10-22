# python-music
## 前置作業
在Anaconda Prompt中分別輸入:
- pip install mido
- pip install pygame

## 執行
依序執行所有cell，並打開MidiWrite視窗介面\
打開scores.xlsx檔，開始編寫歌曲
## 工作表數值存放位置
- 歌曲名稱: 工作表名稱
- BPM: A2
- 音軌數: A4
- 演奏樂器: A6、A7、A8
- 音符: B、D、F...
- 音符長度: C、E、G...

## 工作表編寫方式
- 歌曲名稱: 寫入歌曲的名稱，生成的.mid檔會以此命名
- BPM: 每分鐘的拍數，1拍=$\frac{60}{BPM}$秒
- 音軌數: 音樂的音軌數量
- 演奏樂器: 每個音軌要演奏的樂器
- 音符:
    - do: C / c
    - re: D / d
    - mi: E / e
    - fa: F / f
    - so: G / g
    - la: A / a
    - si: B / b
    - 升記號;降記號: #;b
    - 八度音: 0~8
    - 休止符: rest / REST / Rest
- 音符長度: 音符的持續長度
