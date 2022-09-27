# sonar 9.5 -example With SpringBoot 

# Plugins:

<!--
			<plugin>
				<groupId>org.jacoco</groupId>
				<artifactId>jacoco-maven-plugin</artifactId>
				<version>0.8.5</version>
				<executions>
					<execution>
						<id>prepare-agent</id>
						<goals>
							<goal>prepare-agent</goal>
						</goals>
					</execution>
					<execution>
						<id>report</id>
						<goals>
							<goal>report</goal>
						</goals>
					</execution>
				</executions>
			</plugin>
			-->
# jacoco cmd:
clean org.jacoco:jacoco-maven-plugin:prepare-agent install

# sonar cmd:
mvn sonar:sonar 
## sonar cmd with Token:
sonar:sonar -Dsonar.login=squ_93153813dbe94595e31c738352131cefc752492b
##
sonar:sonar -Pcoverage -Dsonar.login=squ_93153813dbe94595e31c738352131cefc752492b
