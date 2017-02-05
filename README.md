### Step 1. Add the JitPack repository to your build file
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

### Step 2. Add the dependency
```
dependencies {
	        compile 'com.github.zhekeen:LoadingStyle:1.0.0.0'
}
```
### Custom .xml
```
<keen.lib.LoadingStyle
        app:indicatorColor="@color/custom"
        style="@style/LoadingStyle"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="5dp"
        android:id="@+id/loadingStyle" />
```
