# 已知条件

通过接口```https://shopsearch.taobao.com/search?app=shopsearch&q=olmmlo&ajax=true&callback=fn```能够获取淘宝店铺信息，其中参数```q```为用户输入的查询字符串。

# 作业

通过用户输入的字符串，获取相应的淘宝店铺信息，并以表格的形式显示到当前界面上。

# 要求

1. 使用以下框架完成(任选一种)
   * React
   * Vue
   * layui
2. 使用**async/await/Promise**进行编码
3. 使用webpack转译到ES5的运行环境
4. 每个店铺显示的信息包括以下内容
   * 名称 *title*
   * 旺旺 *nick*
   * 图片 *picUrl*
   * 网址 *shopUrl*
5. 直接在本地址提交代码