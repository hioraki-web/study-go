# 第一个GO程序

经过上面的两篇文章我们已经完成了go环境的搭建和IDEA的安装了，接下来可以开始写我们的第一个go语言程序了。

老规矩 第一行代码就是hello world，先不要管其他细节让我们开始吧。

创建一个mian.go的文件

```go
package main

import "fmt"

func main() {
	fmt.Println("hello world") // hello world
}

```

然后我们运行 go语言的命令 `go run mian.go` 注意当前文件的路径一定要选对。

然后我们的终端就会出现 `hello world ` 啦。



