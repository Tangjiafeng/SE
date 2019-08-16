## 常用类：
### java.util.Queue

注意Queue的 **remove()** 和 **poll()** 方法唯一的区别在于，当Queue为空时，调用remove()方法抛出异常，poll()方法返回null。

另外：

element()，返回队列头部的元素，如果队列为空，则抛出一个NoSuchElementException异常

offer(e)，添加一个元素并返回true，如果队列已满，则返回false

peek()，返回队列头部的元素，如果队列为空，则返回null
