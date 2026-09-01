\# Git学习心得

今天学习了git add、commit、push三条命令。



\## 遇到的问题

一开始搞错了远程仓库地址，后来才明白origin是远程仓库别名。



> 感悟：一定要分清楚工作区、暂存区、本地仓库、远程仓库。



\### 代码片段示例

```cmd

git add .

git commit -m "更新笔记"

git push



写完保存，再执行三条上传命令：

```cmd

git add .

git commit -m "新增Git心得笔记"

git push

运行命令：`git init`

```c++

\\#include <iostream>

using namespace std;

int main()

{

\&#x20;   cout<<"hello world";

\&#x20;   return 0;

}



\\# 三、截图/图片怎么放进去（重点！）

GitHub不能直接粘贴图片。

\\### 步骤：

1\\. 在你的 `note‑book` 仓库文件夹里面，新建一个文件夹，名字叫 `images`

>专门存放所有笔记截图

2\\. 把截图图片复制到 `images` 文件夹

3\\. 在你的笔记md文件里，写上图片链接

```markdown

!\\\[截图说明文字](images/git界面截图.png)

2\\. 把截图图片复制到 `images` 文件夹

3\\. 在你的笔记md文件里，写上图片链接

```markdown

!\\\[截图说明文字](images/git界面截图.png)


