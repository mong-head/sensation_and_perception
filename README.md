# sensation_and_perception
감각 및 지각 심리학 과제를 하면서 심리 통계를 그래프로 나타내 보았다.

muller-lyer illusion magnitude illusion관련이다.

각 session당 225 trial을 했다. 


모든 세션은 항상 upper-line은 450px로 standard line이다.

lower-line은 [370,390,410,430,450,470,490,510,530]px중 하나이다.

lower-line이 upper-line 보다 더 길어 보인다면 L key를 누른다.


1 session은 lower-line이 wing이 없는 형태,

2 session은 lower-line의 wing이 inward로 있는 형태,

3 session은 lower-line의 wing이 outward로 있는 형태이다.

# 실험

![K-008](https://user-images.githubusercontent.com/52481037/79642004-f19f7d80-81d5-11ea-8c71-f85a662c64ee.jpg)


![K-007](https://user-images.githubusercontent.com/52481037/79642006-f3694100-81d5-11ea-9a22-2c2dacbb001d.jpg)


![K-009](https://user-images.githubusercontent.com/52481037/79642008-f49a6e00-81d5-11ea-8eed-9a1587b4d22d.jpg)


![K-011](https://user-images.githubusercontent.com/52481037/79642010-f6643180-81d5-11ea-977a-916f34bf68f7.jpg)


엑셀로 했을때는 sigmoid함수를 만들기 어려웠다. 
그래서 logistic regression을 이용해서 분석을 해보았다.


# <엑셀로 했을때>


![K-012](https://user-images.githubusercontent.com/52481037/79641769-86a17700-81d4-11ea-97f3-754676546363.jpg)


![K-013](https://user-images.githubusercontent.com/52481037/79641775-899c6780-81d4-11ea-9be7-6fab8f23bdc0.jpg)


![K-014](https://user-images.githubusercontent.com/52481037/79641778-8bfec180-81d4-11ea-8fc2-19f6dd184192.jpg)



 # <colab을 이용했을 때>


![K-021](https://user-images.githubusercontent.com/52481037/79641795-a3d64580-81d4-11ea-89fe-948a4b9424bc.jpg)


![K-022](https://user-images.githubusercontent.com/52481037/79641797-a6389f80-81d4-11ea-8b32-28ca854305f7.jpg)


![K-023](https://user-images.githubusercontent.com/52481037/79641798-a769cc80-81d4-11ea-81f5-a939fe38f5ce.jpg)
