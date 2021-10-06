# we test for our teamwork 

## test
```
  export function initial(clist:any[]){
    clist.pop()
    return clist
  }

  export function takeRight(array:any[], n:number=1){
    const result = []
    var x = array.length
    var i = x - n;
    if(i < 0) i = 0;
    for(i; i < x; i++){
        if(i < x) result.push(array[i]) 
    }
    return result
}
```

## src
```
  export function initial(clist:any[]){
    clist.pop()
    return clist
  }

  export function takeRight(array:any[], n:number=1){
    const result = []
    var x = array.length
    var i = x - n;
    if(i < 0) i = 0;
    for(i; i < x; i++){
        if(i < x) result.push(array[i]) 
    }
    return result
}
  
```

## result 
```
PS D:\Vscode\sa110\sa110a\note\W3\teamwork> deno test BDD/test
running 2 tests from file:///D:/Vscode/sa110/sa110a/note/W3/teamwork/BDD/test/initial_test.ts
test initial ... ok (23ms)
test takeRight ... ok (15ms)

test result: ok. 2 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out (108ms)
```