# TestLang++

DSL for HTTP API testing (GET/POST/PUT/DELETE) using JFlex + CUP.  
Translates `.test` files into JUnit 5 code that runs via `HttpClient`.

### Run Steps
1. Write tests in `src/test/*.test`
2. Run translator → `GeneratedTests.java`
3. Compile + run with Maven (`mvn test`)
