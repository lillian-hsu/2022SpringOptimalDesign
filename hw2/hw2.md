# HW2 report

## Q1
![](https://i.imgur.com/bbLGE8H.png)

## result

### golden section method
![](https://i.imgur.com/ppbGRG4.png)
![](https://i.imgur.com/14gdrAb.png)
#### parameters:
`a = -2`  
`b = 2`  
`ep = 10 ** (-7)`  

### Dichotomous search method
![](https://i.imgur.com/9JaSDWg.png)
![](https://i.imgur.com/xDIImLL.png)
#### parameters:
`a = -2`  
`b = 2`  
`delta = 0.0000001`  
`ep = 10 ** (-5)`

## Q2
![](https://i.imgur.com/ZWc4lIl.png)
![](https://i.imgur.com/uBbhkDd.png)

## result

### cyclic coordinate method
![](https://i.imgur.com/6pF70w8.png)
#### parameters:
`(x, y) = (0, -5)`  
`ep1 = 10 ** (-5)`  
`ep2 = 10 ** (-7)`

![](https://i.imgur.com/anDx7sL.png)
#### parameters:
`(x, y) = (-5, 5)`  
`ep1 = 10 ** (-5)`  
`ep2 = 10 ** (-7)`

![](https://i.imgur.com/thRl3SF.png)
#### parameters:
`(x, y) = (5, 2)`  
`ep1 = 10 ** (-5)`  
`ep2 = 10 ** (-7)`

![](https://i.imgur.com/VHjb74O.png)
#### parameters:
`(x, y) = (2, -2)`  
`ep1 = 10 ** (-5)`  
`ep2 = 10 ** (-7)`

## Q3
![](https://i.imgur.com/7Ikt4Wz.png)

## result

### Nelder-Mead downhill simplex method
![](https://i.imgur.com/XBi83Ri.png)

#### parameters
`p1 = [0, -5]`  
`p2 = [-5, 0]`  
`p3 = [5, 5]`  
`epsilon = 10 ** (-5)`  

![](https://i.imgur.com/wZSl1ez.png)
#### parameters
`p1 = [0, -5]`  
`p2 = [-5, 0]`  
`p3 = [-5, -5]`  
`epsilon = 10 ** (-5)`  

![](https://i.imgur.com/uAO8vNf.png)
#### parameters
`p1 = [5, 5]`  
`p2 = [-5, 0]`  
`p3 = [-5, 5]`  
`epsilon = 10 ** (-5)`  

![](https://i.imgur.com/raYH4YG.png)
#### parameters
`p1 = [5, -5]`  
`p2 = [0, -5]`  
`p3 = [0, -2]`  
`epsilon = 10 ** (-5)`  

![](https://i.imgur.com/IWoFYgS.png)
#### parameters
`p1 = [2, -5]`  
`p2 = [0, -3]`  
`p3 = [2, -1]`  
`epsilon = 10 ** (-5)`  

![](https://i.imgur.com/4uueENO.png)
#### parameters
`p1 = [2, -5]`  
`p2 = [2, -4]`  
`p3 = [4, -4]`  
`epsilon = 10 ** (-5)`  


###### 有些initial point會進入無窮loop，如`p1 = [-5, 0], p2 = [0, 0], p3 = [0, 5]`，還沒解決
![image](https://user-images.githubusercontent.com/61599898/162715088-ae7a7f95-95d6-4196-a482-9e42572ab3ab.png)
