JSREADME

console.log();  表示する。
A==a A===A  2つは文字形式は問わない　3つは完全一致　！で否定
let 変数（変更できる）　const定数（変更できない）
if(){}else if(){}else{}  もし～でなく～なでもなければ～である等
&& 　～かつ　　||　～または
switch(MOZI){case"A":console.log("あ");break;} コンスとで文字が指定し、ケースで該当するものの文字を実行するbreakで内容を分割する
case以外にもdefaultがありケース以外の際に実行するものを指定できる
ifやelseifによる分岐が多く複雑な場合に書き換えることで読みやすくなる

let number = 1;
while(i>=100){
console.log(number);
number += 1;
}
同じ動作
for(let number = 1;number<=100;number++){console.log(number);}

配列
const fruits=["apple","banana","orange"]
fruits[0]="grape"
console.log(fruits[0]);でGRAPEが実行

for(let i=0;i<3;i++){
console.log(fruits[i]);}　アップル、ばなな、オレンジが表示される
0をfruitslengthにすると配列の要素数を獲得できる

const item = {name:"A",price: 200};
item.price = 300;
プライスが300に変更
