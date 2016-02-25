# .spacemacs

spacemacs 配置
主要针对ror进行配置

常用快捷方式

# spacemacs 常用快捷键总结
## emacs
```spc h spc``` emacs & spacemacs layouts document
```spc f e h``` 允许的layouts
```spc a k``` paradox查找packages（```/```搜索, ```f k```过滤）

## window
```spc 0-9``` 切换window
```spc w c``` 关闭当前window
```spc w /``` 右侧拆分window
```spc w s``` 下面拆分window

## buffer

```spc b b``` 切换buffer
```spc b d``` kill当前buffer
```spc b e``` 擦出当前buffer内容
```spc b R``` 从文件中从新加载当前buffer
```spc b w``` 切换是否只读
```spc b Y``` 拷贝buffer里面内容


## 项目&文件

```spc f t``` neotree 打开项目
```spc p p``` 切换项目
```spc p f``` 查找文件
```spc p d``` 查找目录
```spc p b``` 项目内跳buffer
```spc p t``` 在projectile中打开neotree
```spc p T``` 找到测试文件
```spc p v``` 项目维度打开magit
```spc s a p``` 项目里面用ag查找
```spc s g p``` 项目里面用grep查找
```spc p !``` 执行命令行
```spc p &``` 执行异步命令
```spc p v``` 项目根目录打开magit

## 文件

```spc f c``` 拷贝当前文件
```spc f R``` 从命名当前文件
```spc f s``` 保存当前文件修改内容
```spc f y``` 显示当前文件的绝对路径


## neotree

```h``` 打开/关闭或者跳到上层节点
```H``` 上个兄弟节点
```j``` 下个文件或文件夹
```k``` 上个文件或文件夹
```# l``` #为数字，在指定window中打开文件
```c``` 创建节点
```d``` 删除节点
```gr``` 刷新
```r``` 重命名


## 查找

**当前文件**

```spc s s``` 查找
```spc s a a``` ag
```spc s g g``` grep

**所有打开buffer**

``` spc s b```
```spc s a b```
```spc s g b```

**任意目录的文件查找**

```spc s f```
```spc s a f```
```spc s g f```

**项目内查找**

```spc /``` or ```spc s p```
```spc s a p```
```spc s g p```

**web**

```spc s w g``` google搜索
```spc s w w``` wiki搜索


## 注释

```spc ;``` 注释
```spc c l``` 注释行
```spc c L``` 反注释行
```spc c p``` 注释段落
```spc c P``` 反注释段落
```spc c t```注释行



## rails

```spc m r :``` 执行task
```spc m r c c```执行生成命令
```spc m r i``` rails c
```spc m r s r``` reload project
```spc m r x s``` start server

```spc t a``` rspec测试全部



