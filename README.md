# Lesson-3

## Задание 1
```js
function withoutFormalParameters () {
	console.log(withoutFormalParameters)
	console.log(arguments)
}

withoutFormalParameters (10, false, "google")
```
## Задание 2
```js 
function userInfo () {
    console.log (
        this.registered ? 
            `Дата регистрации: ${this.data.toLocaleString()}` :
            `Незарегистрированный пользователь: ${this.name}`
    );
}

var user1 = {
  name: "Piter", 
  registered: true, 
  data: new Date(), 
  getInfo: userInfo
}

var user2 = {
  name: "NotPiter", 
  registered: false, 
  data: new Date(), 
  getInfo: userInfo
}

user1.getInfo()
user2.getInfo()
```
## Задание 3 (Undefined)
