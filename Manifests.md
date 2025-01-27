Add permissions to Manifest.XML
<uses-permission android:name="android.permission.READ_MEDIA_IMAGES"></uses-permission>
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"></uses-permission>


//Dont forget to call this method im onCreate!!

  override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        registerLauncher()
    }
