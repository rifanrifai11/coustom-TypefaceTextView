# coustom-TypefaceTextView
Penggunaan TypefaceTextView secara coustom untuk mengganti jenis Font pada TextView di Android Studio.

##Konsep Penggunaan dalam struktur coding XML di Android Studio

``` xml
<goku.britech.id.cully.Utility.TypefaceTextView
                                android:maxLength="30"
                                android:textColor="@color/colorTextButton"
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:text="Kentucky Fried Chicken"
                                android:textSize="23dp"
                                android:textStyle="bold"
                                android:gravity="center"
                                android:textAlignment="textStart"
                                android:paddingLeft="4dp"
                                android:id="@+id/food_menu_merchant_name"
                                geekui:customTypeface="fonts/Typo_Round_Light_Demo.otf"/>
```

###Code Utama Mengganti Font, mengambil font pada folder Asset
``` xml 
			<geekui:customTypeface="fonts/Typo_Round_Light_Demo.otf"/>
```

Sebelum menggunakan coustom-TypefaceTextView pastikan membuat Folder Asset sebagai manifest Font Style.
