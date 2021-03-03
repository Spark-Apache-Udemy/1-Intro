# 1-Introducción

0. [Info en el shell](#schema0)
1. [Primeros pasos](#schema)
2. [Primera ejecución del contador](#schema2)


<hr>

<a name="schema0"></a>

# 0. INFO en el shell
~~~python
spark = SparkSession.builder.getOrCreate()
spark.sparkContext.setLogLevel("ERROR")

conf = SparkConf().setMaster("local").setAppName("RatingsHistogram")
sc = SparkContext(conf = conf)
sc.setLogLevel("ERROR") 
~~~
