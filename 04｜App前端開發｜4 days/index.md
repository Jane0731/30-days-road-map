# App 開發
## 開發 App 的所需工具
因 Apple 採用的是封閉系統，而不是使用開放系統。故 iOS 的應用程式只能在 Apple 自己的裝置如 iPhone 與 iPad 中運作。和 Android 的應用程式不同的是，Android 系統可以在不同製造商所製作的行動裝置中運作。如果想要同時開發 iOS 及 Android 的應用程式，就需使用 Mac 電腦做開發。
### 使用 Mac 電腦開發 App
#### 申請 Apple ID
需要一個 Apple ID 才能下載 Xcode，以及閱讀 iOS SDK 文件與其他技術資源。
若是從來沒有建立過Apple ID，到 [Apple 的網站]( https://appleid.apple.com/account ) 跟著步驟來註冊即可。
#### 安裝 Xcode
要開發 iOS App 時，Xcode 是唯一需要下載的工具。Xcode 是一個由 Apple 所提供的整合開發環境（Integrated Development Environment ），它提供開發 App 所有的工具。Xcode 包含了最新版本的 iOS SDK（Software Development Kit ）、一個內建的程式碼編輯器、圖形化使用者介面（ User Interface ）編輯器、除錯（ Debug ）工具，以及其他的工具。最重要的是，Xcode 提供了 iPhone（或iPad ）的模擬器，讓使用者不需要用到實體裝置也能測試你的 App。

當要安裝 Xcode 時，必須開啟你的 Mac 電腦的 Mac App Store 來下載。若是你使用最新版本的 Mac OS，你應該可以在 Mac 電腦下方的 Dock 工具列找到 Apple Store 的圖示。如果找不到的話，使用者可能需要升級到新版的 Mac OS。
### 使用 Windows 電腦開發 App
#### 安裝 Android Studio
Android 為採用 Java 程式設計語言技術，在安裝開發工具Android Studio前，JDK  ( Java Developement Kit ) 環境是基本條件。2017年的 Google I/O 開發者大會中，已經正式把 Kotlin 納入 Android 程式的官方一級開發語言，目前新版的 Android Studio 4 已經不需要事先安裝JDK( Java Development Kit ) 了，因為Android Studio 已有自帶的 JRE ( Java Runtime Environment ) 執行環境。

Android Studio是由 Google 與 JetBrains 合作所開發的新一代 Android IDE整合開發 工具，提供專案管理、編譯、程式設計、除錯、版面設計等，請到 Android Developers 網站中[Android Studio](https://developer.android.com/studio)網頁下載。
## 常見的 App 開發方式
### Native App
根據智慧型手機的作業系統本身提供的SDK 或建議的開發方式來設計給行動裝置上運行的應用程式。
- Android
使用Java、C語言、Kotlin編寫，以Android Studio作為開發工具
- iOS
使用Swift、Objective-C編寫，以Xcode作為開發工具
#### Native App 優勢
1. 良好用戶體驗 ( UX ) - 用戶能夠很快了解如何使用。但是須與系統升級進行匹配，否則就會帶來外觀的不協調感與操作穩定性差等問題。 
2. App性能更好 - 由於 Native App 是由非標準語言及工具開發而成的，當使用者想開發特別功能，即為原生功能以外的功能，就會建議使用者開發 Native App 。整個系統運作起來會更順暢，用戶體驗亦會變得更好。
3. App運行速度較快 - 不會出現因為用戶瀏覽量暴增而導致死機的狀況出現。這個情況只需調整數據庫的主從分離、讀寫分離以及數據庫的負載均衡就能解決到問題。據科學研究指出，兩秒的延遲就足以令一部分的用戶結束瀏覽。所以手機App的運行速度愈順暢，就會令用戶留存率愈高，用戶體驗都得以改善。
#### Native App 劣勢
1. App開發成本高 - 原生語言程式所需要的技術人員比較多，由於不同平台有不同的開發語言和界面適配，所以至少需要一個Android和一和iOS的開發工程師，所以開發成本相對地高，開發時間也比較長。
2. App維護成本高 - 需要更多開發人員來做維護。
3. App更新緩慢 - 根據不同的平台，操作的模式及程序都不同。例如提交、審核、上架等，需要經過的流程都相對比較複雜，所需的時間就會比較多。
### Hybrid App
混合開發方式結合了App的原生開發方式與Html5技術混合運用，並且彌補了原生開發的缺點，跨平台的App不需要分別開發，同一套程式碼只需要做小部分修改即可供Android及iOS使用。而且程式碼維護方便，App更新速度也快，不需要每次更新都上應用程式商店審核，在伺服端修改更新即可。

常見的混合開發技術有React Native、Flutter、Cordova、AppCan......等
### Progressive Web App
## 參考資料
1. [第1 章- 開發工具、學習方法與App 點子](https://www.appcoda.com.tw/learnswift/get-started.html)
2. [學Android程式設計，第一步先安裝Android Studio 開發工具](https://walker-a.com/archives/6806)
3. [Day2-為什麼選擇Flutter？React Native、原生開發 - iT 邦幫忙](https://ithelp.ithome.com.tw/articles/10216825)
4. [Native App和Hybrid App的分別（上）](https://technine.io/en/native-app%E5%92%8Chybrid-app%E7%9A%84%E5%88%86%E5%88%A5%EF%BC%88%E4%B8%8A%EF%BC%89/)
