![cover](https://github.com/y4aniv/Usoris/blob/main/cover.png?raw=true)
<br>
## Description
Usoris is a JavaScript library to generate usernames with infinite combinations

## Installation
To install Usoris you can :
<br>
&nbsp;&nbsp;&nbsp;&nbsp;• use JsDelivr
```js
<script src="https://cdn.jsdelivr.net/gh/y4aniv/Usoris/Usoris.min.js"></script>
```
&nbsp;&nbsp;&nbsp;&nbsp;• download and import the library
```js
<script src="./Usoris.min.js"></script>
```
## Usage
### Demo
```js
<script src="https://cdn.jsdelivr.net/gh/y4aniv/Usoris/Usoris.min.js"></script>
// <script src="./Usoris.min.js"></script>

<script>
var opt = {
      separator: "_",
      style: "upper"
    }
    const username = Usoris(["colors", "animals"], opt)
    console.log("Your new username " + username) // for example: RED_DOG
</script>
```
### Dictionaries
There are 6 word dictionaries available:
<br>
- ```adjectives``` (377 words)
- ```animals``` (132 words)
- ```colors``` (51 words)
- ```countries``` (202 words)
- ```names``` (1000 words)
- ```numbers``` (999 words)
### Api
```Usoris(dictionaries, options)```
<br>
```dictionaries``` <b>Array</b> containing the names of available word dictionaries
<br>
```options.separator``` Character that separates the different words of the username. By default ```-```
<br>
```options.style``` Username style (```lower```,```upper```, and ```capitalize```). By default ```lower```
<br><br>
## Todo
- Add more word dictionaries
- Add more options
## License
[MIT](https://github.com/y4aniv/Usoris/blob/main/LICENSE)
