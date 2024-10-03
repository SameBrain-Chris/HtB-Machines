
---
fileClass: Machine
---

<p align="center"> <img src= "https://www.hackthebox.com//storage/avatars/0eff5f0d7d2208024e519e5abfb132d0.png"> </p>

#machine

## Operation system - Linux
<img style = "max-width:70px" src = "app://local//home/kali/HTNotes/HTB/.res/Linux.png">

## Metadata

|                       |   |
| ----------------      | - |
| ID                    |626 |
| Name                  |Trickster |
| Active                |✅  |
| User Flag             |✅ |
| Root Flag             |✅|
| Difficulty Text       |Medium  |
| Stars                 |⭐️ 2.4 |
| Created Note          |10/02/24 |
| Published             |09/21/24 |
| tags                  | |

<p style = "display:none">
id:: 626
active:: True
name:: Trickster
os::Linux
user_flag:: True
root_flag:: True
difficulty_text:: Medium
stars:: 2.4
created:: 10/02/2024
published:: 09/21/24
avatar:: /storage/avatars/0eff5f0d7d2208024e519e5abfb132d0.png
tags:: 
</p>

## Statistics


```chartsview
#-----------------#
#- chart type    -#
#-----------------#
type: Radar

#-----------------#
#- chart data    -#
#-----------------#
data:
  - item: "ENUM"
    user: "user"
    score: 5.5
  - item: "REAL"
    user: "user"
    score: 4.6
  - item: "CVE"
    user: "user"
    score: 5.2
  - item: "CUSTOM"
    user: "user"
    score: 4.8
  - item: "CTF"
    user: "user"
    score: 5.4
  - item: "ENUM"
    user: "author"
    score: 0
  - item: "REAL"
    user: "author"
    score: 0
  - item: "CVE"
    user: "author"
    score: 0
  - item: "CUSTOM"
    user: "author"
    score: 0
  - item: "CTF"
    user: "author"
    score: 0

#-----------------#
#- chart options -#
#-----------------#
options:
  xField: "item"
  yField: "score"
  seriesField: "user"
  meta:
    score:
      alias: "Score"
      min: 0
      nice: true
  xAxis:
    line: null
    tickLine: null
  yAxis:
    label: false
    grid:
      alternateColor: "rgba(0, 0, 0, 0.04)"
  point: []
  area: []
```



### User rating


```chartsview
#-----------------#
#- chart type    -#
#-----------------#
type: Column

#-----------------#
#- chart data    -#
#-----------------#
data:
    - folder: "PIECE OF CAKE"
      count: 93
     
    - folder: "VERY EASY"
      count: 66

    - folder: "EASY"
      count: 171
      
    - folder: "NOT TO EASY"
      count: 311
      
    - folder: "MEDIUM"
      count: 524
     
    - folder: "A BIT HARD"
      count: 331
      
    - folder: "HARD"
      count: 209
      
    - folder: "EXTREMELY HARD"
      count: 74
      
    - folder: "INSANE"
      count: 20
      
    - folder: "BRAINFUCK"
      count: 46

    

#-----------------#
#- chart options -#
#-----------------#
options:
  xField: "folder"
  yField: "count"
  padding: auto
  label:
    position: "middle"
    style:
      opacity: 0.6
      fontSize: 12
  columnStyle:
    fillOpacity: 0.5
    lineWidth: 1
    strokeOpacity: 0.7
    shadowColor: "grey"
    shadowBlur: 10
    shadowOffsetX: 5
    shadowOffsetY: 5
  xAxis:
    label:
      autoHide: false
      autoRotate: true
  meta:
    count:
      alias: "Votes"
```



```button
name Update this Machine info
type link
action obsidian://shell-commands/?vault=HTB&execute=g7sm2q030y
templater true
```

