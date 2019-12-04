# shimmer介绍
#### 软件包提供了一种在Flutter项目中添加闪光效果的简便方法

#### 如何使用

#### demo
```dart

SizedBox(
  width: 200.0,
  height: 100.0,    
  child: Shimmer.fromColors(
    baseColor: Colors.red,
    highlightColor: Colors.yellow,
    child: Text(
      'Shimmer',
      textAlign: TextAlign.center,
      style: TextStyle(
        fontSize: 40.0,
        fontWeight:
        FontWeight.bold,
      ),
    ),
  ),
);

```
