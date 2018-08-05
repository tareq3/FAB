# FAB
Animated Floating action Button


#1:
allprojects {
		repositories {
			...
			
			maven { url 'https://jitpack.io' }
		}
	}

#2:
dependencies {

	        implementation 'com.github.tareq3:advanced_fab:1.0'
	}



## Example @XML:
```
 <com.mti.fablibrary.FloatingActionsMenu
        android:id="@+id/floatingActionButton"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:elevation="5dp"
        app:fab_addButtonColorNormal="@color/white"
        app:fab_addButtonColorPressed="@color/white_pressed"
        app:fab_addButtonPlusIconColor="@color/half_black"
        app:fab_addButtonSize="mini"
        app:fab_addButtonStrokeVisible="false"
        app:fab_expandDirection="left"
        app:layout_anchor="@+id/include2" //set own anchor if uisng coordinator layout
        app:layout_anchorGravity="right|top"
       >

        <com.mti.fablibrary.FloatingActionButton
            android:id="@+id/fab_open_contact"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"

            android:cropToPadding="true"
            app:fab_colorNormal="@color/white"
            app:fab_colorPressed="@color/white_pressed"

            app:fab_icon="@drawable/ic_phone" //set your own icon right here
            app:fab_size="mini"
            app:fab_mti_icon_size="30dp"
            app:fab_title="Contact" />

        <com.mti.fablibrary.FloatingActionButton
            android:id="@+id/fab_fb_friends"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            app:fab_colorNormal="@color/white"
            app:fab_colorPressed="@color/white_pressed"
            app:fab_size="mini"
            app:fab_icon="@drawable/ic_fb" //set your own icon right here
            app:fab_mti_icon_size="30dp"/>

    </com.mti.fablibrary.FloatingActionsMenu>
```


Creadit: 
I used [ android-floating-action-button](https://github.com/futuresimple/android-floating-action-button?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=965)  library by [Base](https://android-arsenal.com/user/futuresimple) as a base for development.
