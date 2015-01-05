mvn clean         		--> cleans the project
mvn clean test    		--> cleans the project and runs all tests
mvn clean package 		--> cleans the project and builds the WAR
mvn tomcat:run	 		--> web run
mvn eclipse:eclipse		--> gen eclipse .project and .classpath config file
mvn jar:jar				--> only build jar file.
mvn javadoc:javadoc     --> gen api files;

mvn dependency:copy-dependencies  拷贝jar
mvn dependency:tree

mvn test -Dtest={测试文件名称}

2014-01-05
    项目元素:nosql
        mongo
        spring-data
        bootRun

    dependencies {
        compile("org.springframework.boot:spring-boot-starter-web")
        compile("org.springframework.data:spring-data-mongodb")
        compile("org.springframework.data:spring-data-rest-webmvc")
        testCompile("junit:junit")
    }


    
        

    