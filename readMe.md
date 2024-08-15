lesson 6
// Как сократить код:

1. if (res.value.length < 7){
    res.value += digit
}

res.value +=res.value.length < 7 ?digit : ""

2. if (clearFlag || res.value == "0"){
    clearFlag = false
    res.value =""
}

// console.log(event)
// console.log(event.target) 
// console.log(event.target.value)


// Игра крестики нолики
letXturn = false
functiion play(){
    if (Xturn) {
        event.target.innerHTML ="x"
    }
    else {
        event.target.innerHTML ="0"
    }
    XTurn = !Xturn
}

как сократить код:
letXturn = false
functiion play(){
        event.target.innerHTML = XTurn ? "x" : "0"
        XTurn = !Xturn
}

// event.target.tagName === 'BUTTON'
//const randomColor = '#' + Math.floor(Math.random() * 16777215).toString(16);
//