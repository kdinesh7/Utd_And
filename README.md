Utd_And
=======

Ant_D<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="fill_parent"
    android:layout_height="fill_parent"
    android:background="#000000" >
 
    <TableRow>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="20px"
            android:text="Write character"
            android:textColor="#ffffff"
            android:layout_marginLeft="10dip"></TextView>
    </TableRow>       
    <TableRow>
         
        <AutoCompleteTextView
            android:id="@+id/toNumber"
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:layout_marginLeft="10dip"
            android:layout_marginRight="10dip"
            android:textColor="#000000"
            android:textColorHighlight="#000000"
            android:textColorLink="#000000"
            android:textStyle="bold"
            android:width="250dip" />
         
    </TableRow>
    <TableRow android:layout_marginTop="2dip">
         
        <Button android:id="@+id/Send"
                android:clickable="true"
                android:width="86dip"
                android:text="Show Selected Value"
                android:layout_gravity="center_vertical|center_horizontal"/>  
     </TableRow>
  
</TableLayout>
