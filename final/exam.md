# CS307 2022FA final exam 回忆版

- 总体题量一般，如果会的话大概率是可以写完的。
- 可以带一页A4手写的cheating paper。期末的cheating paper建议做得全面一点，个人感觉有部分题目是如果在cheating paper上写了就可以拿到分数的。

- 试卷组成：单选，不定项，大题。

- 单选和不定项选择多是对理论知识的考察，知识点个人感觉在各章分布比较均匀，大部分题目都不是很难，但由于不定项的存在，如果想要得高分的话需要对理论课的内容细节十分熟悉。

- 大题考察到的全部内容：ER图，写SQL语句及运行结果，画B-tree，serializability。
- 下面各部分的内容回忆大概是按题目在试卷中出现的顺序写的。

## 单选题

- 大概11,12个

- 问了SQL是什么的缩写（是Structured Query Language）
- 命名合法性：问给出的某名字是否valid
- 问某给出语句是DDL还是DML

## 不定项选择题

- 大概5,6个

- 有一个题是问给出的数据库satisfy哪一种或多种level的normal form

- 有一个题是关于null的性质：有选项问到null的运算

## 大题（大致按在试卷上的先后顺序）

- 第一个大题是画er图

- 第二个大题是写简单的查询语句
- 有写insert into 语句的题目
- 写查询在某日期之后的数据的语句（涉及到写日期比较的语句）

- 某大题的一个小问是写 rank 函数
- 倒数第三大题是写出几个和union有关的查询的结果，有left union和多层union

- 倒数第二题是画出 B-tree insert nodes 之后的样子，有四小问，分别画出加1，2，3，4个 node 之后的 B-tree
- 最后一个题考的serializability，分别画出两个schedule的precedence graph，判断它们是不是conflict serializability并给出理由。
