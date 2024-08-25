recursively compile all of the code in the directory in linux

```
find ./ -type f -name "*.java" -exec javac -cp ./ -d ./out/ '{}' +
```

remember to cd into ./out before running the code otherwise you'll get 
```
Caused by: java.lang.NoClassDefFoundError
```

- Always a good practice to keep your members private and expose a getter/setter pair to interact with values
- 