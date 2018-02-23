## react抛物线小球
> 写了个小球，方便自己以后用

| API           | 说明               | 类型      |
| ------------- |:------------------:| ---------:|
| terminal      | 终点坐标           | Object    |
| origin        | 起点坐标           | Object    |
| id            | 小球id             | String    |
| complete      | 落到终点的函数     | Function  |

使用说明：在父组件中需要获取起点坐标和终点坐标，并且需要定义一个state，(balls)来存储小球。当小球落到终点后，complete接收id作为参数，根据id来把小球删除

演示：
![image](https://github.com/capslocktao/react-fall-ball/blob/master/ballgif.gif)