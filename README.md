# tts库说明

> 内置语音引擎

使用:

```groovy
dependencies {
	implementation 'com.github.zhongyanlin523:tts:1.0.0'
}
```

使用:

```kotlin
//在进到主页进行初始化
TtsManager.getInstance().init(this)

//语音播报
TtsManager.getInstance().speak(message, 0.8f, true)
```


