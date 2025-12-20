---
title: Hello,World
date: 2025-12-20 10:02:30 +0800
categories: [Learn, Blog]
tags: [markdown]
description: This is the first post,Write some makrdown.
---

# 你好，世界

这份工作较为稳定，不会像之前那样没有个人时间，颇为轻松。故想建立一个类似个人博客的网站。本意是这样的，奈何学艺不精，自觉无甚值得分享于同好，便作为笔记性质的记录留存在这里吧。

## Markdown

markdown语法简单，在表现上也足以承担普通文档的观感，在网络上广泛被使用于文本记录。在这里便复习一下语法，也看一下在网站上的表现形式。

# 标题H1

## 标题H2

### 标题H3

#### 标题H4

##### 标题H5

###### 标题H6

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
# 标题H1

## 标题H2

### 标题H3

#### 标题H4

##### 标题H5

###### 标题H6
```
</details>

### 正文文字

<s>删除线</s>

*斜体字* _斜体字_

**粗体** __粗体__

***粗斜体*** ___粗斜体___

上标：H<sub>2</sub>，下标：O<sup>2</sup>

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
<s>删除线</s>

*斜体字* _斜体字_

**粗体** __粗体__

***粗斜体*** ___粗斜体___

上标：H<sub>2</sub>，下标：O<sup>2</sup>
```

</details>

### Html标签

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.
```
</details>

### 引用

> 引用文本

> 引用：引用内换行需要'\<br/\>'标签<br/>即可换行

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
> 引用文本

> 引用：引用内换行需要'\<br/\>'标签<br/>即可换行
```
</details>

### 链接

[链接](https://github.com/K5087)

[带标题的链接](https://github.com/K5087 "个人主页")

直接链接: <https://github.com/K5087>

[锚点链接][moke_link]

[moke_link]: https://github.com/K5087

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
[链接](https://github.com/K5087)

[带标题的链接](https://github.com/K5087 "个人主页")

直接链接: <https://github.com/K5087>

[锚点链接][moke_link]

[moke_link]: https://github.com/K5087
```
</details>

### 参考链接

测试[^1]脚注

[^1]: 这里可以放一些内容

[链接][2]

[2]: https://github.com/K5087
<details markdown="1">
<summary>点击此处展开</summary>
```markdown
测试[^1]脚注

[^1]: 这里可以放一些内容

[链接][2]

[2]: https://github.com/K5087
```
</details>

### 代码块

#### 行内代码

这是一个查看当前用户的命令 `whoami`

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
这是一个查看当前用户的命令 `whoami`
```
</details>

#### 缩进风格

缩进四个空格的正文会被代码块包起来

    #include <iostream>

    int main(int argc,char** argv)
    {
        std::cout<<"Hello,World\n";
    }

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
    #include <iostream>

    int main(int argc,char** argv)
    {
        std::cout<<"Hello,World\n";
    }
```
</details>

#### 代码块

```cpp
#include <iostream>

int main(int argc,char** argv)
{
    std::cout<<"Hello,World\n";
}
```

<details markdown="1">
<summary>点击此处展开</summary>
````markdown
```cpp
    #include <iostream>

    int main(int argc,char** argv)
    {
        std::cout<<"Hello,World\n";
    }
```
````
</details>

### 图片

带链接的图片
[![](/assets/images/道与碳基猴子饲养守则.png)](https://www.qidian.com/book/1017327563/ "道士大战外星人")

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
[![](/assets/images/道与碳基猴子饲养守则.png)](https://www.qidian.com/book/1017327563/ "道士大战外星人")
```
</details>

### 列表

#### 有序列表

1. 选项一
2. 选项二
3. 选项三

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
1. 选项一
2. 选项二
3. 选项三
```
</details>

#### 无序列表

- 列表一
- 列表二
- 列表三

* 列表一
* 列表二
* 列表三

- 列表一
- 列表二
- 列表三
  - 列表三-1
    - 列表三-1-1
  - 列表三-2
  - 列表三-3

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
- 列表一
- 列表二
- 列表三

- 列表一
- 列表二
- 列表三

* 列表一
* 列表二
* 列表三
  - 列表三-1
    - 列表三-1-1
  - 列表三-2
  - 列表三-3

```
</details>

#### 任务列表

- [x] 任务一
- [x] 任务二
- [ ] 任务三
  - [ ] 任务三-1
  - [ ] 任务三-1
  - [ ] 任务三-2

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
- [x] 任务一
- [x] 任务二
- [ ] 任务三
  - [ ] 任务三-1
  - [ ] 任务三-1
  - [ ] 任务三-2
```
</details>

### 表格

| 时间       |     地点     |       人物 |
| :--------- | :----------: | ---------: |
| 左对齐     |   居中对齐   |     右对齐 |
| 左对齐文本 | 居中对齐文本 | 右对齐文本 |

<details markdown="1">
<summary>点击此处展开</summary>
```markdown
| 时间       |     地点     |       人物 |
| :--------- | :----------: | ---------: |
| 左对齐     |   居中对齐   |     右对齐 |
| 左对齐文本 | 居中对齐文本 | 右对齐文本 |
```
</details>
