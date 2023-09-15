# صحبت اولیه
سلام من **رضا عمرانیان** هستم .



🧑🏻‍🎓دانشجوی رشته 💻نرم افزار و علاقه مند به برنامه نویسی اندرویدم، همچنین من عاشق تدریس و مطالب مربوط این زبان برنامه نوسیسی هستم راستی داخل سوشال مدیا های زیر هم عضوم پس اگه دوست داشتی منو دنبال کن. و برای دسترسی کافیه روی آیکون کلیک کنید تا صفحه من رو مشاهده کنید


‏[![logo_linkedin](./res/drawable/logo_linkedin.png)](https://www.linkedin.com/in/reza-omranian-aa5764132/)

‏[![logo_youtube](./res/drawable/logo_youtube.png)](https://youtube.com/@learndotroid)

‏ [![logo](./res/drawable/logo.png)](https://www.aparat.com/LearnDotRoid)

‏ [![logo_telegram](./res/drawable/logo_telegram.png)](https://t.me/reza_omranian)

‏ [![logo_insta](./res/drawable/logo_insta.png)](https://www.instagram.com/dev_omr)






برنامه نویسی هستم که بهینه . تمیز بودن کدش براش خیلی مهمه و سعی میکنه یه محیط نسبتا ساده اما زیبا رو به کاربرش هدیه بده بدون شک کاربرای من لایق بهترین ها هستن.

رضا عمرانیان 
 متولد سال 1379
 زاده شده در نصف جهان ینی اصفهان :)
- محل سکونت : ایران - اصفهان
- دیگر راه ارتباطی :


# دانشگاه ها :

[خوارزمی شهرضا](https://p-shahreza.tvu.ac.ir/)

[مهاجر ](https://mohajer.tvu.ac.ir/)



# من به تفسیر اندروید :
```xml 
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    <application
        android:name=".Birth"
        android:icon="./res/drawable/me.jpg"
        android:label="Reza Omranian"
        android:supportsRtl="true"
        tools:targetApi="22">
        <activity
            android:name=".Life"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest> 
```

```kotlin 
import android.app.Application

class Birth : Application() {
    override fun onCreate() {
        super.onCreate()

        while (true) {
            println("پسری که همیشه دنبال دانش هست")
        }
    }
}
```

```kotlin 
import androidx.appcompat.app.AppCompatActivity
import android.os.Bundle

class Life : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.life_view)


        while (!this.isFinishing) {
            for (totalHours in 0..24) {
                println("اندروید ")
            }
        }

    }
}
```
