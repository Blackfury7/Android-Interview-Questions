This repository is for intern level interview questions for android role.

Questions:

Q. Things you thinks recyclerview can improve on

Q. Kotlin all operators like lazy, lateinit, is, etc.

Q. Lamda function uses

Q. Activity lifecycle when call comes? 
Ans -> onPause and onStop. After call cut onRestart onStart onResume

Q. Which activity life cycle method trigger when orientation change?
Ans -> onPause() -> onSaveInstanceState() -> onStop() -> onDestroy()
       onCreate() -> onStart() -> onResume()
       
Q. When onDistroy will get called before onPause or onStop?
Ans -> When their is an exception in onCreate/onPause/onResume nothing gets called and when we call finish() only onDestroy is called.

Q. High order functions

Q. How room works

Q. How retrofit works 

Q. In which project will you use data binding and in which viewBinding?

Q. Diff between MVVM and MVVM Clean

Q. Why MVVM

Q. Services

Q. Broadcast receiver

Q. Why Single activity app?
Ans -> https://oozou.com/blog/reasons-to-use-android-single-activity-architecture-with-navigation-component-36

Q. Flows vs live data, uses of flow when and when live data

Q. Const vs val vs companion object vs object

Q. Different classes in kotlin (sealed, object, data, etc.)

Q. Interface vs abstract 

Q. Extention functions

Q. Coroutines uses in different situation like using coroutine scope block, async block, await, await all, etc.

Q. Work of ViewModel

Q. Activities, fragment back stack

Q. passing data between activities present in backstack
