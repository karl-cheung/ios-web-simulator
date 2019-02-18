# ios-web-simulator

> ios 模拟器预览内嵌网页。

## preview

![preview]

## Usage

+ 通过 Xcode 打开 ios-web-simulator.xcodeproj 文件

+ 自定义链接覆写至 ViewController.swift 文件中 URLRequest

+ 构建并运行当前方案（启动模拟器）

```swift
webView.loadRequest(URLRequest(url: URL(string: "https://vincheung.github.io/")!))
```

## License

The MIT License.

[preview]: ./public/preview.gif
