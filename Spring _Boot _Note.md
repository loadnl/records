#Spring Boot学习笔记

@RestController表示不渲染视图 直接输出结果  
@GetMapping 是@RequestMapping(method = RequestMethod.GET)的缩写  
@RequestParam(required=false,defaultValue="")String name 表示http请求?name=??  

@Data 自动生成 getters, setters, toString(),equals()

@Document 标志适用于MongoDB

ReactiveCrudRepository实现基本操作，save,delete,deleteById,deleteAll,findById,findAll

@Configuration 标记类位bean资源

SpringBoot在Application启动和运行之后 运行所有CommandLineRunner

./gradlew clean build 编译项目

java -jar build/libs/name.jar运行



