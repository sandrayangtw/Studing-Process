# Studing-Process
heat = float(input('今天氣溫？'))
type = input('華氏（Ａ）或 攝氏（Ｂ）')

if type == 'A':
  print('華氏',heat,'度等於攝氏',(heat-32)/1.8,'度')
else:
  print('攝氏',heat,'度等於華視',heat*1.8+32,'度')
