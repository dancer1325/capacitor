<br />
<div align="center">
  <img src="https://user-images.githubusercontent.com/236501/105104854-e5e42e80-5a67-11eb-8cb8-46fccb079062.png" width="560" />
</div>
<div align="center">
  ⚡️ Cross-platform apps -- via -- JavaScript & Web ⚡️
</div>

---

* Capacitor 
  * lets you 
    * 👀run web apps NATIVELY | iOS, Android, Web / 1! codebase & cross-platform APIs 👀
  * 's design
    * use | EXISTING modern web app
  * provides
    * cross-platform API (Plugin API)
      * ways to write plugins
        * to distribute
          * | Capacitor apps
          * packaged | npm dependency
            * -- recommended for -- community use
        * to code
          * | iOS, Swift
          * | Android, Kotlin or Java
    * code execution layer / makes it easy to
      * from web code -- call -- Native SDKs
      * write CUSTOM native plugins 
    * 👀first-class Progressive Web App support 👀
      * == write 1 app (web one) / deployed | app stores

## How to set up?
### | Existing app
* initialize Capacitor | your app
  ```
  npm install @capacitor/core @capacitor/cli
  npx cap init
  ```
* install | DESIRED NATIVE platforms
  ```
  # Android
  npm install @capacitor/android
  npx cap add android
  
  # iOS
  npm install @capacitor/ios
  npx cap add ios
  ```

### From scratch

* recommendation
  * use [Ionic Framework](https://ionicframework.com/) + Capacitor
    * if you do NOT use Ionic -> 
      * require 
        * implement Native UI, by yourself
        * configure tooling
          * _Example:_ to get [livereload feature](https://ionicframework.com/docs/cli/livereload)
          * Reason: 🧠NOT have Ionic CLI 🧠
      * see [benefits using Ionic](https://capacitorjs.com/docs/getting-started/with-ionic)
* `npm install -g @ionic/cli`
  * install the [Ionic CLI](https://ionicframework.com/docs/cli/)
* `ionic start --capacitor`
  * start a NEW app

## FAQ

### Capacitor vs Cordova

* SAME spirit
* 👀backward compatibility -- with a -- vast majority of Cordova plugins👀
* Capacitor 's tooling & plugin development vs Cordova's
  * MORE modern approach 
  * NATIVE projects
    * source artifacts vs build artifacts
* DIFFERENT Team maintenance
* check [ALSO here](https://capacitorjs.com/docs/cordova#differences-between-capacitor-and-cordova)
