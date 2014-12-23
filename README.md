# A circular progressbar with sweeping angle
![demo](shots/demo.gif)

## usage

In build.gradle config dependency.

``` groovy
compile 'org.quanqi:CircularProgress:1.0.2'
```

In laout xml

``` xml
<org.quanqi.circularprogress.CircularProgressView
    android:layout_width="100dp"
    android:layout_height="100dp"
    android:layout_margin="8dp"
    app:angleAnimationDurationMillis="@integer/circular_default_angleAnimationDurationMillis"
    app:borderWidth="@dimen/circular_default_border_width"
    app:colorSequence="@array/circular_default_color_sequence"
    app:sweepAnimationDurationMillis="@integer/circular_default_sweepAnimationDuration" />
```

## LICENSE
bsd-2

