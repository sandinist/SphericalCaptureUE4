# Spherical Capture UE4
UE4.13 以上で動作する、全天球イメージを撮影するサンプルです。

# Example
MotionControllerMap に組み込んだ例があります。MotionControllerPawn のカメラ位置でキャプチャを行います。

# How to Use
Content/SphericalCapture を Content 以下にコピーしてください。

撮影したい位置のオブジェクトに SceneCaptureComponentCube を追加して Detail で下記の設定を行ってください
* Texture Target に CubeRenderTarget を追加
* Capture Every Frame を Off
* Capture on Movement を Off
* Auto Activate を Off

BluePrint で下例のように呼び出しを行ってください。
![saveHDR](https://raw.githubusercontent.com/sandinist/SphericalCaptureUE4/master/Images/Call.png)

こちらでも解説しています: http://qiita.com/sandinist/items/b54090586f5575ea62eb

# Contact
[@sandinist](https://twitter.com/sandinist) までどうぞ
