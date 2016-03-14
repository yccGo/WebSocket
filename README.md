# WebSocket

Java WebSocket编程

通过注释来自定义WebSocket @ServerEndPoint("/chat") 括号中的是注释中的value值，URI

页面通过new WebSocket（url）创建，之后同服务器端一样定义onMessage，onError，onClose，onOpen等方法处理事件
