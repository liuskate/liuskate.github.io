## 深度学习常规流程

#### 模型选择
  先从简单模型开始，逐步使用复杂模型
  
#### 过拟合/欠拟合
  - 测试集区分 集内、集外测试集  
  - 集内测试集的结果，表征了模型的能力上限，即只要数据集够大，在测试集上应该也能达到相似的效果  
  - 集内集外测试集上的diff，表达了是欠拟合 or 过拟合；
  - 若欠拟合，增加模型复杂度；若过拟合，开启dropout or 简化模型结构
#### 优化器的选择
  - 先使用带动量的SGD尝试。如果优化不动可以试试Adam



[软连接](https://github.com/liuskate/liuskate.github.io/edit/master/index.md)

# 一级主题
## 二级主题
### 三级主题

- 无序列表1
- 无序列表2

1. 有序列表1
2. 有序列表2

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
空白，不进行markdown格式转义

# Header 1
## Header 2
### Header 3

- 无序列表1
- 无序列表2

1. 有序列表1
2. 有序列表2

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/liuskate/liuskate.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
