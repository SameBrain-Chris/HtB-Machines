
---
fileClass: Machine
---

<p align="center"> <img src= "https://www.hackthebox.com//storage/avatars/79616a32a057e5e672dadb51bb96dd04.png"> </p>

#machine

## Operation system - Windows
<img style = "max-width:70px" src = "app://local//home/kali/HTNotes/HTB/.res/Windows.png">

## Metadata

|                       |   |
| ----------------      | - |
| ID                    |627 |
| Name                  |Cicada |
| Active                |✅  |
| User Flag             |✅ |
| Root Flag             |✅|
| Difficulty Text       |Easy  |
| Stars                 |⭐️ 4.3 |
| Created Note          |10/02/24 |
| Published             |09/28/24 |
| tags                  | |

<p style = "display:none">
id:: 627
active:: True
name:: Cicada
os::Windows
user_flag:: True
root_flag:: True
difficulty_text:: Easy
stars:: 4.3
created:: 10/02/2024
published:: 09/28/24
avatar:: /storage/avatars/79616a32a057e5e672dadb51bb96dd04.png
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
    score: 7.1
  - item: "REAL"
    user: "user"
    score: 5.8
  - item: "CVE"
    user: "user"
    score: 5.6
  - item: "CUSTOM"
    user: "user"
    score: 4.4
  - item: "CTF"
    user: "user"
    score: 4.2
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
      count: 486
     
    - folder: "VERY EASY"
      count: 521

    - folder: "EASY"
      count: 935
      
    - folder: "NOT TO EASY"
      count: 417
      
    - folder: "MEDIUM"
      count: 244
     
    - folder: "A BIT HARD"
      count: 78
      
    - folder: "HARD"
      count: 49
      
    - folder: "EXTREMELY HARD"
      count: 18
      
    - folder: "INSANE"
      count: 3
      
    - folder: "BRAINFUCK"
      count: 15

    

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

