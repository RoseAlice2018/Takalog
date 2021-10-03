# Takalog

- 需求
1. 日志是重要的debug工具，因此，日志系统需要携带必要的参数，方便debug
    - 时间
    - thread id 。对于多线程可选
    - 准确的源码溯源。日志log函数被调用的源码文件名_FILE_,源码行号_LINE_,源码函数名_FUNCTION_。
    - 简单易用的调用方式
    - crash自动trace
2. 日志输出定向。
    - 支持输出到屏幕，输出到文件，