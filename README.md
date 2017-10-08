# Retrofit Converter of Kotlin serialization

It convert JSON request/response by [Kotlin serialization](https://github.com/Kotlin/kotlinx.serialization) for Retrofit.


## usage

```kotlin
val retrofit = Retrofit.Builder()
    .baseUrl("https://api.github.com/")
    .addConverterFactory(SerializationConverterFactory.create())
    .build()
```

## notes

experimental