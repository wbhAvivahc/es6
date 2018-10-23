map
===

`//map
//与普通的对象不同的是在于，对象的key是任意的类型
var map1 = new Map();

var key1 = 'abc',
    key2 = function(){},
    key3 = {};

map1.set(key1,'value1')
map1.set(key2,'value2')
map1.set(key3,'value3')

console.log(map1,'map1')

map1.get()

`