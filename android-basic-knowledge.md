1. An Adapter object acts as a bridge between an AdapterView and the underlying data for that view. The Adapter provides access to the data items. The Adapter is also responsible for making a View for each item in the data set.
2. A [Fragment ](https://github.com/codepath/android_guides/wiki/Creating-and-Using-Fragments)is **a piece of** an application's user interface or behavior that can be placed in an Activity. Interaction with fragments is done through FragmentManager, which can be obtained via Activity.getFragmentManager\(\) and Fragment.getFragmentManager\(\). [Why do you check for savedInstanceState == null when adding fragment? ](/adding)
3. [RecyclerView](https://github.com/codepath/android_guides/wiki/Using-the-RecyclerView)
4. > * Add RecyclerView dependency into gradle file \(how?\)
   > * Replace the ListView in .xml with RecyclerView
   > * Create view holder class 可以理解为坑，即初始化（某个功能）用到的各种View（将layout文件中的View赋值，用ButterKnife）
   > * Create adapter class
   > * Choose layout manager and use RecyclerView in MainActivity 组合
5. [CardView](https://github.com/codepath/android_guides/wiki/Using-the-CardView), [Navigation Drawer & Toolbar](https://www.gitbook.com/book/sugarac/android-tutorials-summary/edit#), [Toolbar](https://github.com/codepath/android_guides/wiki/Using-the-App-Toolbar)
6. ```css
               android:fitsSystemWindows="true" //自动调整Toolbar和StatusBar位置关系
               android:minHeight="?attr/actionBarSize"
   ```
7. [What is callback in Android? ](https://stackoverflow.com/questions/18054720/what-is-callback-in-android)
8. ViewHolder类将xml每个控件的id绑定到Java对象
9. [https://developer.android.com/topic/libraries/support-library/features.html\#v7](https://developer.android.com/topic/libraries/support-library/features.html#v7)
10. [Butter Knife](http://jakewharton.github.io/butterknife/)
11. xmlns: [http://blog.qiji.tech/archives/3744](http://blog.qiji.tech/archives/3744)
12. 静态图片，矢量图 \(res/drawable/\) 布局文件 \(res/layout/\) 菜单 \(res/menu/\) 程序图标 \(res/mipmap/\) 静态字符串 \(res/values/strings.xml\)
13. [Supporting Multiple Screens\(支持Android各种屏幕尺寸\)](http://blog.csdn.net/wzy_1988/article/details/52932875)
14. android:background="?attr/selectableItemBackground" 指定有界的波纹
15. .view.MainActivity 是MainActivity类所在位置
16. ADB: Android Debug Bridge
17. 在ShotListAdapter的onBindViewHolder中添加点击事件，以实现Activity切换
    > This is how the shot data flows between activities and fragments  
    > ShotListFragment \(generates fake data\)  
    > → ShotListAdapter \(displays fake data\)  
    > → ShotActivity \(gets data from ShotListAdapter\)  
    > → ShotFragment \(gets data from ShotActivity and displays it\)
18. Intent中的数据是Bundle
19. [Picasso，Glide，Fresco对比分析](http://blog.csdn.net/github_33304260/article/details/70213300)



