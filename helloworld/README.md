## Code Refactroing and TDD in Hello World
1. The hello.go program contains the base code for our hello world program,  which greets user in different languages based on selection of langauage and defaults to English. 
2. We have started with simple `fmt.Println("Hello, world")`
3. Then we have added the code refactoring for our language input in `func Hello` with block of if-else statements. 
4. Then the block of if-else statments converted to switch case refactored to `func greetingPrefix`.
5. In our test cases for each of the language input we have created seprate test cases.

## How to Run
1. To execute the hello.go : `go run hello.go`
2. To execiute the test cases: `go test`