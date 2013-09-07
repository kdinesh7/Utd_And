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
         
      
         
    </TableRow>
    <TableRow android:layout_marginTop="2dip">
         
        <Button android:id="@+id/Send"
                android:clickable="true"
                android:width="86dip"
                android:text="Show Selected Value"
                android:layout_gravity="center_vertical|center_horizontal"/>  
     </TableRow>
    
        final Button Send = (Button) findViewById(R.id.Send);
          
        // Initialize AutoCompleteTextView values
         
            textView = (AutoCompleteTextView) findViewById(R.id.toNumber);
             
            //Create adapter    
            adapter = new ArrayAdapter<String>
                      (this, android.R.layout.simple_dropdown_item_1line, new ArrayList<String>());
            textView.setThreshold(1);
             
           //Set adapter to AutoCompleteTextView
            textView.setAdapter(adapter);
            textView.setOnItemSelectedListener(this);
            textView.setOnItemClickListener(this);
</TableLayout>
