# 传统IO与NIO比较


传送IO特点
阻塞点
server.accept();
inputStream.read(bytes);

单线程情况下只能有一个客户端


用线程池可以有多个客户端连接，但是非常消耗性能


=======================分割线==========================

NIO的特点

ServerSocketChannel	ServerSocket

SocketChannel		Socket

Selector

SelectionKey

