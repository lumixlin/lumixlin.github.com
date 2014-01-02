Date: 2014-01-02
Title: Markdown note
Slug: markdown
Tags: note,web 

#### 格式
- markdown 内可直接使用HTML标签(block-level)， 标签内不可使用Markdown
- markdown 内使用HTML标签(block-level)时，首尾标签前后必须空行，并且不能缩进
- span-level 标签不受限制
- **强制换行** = 行尾两空格+回车
- **分隔线** = -----------

----------

#### 列表
- 示例 

		- 无序列表
		- 无需列表
		1. 有序列表
		2. 有序列表
		4. 有序列表

- 有序列表前的序号不影响输出的序号

----------

#### 代码
- 两个tab缩进生成代码块
- \`printf()\`生成行内代码 `printf()` 
- 代码内 `, &` 会被转为entity

----------

#### 标题
- 示例 

		# 一级标题
		## 二级标题
		### 三级标题
		###### 六级标题

----------

#### 强调
- 示例

		- *em*
		- **strong**
		- * em *

- *em*
- **strong**
- * em *  = 如果有空格的话将被当普通字符

----------

#### 段落
- 段落以空行分隔
- 自动换行，除非行尾有两空格加回车

----------

#### 链接
- 示例
		
		- This is [google](http://google.com "The google link"), an inline link. 
		- This is [reference][ref] reference-style link
		- [ref]: http://google.com "The google link"		
		- 自动链接 = <http://google.com>

- This is [google](http://google.com "THe google link"), an inline link. 
- This is [reference][ref] reference-style link
- **自动链接** = <http://google.com>

[ref]: http://google.com "The google link"

----------

#### 图片
- 示例

		- ![Alt text](/path/to/img.jpg "Optional Title")
		- ![Alt text][id]

