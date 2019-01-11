# Flutter Local Notification

Step 1 : Add flutter_local_notifications dependency in your pubspec.yaml file.
dependencies:
  flutter:
    sdk: flutter
  flutter_local_notifications:
  
Step 2 : Add VIBRATE and RECEIVE_BOOT_COMPLETED permission to your AndroidManifest.xml [ Optional ]

    <uses-permission android:name="android.permission.VIBRATE" />
    <uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED"/>
    
Step 3: Add image inside drawable directory for Notificaiton Icon [ Optional ]
( flutter_app_name > android > app > src > res > drawable > app_icon.png )
If you don’t add image for notification icon then you have to tell the app to use app icon, which is stored in ‘mipmap’. [ ANDROID ]


Step 4 : Add a Tone (Music) for Notification [ Optional ]

To add custom Tone (Music)

Make a directory inside res directory.
Keep a small Audio (Music) there and remember the file name.
( flutter_app_name > android > app > src > res > raw > slow_spring_board.mp3 )