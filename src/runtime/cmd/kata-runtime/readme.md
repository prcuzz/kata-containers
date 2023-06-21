# 代码结构

入口在main.go，用了cli来创建一个app，实现的功能由runtimeCommands定义。其中kataCheckCLICommand在kata-check.go中实现，kataEnvCLICommand在kata-env.go中实现，依此类推。

