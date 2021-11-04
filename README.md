# Word-count problem with Hadoop MapReduce

### INPUT
- Type input : Text 
- Path : input.txt
- Description : A paragraph, any text

### OUTPUT
- Type output : Text
- Path : output/
- Description : [word] [frequency of occurrence]

# Run project
See details tutorial: [https://demanejar.github.io/posts/hadoop-mapreduce-and-wordcount-project/](https://demanejar.github.io/posts/hadoop-mapreduce-and-wordcount-project/#ch%C6%B0%C6%A1ng-tr%C3%ACnh-wordcount-v%E1%BB%9Bi-mapreduce)

```
mvn clean package
hadoop jar target/wordcount-V1.jar com.hadoop.mapreduce.WordCount <input_path> <output_path>
```
