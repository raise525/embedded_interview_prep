1. sizeof 是运算符， strlen是函数，需要导入string.h
2. sizeof是计算内存大小， strlen是计算字符串长度
3. sizeof（"\0"）:是2，   strlen("\0"):是零，因为字符串就是以\0结尾的