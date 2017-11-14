<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/wallpaper"
        android:src="@drawable/wallpaper"
        android:scaleType="centerCrop"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />

    <de.hdodenhof.circleimageview.CircleImageView
        android:id="@+id/doge"
        android:layout_width="390dp"
        android:layout_height="390dp"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:src="@drawable/doge" />

    <TextView
        android:id="@+id/happy_birthday"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="44dp"
        android:textColor="@android:color/white"
        android:fontFamily="sans-serif-condensed"
        android:paddingLeft="4dp"
        android:paddingTop="4dp"
        android:text="Happy Birthday, Billy!" />

    <TextView
        android:id="@+id/such_birthday"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-condensed"
        android:textColor="@android:color/white"
        android:textSize="32dp"
        android:layout_alignTop="@id/doge"
        android:layout_alignRight="@id/doge"
        android:layout_marginRight="20dp"
        android:layout_marginTop="45dp"
        android:text="Such Birthday" />

    <TextView
        android:id="@+id/celebrate"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-condensed"
        android:textColor="@android:color/white"
        android:textSize="32dp"
        android:layout_alignTop="@id/doge"
        android:layout_alignLeft="@id/doge"
        android:paddingLeft="12dp"
        android:text="So Celebrate" />

    <TextView
        android:id="@+id/wow2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-condensed"
        android:textColor="@android:color/white"
        android:textSize="32dp"
        android:layout_alignTop="@id/doge"
        android:layout_alignLeft="@id/doge"
        android:layout_marginTop="120dp"
        android:paddingLeft="16dp"
        android:text="Wow" />

    <TextView
        android:id="@+id/very_age"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-condensed"
        android:textColor="@android:color/white"
        android:textSize="32dp"
        android:layout_alignBottom="@id/doge"
        android:layout_alignRight="@id/doge"
        android:layout_marginBottom="120dp"
        android:layout_marginRight="18dp"
        android:text="Very Age" />

    <TextView
        android:id="@+id/superwow"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-condensed"
        android:textColor="@android:color/white"
        android:textSize="32dp"
        android:layout_below="@id/gift"
        android:layout_toRightOf="@id/gift"
        android:text="Super Wow" />

    <TextView
        android:id="@+id/gift"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@id/doge"
        android:fontFamily="sans-serif-condensed"
        android:textColor="@android:color/white"
        android:textSize="32dp"
        android:paddingLeft="8dp"
        android:layout_marginBottom="50dp"
        android:text="Many Gift" />

    <TextView
        android:layout_alignParentRight="true"
        android:layout_alignParentBottom="true"
        android:textColor="@android:color/white"
        android:textSize="12dp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:paddingRight="8dp"
        android:paddingBottom="8dp"
        android:text="coded by vigyi" />

</RelativeLayout>
