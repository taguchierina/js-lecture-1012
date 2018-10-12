# テクノロジー（藤原） 10/12課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
var numA = 2;
undefined
var numB = 3;
undefined
var numC = numA + numB;
undefined
console .log(numC);
VM181:1 5
undefined
var numD = numA * numB ;
undefined
console.log(numD);
VM251:1 6
undefined
var numA  = 1;
undefined
var numB = 2;
undefined
var boolC = numA == numB;
undefined
console.log(boolC);
VM367:1 false
undefined
var boolD = numA < numB;
undefined
console.log(boolD);
VM437:1 true
undefined
var numA = 1;
undefined
var numB = "1";
undefined
console.log(numA == numB);
VM536:1 true
undefined
console.log(numA === numB);
VM632:1 false
undefined
var strA = "吾輩は";
undefined
var strB = "猫である";
undefined
var strC = strA + strB;
undefined
console.log(strC);
VM786:1 吾輩は猫である
undefined
console.log(strA === strB);
VM852:1 false
undefined
var numA =1;
undefined
if(numA === 1){
console.log("numAは1です");
}
VM935:2 numAは1です
undefined
if(numA ===2 ){
console.log("numAは"です");}
VM1002:2 Uncaught SyntaxError: missing ) after argument list
if(numA ===2 ){
console.log("numAは"2です");
VM1011:2 Uncaught SyntaxError: Invalid or unexpected token
if(numA === 2 ){
console.log("numAは2です");
}
undefined
var numA = 3;
undefined
if(numA === 1){
console.log("numAは1です");
}
undefined
else if (numA === 2 ){
VM1175:1 Uncaught SyntaxError: Unexpected token else
if(numA === 1){
console.log("numAは1です");
}else if (numA === 2){
console.log("numAは2です");
}else if(numA === 3){
console.log("numAは3です");
}else{
console.log("numAは1,2,3以外です");
}
VM1476:6 numAは3です
undefined
var numA = 3;
undefined
if(numA%2 ==0){
console.log("numAは偶数です");
if(numA >=2){
console.log("numAは2以上です");
}else{
console.log("numAは2未満です");
}
}
undefined
if(numA === 1){
console.log("numAは1です");
}else if (numA === 2){
console.log("numAは2です");
}else if(numA === 3){
console.log("numAは3です");
}else{
console.log("numAは1,2,3以外です");
}else{
VM1698:9 Uncaught SyntaxError: Unexpected token else
if(numA%2 ==0){
console.log("numAは偶数です");
if(numA >=2){
console.log("numAは2以上です");
}else{
console.log("numAは2未満です");
}
}else{
console.log("numAは3以上です");
if(numA >= 3 ){
console.log("numAは3
VM1814:11 Uncaught SyntaxError: Invalid or unexpected token
if(numA%2 ==0){
console.log("numAは偶数です");
if(numA >=2){
console.log("numAは2以上です");
}else{
console.log("numAは2未満です");
}
}else{
console.log("numAは3以上です");
if(numA >= 3 ){
console.log("numAは3以上です");
}else{
console.log("numAは3未満です");
}
}
VM1892:9 numAは3以上です
VM1892:11 numAは3以上です
undefined
for(var i = 0; i < 5; i++){
console.log(i);
}
VM1958:2 0
VM1958:2 1
VM1958:2 2
VM1958:2 3
VM1958:2 4
undefined
var i = 5;
undefined
while(i < 20 ){
console.log(i);
i = i + 3;
}
VM2038:2 5
VM2038:2 8
VM2038:2 11
VM2038:2 14
VM2038:2 17
20
var i = 5;
undefined
do{
console.log(i);
i = i + 3;
}while(i < 20);
VM2126:2 5
VM2126:2 8
VM2126:2 11
VM2126:2 14
VM2126:2 17
20
var j = 30;
undefined
do{
console.log(j);
j = j + 10;
}while(j < 20);
VM2204:2 30
40
for(var i = 1; i < 10; i++){
if( i > 3 ){
break;
}
console.log(i);
}
VM2305:5 1
VM2305:5 2
VM2305:5 3
undefined
for(var i = 1; i < 10; i++){
if( i % 2 == 0){
continue;
}
console.log(i);
}
VM2434:5 1
VM2434:5 3
VM2434:5 5
VM2434:5 7
VM2434:5 9
undefined
function addCalue(a, b){
var c = a + b;
return c;
}
undefined
var d = addValue(1, 2);
VM2542:1 Uncaught ReferenceError: addValue is not defined
at <anonymous>:1:9
(anonymous) @ VM2542:1
console.log(d);
VM2566:1 undefined
undefined
var e = addValue(4, 5);
VM2602:1 Uncaught ReferenceError: addValue is not defined
at <anonymous>:1:9
(anonymous) @ VM2602:1
console.log(e);
VM2626:1 undefined
undefined
function hello(){
console.log("hello");
}
undefined
helli()
VM2689:1 Uncaught ReferenceError: helli is not defined
at <anonymous>:1:1
(anonymous) @ VM2689:1
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
