# Tugas-Aplikasi-Mobile-Fix
activity_main.xml.
 
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    tools:context=".MainActivity"> //direktori dimana button dan text berada

   <Button
        android:id="@+id/tombol"                                     
        android:layout_width="200dp"
        android:layout_height="70dp"
        android:text="@string/teks1"
        android:textSize="20sp"
        android:textColor="#ffff"
        android:layout_margin="10dp"/>
//di atas id yang nantinya akan di panggil sebagai intent dari activiti
    <Button
        android:id="@+id/button2"
        android:layout_width="200dp"
        android:layout_height="70dp"
        android:text="teks2"
        android:textSize="20sp"
        android:textColor="#ffff"
        android:layout_margin="10dp"/>

    <Button
        android:id="@+id/button3"
        android:layout_width="200dp"
        android:layout_height="70dp"
        android:text="teks3"
        android:textSize="20sp"
        android:textColor="#ffff"
        android:layout_margin="10dp"/>

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:text="Tekan Teks1" />


</LinearLayout>
activity_main.xml.
 
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    tools:context=".MainActivity"> //direktori dimana button dan text berada

   <Button
        android:id="@+id/tombol"                                     
        android:layout_width="200dp"
        android:layout_height="70dp"
        android:text="@string/teks1"
        android:textSize="20sp"
        android:textColor="#ffff"
        android:layout_margin="10dp"/>
//di atas id yang nantinya akan di panggil sebagai intent dari activiti
    <Button
        android:id="@+id/button2"
        android:layout_width="200dp"
        android:layout_height="70dp"
        android:text="teks2"
        android:textSize="20sp"
        android:textColor="#ffff"
        android:layout_margin="10dp"/>

    <Button
        android:id="@+id/button3"
        android:layout_width="200dp"
        android:layout_height="70dp"
        android:text="teks3"
        android:textSize="20sp"
        android:textColor="#ffff"
        android:layout_margin="10dp"/>

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:text="Tekan Teks1" />


</LinearLayout>
activity_2.xml :
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_margin="12dp"
    tools:context="android.">
      //koding di bawah adalah kodingan untuk scrollview
    <ScrollView
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical" >

                                                                              <TextView
                android:id="@+id/textView"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/teks_panjang"
                android:textSize="15sp" />

        </LinearLayout>
    </ScrollView>
</RelativeLayout>
