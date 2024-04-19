Please use this command to generate the code coverage as this command excludes program.cs file that cannot be covered by test cases.

**Command : dotnet test /p:CollectCoverage=true /p:CoverletOutputFormat=lcov /p:CoverletOutput=./TestResults/lcov.info /p:ExcludeByFile=**/program.cs**

**Coverage Report Image**


 ![test_result](https://github.com/devansh-kapoor/dotNet_Assignment_unitTest/assets/94031829/d3bacae8-6677-4acc-87ab-c482de7c624c)
