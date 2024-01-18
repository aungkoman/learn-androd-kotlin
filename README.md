# Learn Android Repo (Kotlin Version)

## ဒီမှာ လေ့လာ

https://developer.android.com/courses/pathways/android-basics-compose-unit-1-pathway-3


ဓာတ်ပုံ အပြည့်ပေါ်စေဖို့

```kotlin
Image(
            painter = image,
            contentDescription = null,
            contentScale = ContentScale.Crop,
            // Ensure the image takes the entire screen
            modifier = Modifier.fillMaxSize().alpha(0.5F)
        )
```

ကိုယ့်ရဲ့ Compose Widget က ဘယ်လောက် နေရာယူနေလဲ သိချင်ရင် modifier မှာ Background Color ထည့်ကြည့်လိုက်။

```kotlin
modifier = Modifier
        .fillMaxSize()
    .padding(8.dp)
    .background(color = Color.Blue)
```


#### String တွေကိုလည်း Resource အနေနဲ့ပဲ သုံးကြတယ်။

stringResource(id = R.string.by)
