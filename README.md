# PageIndicatorView

<img src="https://user-images.githubusercontent.com/18132015/79177862-f2c75800-7e2d-11ea-9b23-dcd3ca40e23d.jpg" width="300">

How to

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

    gradle
    maven
    sbt
    leiningen

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.nguyenkhiem7789:PageIndicatorView:0.1.0'
	}
	
Usage

XML:

<RelativeLayout>
    ...

	<com.nguyen.indicatorview.IndicatorView
        android:id="@+id/indicator"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>

    ...
</RelativeLayout>

Java:

	indicatorView.setViewPager(viewPager); //make sure that adapter had added to viewpager

