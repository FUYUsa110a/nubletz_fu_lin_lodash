# test for initial and takeright lodash
>* 成員:傅于軒、魏美亞、林妍汝
* 作品: initial.ts,takeright.ts
* 魏美亞、林妍汝給pull request，傅于軒接收

* 先進行兩個專案的測試
```
s1108@DESKTOP-IJI9NA5 MINGW64 /d/Vscode/sa110/deno/nubletz_fu_lin_lodash/test (master)
$ deno test
Check file:///D:/Vscode/sa110/deno/nubletz_fu_lin_lodash/test/initial_test.ts
running 2 tests from file:///D:/Vscode/sa110/deno/nubletz_fu_lin_lodash/test/initial_test.ts
test initial ... ok (21ms)
test takeRight ... ok (16ms)

test result: ok. 2 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out (102ms)
```
## example
```
import * as _ from 'https://deno.land/x/nubletz_fu_lin_lodash/mod.ts'
//import * as _ from "../mod.ts";
console.log("_.initial([1, 2, 3])",_.initial([1, 2, 3]))
```

## result
```
PS D:\Vscode\sa110\deno\nubletz_fu_lin_lodash\example> deno run ex1.ts
Check file:///D:/Vscode/sa110/deno/nubletz_fu_lin_lodash/example/ex1.ts
_.initial([1, 2, 3]) [ 1, 2 ]
```

