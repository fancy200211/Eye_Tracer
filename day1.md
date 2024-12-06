# day1

1. 学习正则表达式与grep指令
- []字符表示从中选一个，可以用-号表示一个范围
- ^号在 [] 内代表“反向选择”，在 [] 之外则代表定位在行首的意义！$号表示行尾
- .号表示任意一个字符
- *号表示重复前一个字符,零次到无数次，可以用 .* 表示任意长度字符
- ()表示捕获，捕捉括号内容，在（）后加入 ？匹配零次或一次 *匹配零次或多次 +匹配一次或多次 
- 引用捕获可以用 \num
- none greedy input symbol:  .*?  match one time or zero

2. 复习vim指令
- 宏命令必须完备，每次改写宏命令都是覆写操作
- ^q为可视块操作

3. 配置PA1
- 在~/.zshrc 中部署环境变量PATH改写gcc编译路径

4. other useful command in linux
- *sed* for replacement **sed /regular expression/replace text/mode(g for the whole page)**
- *awk* for editting the input stream,great for operating columns
    - sort and awk are like programming language and can support program.
- *sort* for sorting and *wc -l* for counting lines
- *bc* calculator
- *paste*
- *R* programming lang, cal and statistic analysing
- *xargs* take the input data by line as args to another command 
```bash
    find . -path *.html | xargs rm 
    # remove all the files with a suffix of .html in current directory
```
