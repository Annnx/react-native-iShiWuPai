## iShiWuPai
iShiWuPai是基于React Native和Redux实现的美食类APP，接口来自《食物派》。项目中关于View的state都放在xxxView.js组件（比如ListView的数据源），其他的state数据都迁至对应的reducer中。

## 完成功能
目前只针对iOS端，完成功能：
>* 逛吃页面，支持下拉刷新和上拖加载更多
>* 资讯详情页面
>* 食物百科页面
>* 食物列表页面所有功能，包括子类别排序、营养素排序功能及动画，支持上拖加载更多

## 部分功能演示
![排序](https://github.com/ljunb/react-native-iShiWuPai/blob/master/screenshot/sortList.gif)

## 运行截图
![逛吃](https://github.com/ljunb/react-native-iShiWuPai/blob/master/screenshot/strolling.png)
![资讯详情](https://github.com/ljunb/react-native-iShiWuPai/blob/master/screenshot/feedDetail.png)
![食物百科](https://github.com/ljunb/react-native-iShiWuPai/blob/master/screenshot/categories.png)
![排序功能](https://github.com/ljunb/react-native-iShiWuPai/blob/master/screenshot/sortList.png)
![排序功能](https://github.com/ljunb/react-native-iShiWuPai/blob/master/screenshot/subcategory.png)

## TODO
>* 搜索页面
>* 食物详情、对比页面
>* 我的页面
>* 分享、收藏

## 相关依赖
```
"dependencies": {
    "react": "^15.0.2",
    "react-native": "^0.26.1",
    "react-native-swiper": "^1.4.4",
    "react-native-vector-icons": "^2.0.2",
    "react-redux": "^4.4.5",
    "redux": "^3.5.2",
    "redux-thunk": "^2.1.0"
},
"devDependencies": {
    "redux-devtools": "^3.3.1"
}
```