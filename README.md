#### flex box 布局

- 是一维布局方式，解决元素的响应，元素对齐，分布；一次只能解决一个维度布局

- 开启`flex`布局只需在父容器中设置 `display: flex` 子元素默认按**行**进行排列

> 父容器

- `flex-direction`
- `flex-wrap`
- `flex-flow`
- `align-items`
- `align-content`
- `justify-conent`

> 子元素

- `flex-grow`
- `flex-shrink`
- `flex-basis`
- `flex`
- `align-self`
- `order`

##### 设置 flex-direction: row 时候

> **行**: 主轴

- [x] 靠右对齐`justify-content: flex-end`

- [x] 居中对齐`justify-content: center`

- [x] 平分空间`justify-content: space-evenly`

- [x] 两端对齐`justify-content: space-between`

> **列**：交叉轴

- [x] 靠下对齐`align-items: flex-end`

- [x] 居中对齐`align-items: center`

##### 设置 flex-direction: column 

##### 子元素

- [x] 通过调试`flex: 1 | flex: 2`占比进行

#### Grid 布局

- 是二维布局方式，由水平线（行轨道）与列轨道

- 开启在外层容器`display: grid`

> **设置宽度，显示指定列**

- [x] 固定宽度：`grid-template-columns: 100px 100px 100px`

- [x] 浮动宽度：`grid-template-columns: 1fr 1fr 1fr`

- [x] 设置列间距：`column-gap: 24px`

- [x] 设置行间距：`row-gap: 24px`

- [x] 设置列与行间距：`gap: 24px`





