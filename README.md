# AnimatedLinearLayout
Custom ViewGroup with animating childs

<img src="https://github.com/jineshfrancs/AnimatedLinearLayout/blob/master/screens/linear_layout.gif"/>

Add childs with required animation as tag

```
  <test.jinesh.animatedlinearlayout.AnimatedLinearLayout
        android:layout_width="match_parent"
        android:orientation="horizontal"
        android:layout_marginTop="10dp"
        android:gravity="center"
        android:layout_height="wrap_content">
        <TextView
            android:layout_width="wrap_content"
            android:text="@string/test_header_details"
            android:textColor="#fff"
            android:textSize="20sp"
            android:layout_marginRight="60dp"
            android:tag="SlideDown" //animation
            android:layout_height="wrap_content" />
        <ImageView
            android:layout_width="24dp"
            android:tag="ZoomInAndRotateClockWise"
            android:src="@android:drawable/ic_menu_close_clear_cancel"
            android:layout_height="24dp" />
    </test.jinesh.animatedlinearlayout.AnimatedLinearLayout>
```
