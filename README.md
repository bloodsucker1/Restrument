#开发环境：AndroidStudio


##开发文档规范：

###1.	类和接口 命名
命名规则：类名是个一名词，采用大小写混合的方式，每个单词的首字母大写。尽量使你的类名简洁而富于描述。使用完整单词，避免缩写词(除非该缩写词被更广泛使用，像 URL，HTML)  
###2.	方法的命名
命名规则：方法名是一个动词，采用大小写混合的方式，第一个单词的首字母小写，其后单词的首字母大写。
###3.	成员变量命名
同变量命名，但不要在私有变量前添加m字样！
###4.	常量命名
命名规则：类常量的声明，应该全部大写，单词间用下划线隔开。
例如：static final int MIN_WIDTH = 4; 
例如：static final int MAX_WIDTH = 999; 
例如：static final int GET_THE_CPU = 1;  
###5.	layout 命名
规约：layout xml 的命名必须以 全部单词小写，单词间以下划线分割，并且使用名词或名词词组，即使用 模块名_功能名称 来命名。
###6.	id 命名
规约：layout 中所使用的id必须以全部单词小写，单词间以下划线分割，并且使用名词或名词词组，并且要求能够通过id直接理解当前组件要实现的功能。
###7.	资源命名
规约：layout中所使用的所有资源（如drawable,style等）命名必须以全部单词小写，单词间以下划线分割，并且尽可能的使用名词或名词组，即使用 模块名_用途 来命名。如果为公共资源，如分割线等，则直接用用途来命名
###8.	方法注释
每一个方法都要包含 如下格式的注释 包括当前方法的用途，当前方法参数的含义，当前方法返回值的内容和抛出异常的列表。

