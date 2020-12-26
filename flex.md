### 学习进度：https://www.bilibili.com/video/BV1N54y1i7dG?p=20


### flex 父容器的属性
display:flex; 布局方式
flex-direction:row,column  设定主轴方向

justify-content:flex-start   从起始开始排列
justify-content:flex-end   从结尾开始排列
justify-content:center  居中排列
justify-content:space-around 平分剩余空间
justify-content:space-between 先两边贴住，再平分剩余空间   重要！！



flex-wrap:wrap; //默认不换行，如果不换行，会压缩子元素

align-content:设置侧轴上子元素的排列方法（必须是多行下有效）

### flex 的item的属性
flex: 2  //在剩余空间中占据2份
align-self:控制自己在侧轴的排列方式  ===也就是脱离整体的侧轴排列方式，单独拿出来设置样式
order:1  //排列顺序，越小越靠前 默认是0



#### 目录说明
1. index.html --- 基础flex布局
2. index2.html --- column布局，主轴侧轴居中
3. index3.html --- row布局，主轴侧轴居中,wrap换行
4. index4.html --- align-content: space-between
5. index5.html --- 左右固定，当中自适应width
6. index6.html --- 子item 的 flex:<number> 的写法
7. index7.html --- 子item 的 align-content: space-between 的写法 ，在align-item或者align-content整体设置之外，单独对item进行设置
8. marginAuto.html --- 利用margin:auto 来使得水平居中