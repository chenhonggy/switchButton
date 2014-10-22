switchButton是根据IOS开关按钮风格做成的基于android 2.2以上的安卓按钮<br>
可以直接通过传入图片的drawable  id  就可以成功的运用<br>

![github](https://github.com/chenhonggy/switchButton/blob/master/example.jpg "github")

####如何开始
#####手动安装
    1.复制IosSwitchButton目录下的类到工程项目中.
    2.复制values文件夹下面的attrs.xml文件到工程项目中。

####开始编码
#####xml文件
在布局文件里面加上这句
        <com.switchbutton.main.IosSwitchButton.Ios_switchButton
                android:id="@+id/center_switch_button"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                switchbutton:bmHeight="50dp"
                switchbutton:bmWidth="150dp"
                android:layout_centerInParent="true"
                />
    加上这句之后别忘记了还要在最顶层的布局上面加上
    xmlns:switchbutton="http://schemas.android.com/apk/res-auto"
