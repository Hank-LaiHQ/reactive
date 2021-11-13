函数式接口:
    
    接口                         入参       出参   说明
    Predicate<T>                boolean     /    断言
    Consumer<T>                 T
    Function<T,R>               T          R     输入T输出R的函数
    Supplier<T>                 /          T     提供一个数据
    UnaryOperator<T>            T          T     一元函数(输入输出相同)
    BiFunction<T,U,R>           (T,U)      R     2个输入函数
    BinaryOperator<T>           (T,T)      T     二元函数(输入输出相同)