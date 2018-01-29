##后缀优先级

该demo是测试当node\_modules中存在enhance\_show.js，同时存在enhance\_show.json,require查找顺序是什么

同时该demo也说明package.json中的main会覆盖默认的index.js的查找

1. 打开命令行工具
2. 通过cd命令，将执行路径调整到F:\2018\demo\node_require\demo001
3. 输入node命令，进入REPL(交互式解释器)
4. 输入require('enhance_show')
5. 查看输出结果

输出结果为F:\2018\demo\node\_require\demo001\node_modules\enhance\_show.js