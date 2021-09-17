# 为什么选择godot

- 比unity简单，更加易上手，GDScript学起来也比C#简单

```
大部分使用unity的都在和lua做斗争，虽然官方说用C#但是实际上工作用的大部分是lua，脚本中的脚本
虽然unity可以把C#编译成二进制，但是使用这种方式也就意味着放弃了热更新
这个利弊对于不同项目不一样，需要频繁更新的游戏使用脚本语言更加友好，不需要频繁更新的完全使用C#也可以

现在需要频繁更新的比如王者荣耀，大部分都是用h5页面去做了，这个只需要JavaScript就可以了，比较完美和超前的解决方案

GDScript兼顾性能的同时，还带来比较简介的语法，还可以热更新
```

- 源代码开源，不收费，unity和ue都是要收费的，ue超过100万美元触发5%的分成费用
  ![Image text](apache-license.png)
  ![Image text](gd-home.JPG)

- godot的源代码比cocos的源代码少一倍，简介的代码更容易学习底层原理

```
godot的作者尽最大努力的减少第三方库的依赖，最终使其代码非常精简，适合学习
unity和ue安装后都得1g以上，godot下载包50m就搞定了，而且不用安装
ue虽然开源源代码，但是代码量太大，历史包袱太重，不适合深入研究底层代码的人 
```

- 自己能够本地编译godot源代码，成就感爆棚
- unity用多了，你会感觉自己就是个脚本小子

```
使用godot你既可以用GDScript去编写代码，也可以用C++去编写代码，还可以去改底层引擎代码
```

- 用godot你能感觉我能把控底层，我能把控每一行代码的底层细节，这个是程序员的浪漫，godot在国外比较火是有原因的

# 为使用godot我应该选择什么语言，C# or GDScript

- gds更加简单，支持的更加完整，而且是脚本可以热更新
- C#很多库用不了，有限制，如果是为了性能可以在godot中使用C++
- C#对于godot来说比较重，推荐gds
- unity在很久之前也同时支持过js和C#，最后放弃了js，主要是因为unity是mono和C#非常友好
- godot使用C++去解释执行gds，这个时候对于godot来说比较重，推荐gds
- 通过学习gds也可以学到一些编译原理的知识
- godot不仅仅是一个游戏引擎，而且还是一个优质的学习资源