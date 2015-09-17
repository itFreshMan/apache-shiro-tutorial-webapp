apache-shiro-webapp-tutorial
============================

A step-by-step tutorial showing how to secure a web app with Apache Shiro



 <groupId>org.eclipse.jetty</groupId>
    <artifactId>jetty-maven-plugin</artifactId>
    <version>9.1.0.v20131115</version>
    <configuration>
        <webApp>
            <contextPath>/</contextPath>
        </webApp>
		<httpConnector>
			<port>8081</port>
		</httpConnector>
    </configuration>