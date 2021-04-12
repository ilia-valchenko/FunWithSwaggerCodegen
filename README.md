# Instruction
1. Visit https://swagger.io/tools/swagger-codegen/download/
2. For Windows users, you will need to install wget or you can use Invoke-WebRequest in PowerShell (3.0+), e.g. 
`Invoke-WebRequest -OutFile swagger-codegen-cli.jar https://repo1.maven.org/maven2/io/swagger/swagger-codegen-cli/2.4.19/swagger-codegen-cli-2.4.19.jar`
3. Find the `swagger-codegen-cli.jar` on your computer
4. Run the REST API application
5. Open the swagger home page of your application 
6. Navigate to the `/swagger/v1/swagger.json`
7. Run the following command
`java -jar D:\swagger-codegen-cli-3.0.25.jar generate -i http://localhost:62615/swagger/v1/swagger.json -l csharp -o F:\_TEST_API_CLIENTS\test-client-1`