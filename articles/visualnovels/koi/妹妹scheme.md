### 第一章

1.1

[哥哥,scheme中最简单的元素有什么呀?]汐音一脸兴奋.

[那个呀,最简单的我们可以从表达式学起.]我回答.

[一个简单的数学表达式在scheme里面长这样]我迅速新建了一份文件并打出一个表达式.

```scheme
(+ 1 2)
```

[你看,scheme里面是符号前缀表示的,所以这个就表示1+2]我扭头看了一眼汐音,她正坐在我右边.润泽的眼睛目不转睛的看着屏幕.

[嗯,然后呢,前缀表示法有一个好处,就是可以对很多参数同时运用这种运算]我接着给她演示.

```scheme
(+ 1 2 2 4)
```

[哦!可以这样用]汐音点点头.

[乘法,减法和除法也都可以这样用哦]我继续演示.

```
(* 2 3 1)
6

(- 4 2 2 1)
-1

(/ 2 3 4)
1/6
```

汐音双腿并拢白皙的小手放在大腿上,认真的听着.一副认真思考的样子.

[scheme里面所有的表达式都要用括号括起来哦]我提醒汐音.

[再进一步的话,就是把简单的表达式组合起来,像这样]

```
(+ 2 (* 2 3))
```

[或者更复杂的]

```
(+ 1 (* 2 1 (-3 2)) 2 (+ 2 2))
```

[实际上,你可以嵌套任意多层!]

[这个表达式是什么意思呢?]我问汐音.

[嗯...]汐音又凑近了一点[这个...是...加起1,2,2,4吧]

[是哦!]

汐音眼睛中闪过一丝不易察觉的开心[因为哥哥最喜欢1224这个数字嘛.]

汐音笑了,很开心的样子.

[这样的嵌套式子结构不太清晰对吧?我们有一种叫做美化打印的东东,就是把复杂的式子结构理清一下,实际上和原来的式子没区别.]我演示给汐音看.

```scheme
(+ 1
   (* 2
      1
      (- 3 2))
   2
   (+ 2 2))
```



