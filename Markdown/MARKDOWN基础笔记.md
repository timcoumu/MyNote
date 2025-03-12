<center><h1>MARKDOWN基础笔记</h1></center>

[详细内容](https://markdown.com.cn/basic-syntax/)
## 标题
- **\#[空格]**
&emsp;&emsp;一级标题
- **\#\#[空格]**
&emsp;&emsp;二级标题
- **......**
&emsp;&emsp;以此类推
- **\====**
&emsp;&emsp;文字下方添加任意“=”识别一级标题
- **\------**
&emsp;&emsp;文字下方添加任意“-”识别二级标题
## 段落
- **[空行]**
&emsp;&emsp;一个段落
## 换行
- **[空格][空格]**
&emsp;&emsp;添加两个以上的空格，推荐用\<br\>
## 强调
- **\*\*[文本]\*\***
&emsp;&emsp;加粗
- **\*[文本]\***
&emsp;&emsp;斜体
## 引用
- **\>**
&emsp;&emsp;块引用
- **\>\>**
&emsp;&emsp;嵌套块引用
## 列表
- 1\.
  2\.
  ......
  &emsp;&emsp;有序列表，以1\.起始，可以嵌套
- \-
  \-
  ......
&emsp;&emsp;无序列表，以\-或\*\+开始，可以嵌套
## 代码
- \`[代码]\`
&emsp;&emsp;反引号包裹
## 分割线
- \*\*\*
&emsp;&emsp;\*\*\*分割
- \-\-\-
&emsp;&emsp;\-\-\-分割
- \_\_\_
&emsp;&emsp;\_\_\_分割
## 超链接
- \[链接名\]\(链接地址\ \"链接title\")
&emsp;&emsp;添加超链接
- \<网址或email\>
&emsp;&emsp;使网址或链接可点击
- 、\*\*\[超链接名\]\(超链接地址\)\*\*
&emsp;&emsp;带有格式(加粗)的链接
## 图片
- \!\[图片alt\]\(图片链接 \"图片title\"\)
&emsp;&emsp;添加图片
- \[\!\[图片alt\]\(图片链接 \"图片title\"\)\](链接)
&emsp;&emsp;[![图片链接（前往图片转base64）](https://www.toolhelper.cn/Image/Base64 "图片title")](链接)
- \!\[图片alt\]\(data:image/png;base64,Base64编码\)
&emsp;&emsp;添加base64图片
