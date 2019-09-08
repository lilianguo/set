# set
# Set 相对于List, Map是最简单的一种集合。 集合中的对象不按特定的方式排序，并且没有重复对象
# TreeSet 类实现了SortedSet接口， 自然升序排列
# 基本操作
boolean add(Object o)   :向集合中加入一个对象的引用
void clear()                        :删除集合中所有的对象，即不再持有这些对象的引用
boolean isEmpty()           :判断集合是否为空
boolean contains(Object o): 判断集合中是否持有特定对象的引用
Iterartor iterator()              : 返回一个Iterator对象，可以用来遍历集合中的元素
boolean remove(Object o):从集合中删除一个对象的引用
int size()                               :返回集合中元素的数目
Object[] toArray()                 :返回一个数组，该数组中包括集合中的所有元素
E higher(E ele )                   :method of TreeSet class in Java is used to return the least element in this set which is strictly greater than the given element ele. If no such element is there then this method returns NULL.