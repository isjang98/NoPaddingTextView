# NoPaddingTextView

Font Size as TextView's height in NoPaddingTextView. So It's TextView

## Compare TextView with NoPaddingTextView
### TextView(기본) - 기본적으로 들어가는 상하 여백
	<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="쏘카 타자~ ABCDEFGHIJK"
        android:textSize="70px"
        android:background="@android:color/holo_red_dark"
        />

![](https://github.com/isjang98/NoPaddingTextView/blob/master/img/wrap_textview.png)

### TextView - (height = textSize) 로 같게 했을 경우 발생하는 글자 잘림 현상
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="70px"
        android:textSize="70px"
        android:text="쏘카 타자~ ABCDEFGHIJK"
        android:background="@android:color/holo_blue_dark"
    />
    
![](https://github.com/isjang98/NoPaddingTextView/blob/master/img/50px_textview.png)

### **NoPaddingTextView** - 상하여백 없는 TextView
    <kr.socar.wordlib.NoPaddingTextView
    	android:layout_width="wrap_content"
    	android:layout_height="70px"
    	android:textSize="70px"
    	android:text="쏘카 타자~ ABCDEFGHIJK"
    	android:background="@android:color/holo_orange_light"
    />

![](https://github.com/isjang98/NoPaddingTextView/blob/master/img/NoPaddingTextView.png)

# Getting Started
please type it in your build.gradle file.

	repositories {
        jcenter()
    }
    
	dependencies {
    	compile 'kr.socar.wordlib:wordLib:0.1.0'
	}    
    

# Example Usage	
    <kr.socar.wordlib.NoPaddingTextView
        android:layout_marginTop="50px"
        android:layout_width="wrap_content"
        android:layout_height="70px"
        android:textSize="70px"
        android:text="쏘카 타자~ ABCDEFGHIJK"
        />


## Developed By
- Word - isjang98@gmail.com
