SimpleController
================
　これは簡単なGUIを用いてMotonLoaderへモーション再生のコマンドを送ることのできるコンポーネントです。  
　  
コンポーネントの仕様
--------------------

　　　[![画像1][image1]](https://github.com/downloads/s-ryuki/Pictures/SimpleController_Comm.png)
[image1]:https://github.com/downloads/s-ryuki/Pictures/SimpleController_Comm.png

　MotionLoaderと接続することで各ボタンに割り当てられたコマンドを送ることができます。  

GUIの説明
---------
　　各ボタンには下図の様にコマンドが割り当てられています。  
　　　　※実際は番号は表示されません。  

　　　[![画像2][image2]](https://github.com/downloads/s-ryuki/Pictures/SimpleController_GUI-Guide.png)
[image2]:https://github.com/downloads/s-ryuki/Pictures/SimpleController_GUI-Guide.png

使用方法
--------
　　　　(1)motionloader.iniでSimpleControllerのコマンドと、それに対応して再生するモーションの設定を行い保存します。  
　　　　(2)SimpleController.pyを起動します。  
　　　　(3)RTSytemEditor上でSimpleControllerコンポーネントを繋ぎ、Activateします。  
　  
　　本コンポーネントはMotionEditor等を用いて作成したモーションの確認等に有用です。  