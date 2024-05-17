# Bug汇总
## 文章数量过多无法完整显示
运行或生成静态文件时，提示：`Error: EMFILE: too many open files`

官方有对此错误作出说明：
虽然 Node.js 有非阻塞 I/O，同步 I/O 的数量仍被系统所限制，在生成大量静态文件的时候，您可能会碰到 EMFILE 错误，您可以尝试提高同步 I/O 的限制数量来解决此问题。

提供了在Linux系统下的解决方法: `ulimit -n 10000`，但windows没有说明。

GitHub Pages使用Actions可以生成站点。如果文章过多，仍然会导致数据库过大，影响搜索服务响应。
