# CapsNet
## 概念理解
 计算机图形学，基于几何数据内部的分层表示，构造可视化图像。这类表示的结构需要考虑对象的相对位置。这些内部表示存储在计算机内存中。几何化的对象以数组表示，对象间的相对位置和朝向以矩阵表示。接着，特定的软件接受这些表示作为输入，并将它们转化为屏幕上的图像。这叫渲染。

 大脑做的和渲染正好相反，把这个叫做逆图形，从眼睛接收到的视觉信息中，大脑解析出我们周围世界的分层表示，并尝试匹配已学习到的模式和存储在大脑中的关系。辨识就是这样进行的。关键的想法是大脑中物体的表示并不依赖于视角。在三维图形中，三维对象之间的关系可以用位姿表示，位姿的本质是平移和旋转。胶囊理论结合了对象之间的相对关系，在数值表示为4维位姿矩阵。

 （脑中的物体内部表示并不依赖视角）胶囊方法相比CNN需要的数据集小得多。
