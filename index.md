# **es6**
1.let const
> 操作描述符:
- writable
---
    var obj = { a: 1 };
    Object.defineProperty(obj, "a", {
        writable: false
     })
- configurable
---
    Object.defineProperty(obj,"a",{
        configurable:false
})

---
- enumerable
---
    Object.defineProperty(obj,"a",{
            enumerable: false
})

---
- value,
- get,
- set
# 2. git
- 创建分支 git branch 分支名字
- 查看是否创建成功 git branch
- 从master分支切换到自己的分支 git checkout 分支名
- 内容修改完成之后 提交 git add .
- 提交 git push -u origin 名字
- 切换到主分支 git checkout msater
- 提交到mster git pull origin master
- 将自己的分支合并到主分支 git merge 名字
- 查看状态 git status
- 把修改的内容提交到主分支 git push origin master
