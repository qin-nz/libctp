# libctp
上期所提供的CTP二进制，使用 swig 封装为 go lib

## 原理

利用 Swig 为使用 C++ 编写的 ctp 的二进制进行 warpper 处理，生成 Go 代码，并编译成类库。因为本库只引用了 Linux 版的CTP二进制，因此编译后的Go程序也只能在Linux上运行。

具体原理可参考 [Swig 的 Go 文档](http://swig.org/Doc2.0/Go.html)
