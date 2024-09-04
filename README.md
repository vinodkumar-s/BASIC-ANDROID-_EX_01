# BASIC-ANDROID-_EX_01_Implementation of a Hello world Activity using all lifecycles methods using Android Studio.


## AIM:
To create Hello world Activity using all lifecycles methods to display messages using android studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min. required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM
### DEVELOPED BY :VINOD KUMAR S
### REGISTER NO: 212222240116

### MainActivity.java:
``` java
package com.example.exp1;

import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }


    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast.show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause() {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume() {
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop() {
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy() {
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
        toast.show();
    }
}

```
### Activity_Main.XML:
``` java
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="serif"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

  </androidx.constraintlayout.widget.ConstraintLayout>
```
## OUTPUT:

![WhatsApp Image 2024-09-04 at 9 14 06 AM](https://github.com/user-attachments/assets/f180f1dc-14e3-4486-8f4e-5f9f970ed995)

![WhatsApp Image 2024-09-04 at 9 14 05 AM (1)](https://github.com/user-attachments/assets/ce887a83-0355-4c38-92c7-e9479399a6d3)

![WhatsApp Image 2024-09-04 at 9 14 08 AM](https://github.com/user-attachments/assets/f05fad08-d14a-4d72-957f-c8bd18ff18f8)
![WhatsApp Image 2024-09-04 at 9 14 07 AM](https://github.com/user-attachments/assets/c6787cba-6cde-416e-b6bc-41ddb3b39bd2)
![WhatsApp Image 2024-09-04 at 9 21 08 AM](https://github.com/user-attachments/assets/0ea4f2ee-371d-4ba4-a4e8-29a4bcd0ff95)

![WhatsApp Image 2024-09-04 at 9 14 08 AM (2)](https://github.com/user-attachments/assets/7c0d3c7c-926c-44c5-8fa1-189e916ea8f4)



## RESULT:
Thus a program to implement the various life cycles of an activity is written and successfully executed using Android Studio.

