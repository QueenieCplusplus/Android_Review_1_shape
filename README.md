# Android_Review_1_shape
login app using shape to do a round button 


![](https://raw.githubusercontent.com/QueenieCplusplus/Android_Review_1_shape/main/output1.png)

![](https://raw.githubusercontent.com/QueenieCplusplus/Android_Review_1_shape/main/output2.png)

# Shape

 see res/drawable/round_shape in under project.
 
 
     <?xml version="1.0" encoding="utf-8"?>
    <shape xmlns:android="http://schemas.android.com/apk/res/android">
        <corners android:radius="100dp" />
        <solid android:color="#00FF00" />
    </shape>
    
    
see res/layout/activity_main.xml

           <Button
                android:id="@+id/btn_submit"
                android:text="Login"
                android:background="@drawable/round_shape"
                android:textColor="@color/black"
                android:textAllCaps="false"
                android:padding="20dp"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
              />

# Dimens

![](https://raw.githubusercontent.com/QueenieCplusplus/Android_Review_1_shape/main/dimens.png)

ref : 

https://www.itread01.com/content/1547691692.html

http://blog.wulk.com.tw/android-round-corner-button/
