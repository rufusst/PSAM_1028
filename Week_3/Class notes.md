####The first thing we did:

```ruby
//chapter 3
//list of things
var myfruitarray = ["","",""]
undefined
myfruitarray
(3) ["", "", ""]0: ""1: ""2: ""length: 3__proto__: Array(0)
var myfruitarray = ["apple","orange","carrot"]
undefined
myfruitarray
(3) ["apple", "orange", "carrot"]0: "apple"1: "orange"2: "carrot"length: 3__proto__: Array(0)
myfruitarray[0]
"apple"
myfruitarray[1]
"orange"
myfruitarray[2]
"carrot"
myfruitarray
(3) ["apple", "orange", "carrot"]
(anonymous) @ VM590:1
myfruitarray[0] = "pineapple"
"pineapple"
myfruitarray[0]
"pineapple"
myfruitarray[2] = "last fruit"
"last fruit"
myfruitarray[6]=grape
VM645:1 Uncaught ReferenceError: grape is not defined
    at <anonymous>:1:17
(anonymous) @ VM645:1
myfruitarray[6]= "grape"
"grape"
myfruitarray
(7) ["pineapple", "orange", "last fruit", empty × 3, "grape"]
myfruitarray.length
7
myfruitarray.length - 1
6
var lastelementinarray = myfruitarray[myfruitarray.length-1]
undefined
lastelementinarray
"grape"
var mynestedarrayoffruit = []
undefined
var mynestedarrayoffruit = ["","",""]]
VM1017:1 Uncaught SyntaxError: Unexpected token ]
var mynestedarrayoffruit = ["","",""]
undefined
var mynestedarrayoffruit = [["","",""],["","",""],["","",""]]
undefined
mynestedarrayoffruit
(3) [Array(3), Array(3), Array(3)]0: (3) ["", "", ""]1: (3) ["", "", ""]2: (3) ["", "", ""]length: 3__proto__: Array(0)
mynestedarrayoffruit[1][1] = "X"
"X"
mynestedarrayoffruit
(3) [Array(3), Array(3), Array(3)]0: (3) ["", "", ""]1: (3) ["", "X", ""]2: (3) ["", "", ""]length: 3__proto__: Array(0)
mynestedarrayoffruit[0][2] = "O"
"O"
mynestedarrayoffruit
(3) [Array(3), Array(3), Array(3)]0: (3) ["", "", "O"]1: (3) ["", "X", ""]2: (3) ["", "", ""]length: 3__proto__: Array(0)
mynestedarrayoffruit = [["apple","red","worm"],["bannan","yellow","bruise"],["cucumber","green","freezer burn"]]
(3) [Array(3), Array(3), Array(3)]0: (3) ["apple", "red", "worm"]1: (3) ["bannan", "yellow", "bruise"]2: (3) ["cucumber", "green", "freezer burn"]length: 3__proto__: Array(0)

```

####Then we did this:

```ruby

// .push adds elements to end of array
undefined
var mysimplefruitarray = []
undefined
mysimplefruitarray.push()
0
mysimplefruitarray.push("apple")
1
mysimplefruitarray
["apple"]
mysimplefruitarray.push("bannan")
2
mysimplefruitarray.push("bannan")
mysimplefruitarray.push("carrot")
mysimplefruitarray.push("kiwi")
mysimplefruitarray.push("orange")
6
mysimplefruitarray
(6) ["apple", "bannan", "bannan", "carrot", "kiwi", "orange"]
// Add element to front, shift it all down
undefined
var colourarray = ["red","green","blue"]
colourarray.unshift("yellow")
4
colourarray
(4) ["yellow", "red", "green", "blue"]
colourarray.unshift("purple")
5
// .po removing elements from end of an array
undefined
// .pop removing elements from end of an array
undefined
var colourarray = ["red","green","blue"]
undefined
colourarray.pop()
"blue"
colourarray
(2) ["red", "green"]
colourarray.pop()
"green"
colourarray.pop()
"red"
colourarray
[]
colourarray.puh("grey")
VM1695:1 Uncaught TypeError: colourarray.puh is not a function
    at <anonymous>:1:13
(anonymous) @ VM1695:1
colourarray.push("grey")
1
colourarray.push("yellow")
2

```
