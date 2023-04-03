## length用法
1、如果要得到字符串的长度，需调用String的实例方法，因为String作为引用数据类型跟对象一样，则需要用.length()；\
2、因为length为数组中的一个属性（成员变量），所以我们在获取数组的length时不需要加括号\

## charAt()
charAt(int index)方法是一个能够用来检索特定索引下的字符的String实例的方法.\
charAt()方法返回指定索引位置的char值。索引范围为0~length()-1.\
如: str.charAt(0)检索str中的第一个字符,str.charAt(str.length()-1)检索最后一个\
