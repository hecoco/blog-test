### 浏览器渲染原理
根据HTML构建HTML树（DOM）
根据CSS构建CSS树（CSSOM）
两颗树合并成一颗渲染树（render tree）
Layout布局（文档流、盒模型、计算大小和位置）
Paint绘制（把边框颜色、文字颜色、阴影等画出来）
Compose合成（根据层叠关系展示画面）

### CSS 动画的两种做法（transition 和 animation）
transition:
        transition-property 过渡的属性
        transition-duration 过度动画所需要的时间
        transition-timing-function 过度速度曲线
        transition-delay 过度开始之前需要等待的时间

animation:
        @keyframes      声明关键帧
        animation-name      关键帧名字
        animation-duration  过度动画所需要的时间
        animation-timing-function 过度速度曲线
        animation-delay     过度开始之前需要等待的时间
        animation-iteration-count 定义动画在结束前运行的次数(infinite 无限循环播放)
        animation-direction 指示动画是否反向播放(alternate)
        animation-fill-mode
        animation-play-state 定义一个动画是否运行或者暂停(running运行 paused 停止)

animation 属性不分先后

### 其他任何你想写的。