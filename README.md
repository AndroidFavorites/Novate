# Novate
   a  safety client by Https for Android,  (Android线程安全http请求库)

# Summary



#Download

Download the latest JAR:

or Gradle:

     compile project(':novate')
  
Snapshots of the development version are available in Sonatype's snapshots repository.

Retrofit requires at minimum Java 7 or Android 2.3.


--------------------------


# 中文文档

  基于Retrofit和RxJava封装的链式请求库，为何起名 Novate？
  
  Novate的英文原意是用新事物代替
  那我们用新的东西来代替Retrofit,新奇的东西，所以结合了原来的Http用法习惯，又加入了Retrofit的特性，因此起名 Novate

功能
----

   - 支持离线缓存
   - 支持多种方式访问网络（get,put,post ,delete）
   - 支持文件下载和上传
   - 支持请求头统一加入
   - 支持对返回结果的统一处理
   - 支持自定会的扩展API
   - 
   
用法
----

        Novate novate = new Novate.Builder(this)
                .baseUrl(baseUrl)
                .build();
                
       
# Get
        
        novate.executeGet(）
        
        

