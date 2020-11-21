# moodle_model
project to store dto 

release - released artifacts <br />
main - staging & test  
development - integration branch
feature_branch - create branch to develop feature, after work is done - merge to development

to download artifact add repository with following credentials   
1. in ./m2/settings
<server>
	<id>max-java-git</id>
	<username>max-java</username>
	<password>04ae8b08dfd8cb64f1c0db68cbe603473cde8e31</password>
</server>

2. in pom.xml add 
    <dependencies>
        <dependency>
            <groupId>by.jrr</groupId>
            <artifactId>moodle-model</artifactId>
            <version>1.0.4-SNAPSHOT</version>
        </dependency>
    </dependencies>

    <repositories>
        <repository>
            <id>max-java-git</id>
            <url>https://maven.pkg.github.com/max-java/moodle_model</url>
        </repository>
    </repositories>
    
