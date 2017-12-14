1. An Adapter object acts as a bridge between an AdapterView and the underlying data for that view. The Adapter provides access to the data items. The Adapter is also responsible for making a View for each item in the data set.
2. A Fragment is **a piece of** an application's user interface or behavior that can be placed in an Activity. Interaction with fragments is done through FragmentManager, which can be obtained via Activity.getFragmentManager\(\) and Fragment.getFragmentManager\(\).
   [https://github.com/codepath/android\_guides/wiki/Creating-and-Using-Fragments](https://github.com/codepath/android_guides/wiki/Creating-and-Using-Fragments)
3. RecyclerView: [https://github.com/codepath/android\_guides/wiki/Using-the-RecyclerView](https://github.com/codepath/android_guides/wiki/Using-the-RecyclerView)

   > * Add RecyclerView dependency into gradle file \(how?\)
   > * Replace the ListView in activity\_main.xml with RecyclerView
   > * Create view holder class 可以理解为坑，即初始化（某个功能）用到的各种View（将layout文件中的View赋值，用ButterKnife）
   > * Create adapter class
   > * Choose layout manager and use RecyclerView in MainActivity 组合

4. [https://developer.android.com/topic/libraries/support-library/features.html\#v7](https://developer.android.com/topic/libraries/support-library/features.html#v7)

5. [Butter Knife](http://jakewharton.github.io/butterknife/)

6. xmlns: [http://blog.qiji.tech/archives/3744](http://blog.qiji.tech/archives/3744)



