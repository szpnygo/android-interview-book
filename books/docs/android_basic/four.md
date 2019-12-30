# 四大组件
## 四大组件是什么
## 四大组件的生命周期和简单用法
## Activity 怎么和Service 绑定？
## 怎么在Activity 中启动自己对应的Service？
## service和activity怎么进行数据交互？
## Service的开启方式

## 请描述一下Service 的生命周期

## 谈谈你对ContentProvider的理解

## 说说ContentProvider、ContentResolver、ContentObserver 之间的关系

## 请描述一下广播BroadcastReceiver的理解

## 广播的分类

## 广播使用的方式和场景

## 在manifest 和代码中如何注册和使用BroadcastReceiver?

## 本地广播和全局广播有什么差别？

## BroadcastReceiver，LocalBroadcastReceiver 区别

## 是否使用过本地广播，和全局广播有什么差别？
## Android Service与Activity之间通信的几种方式
## 说下Activity的启动模式，生命周期，两个Activity跳转的生命周期，如果一个Activity跳转另一个Activity再按下Home键在回到Activity的生命周期是什么样的
启动模式
Standard模式:Activity可以有多个实例，每次启动Activity，无论任务栈中是否已经有这个Activity的实例，系统都会创建一个新的Activity实例

SingleTop模式:当一个singleTop模式的Activity已经位于任务栈的栈顶，再去启动它时，不会再创建新的实例,如果不位于栈顶，就会创建新的实例

SingleTask模式:如果Activity已经位于栈顶，系统不会创建新的Activity实例，和singleTop模式一样。但Activity已经存在但不位于栈顶时，系统就会把该Activity移到栈顶，并把它上面的activity出栈

SingleInstance模式:singleInstance模式也是单例的，但和singleTask不同，singleTask只是任务栈内单例，系统里是可以有多个singleTask Activity实例的，而singleInstance Activity在整个系统里只有一个实例，启动一singleInstanceActivity时，系统会创建一个新的任务栈，并且这个任务栈只有他一个Activity

## 四大组件及生命周期；ContentProvider的权限管理(读写分离，权限控制-精确到表级，URL控制)；Activity的四种启动模式对比；Activity状态保存于恢复
