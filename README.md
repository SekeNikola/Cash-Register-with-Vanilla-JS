# Cash-Register-with-Vanilla-JS
## Task
Build a cash register that will take price and amount that customer would like to pay and show how much of each currency you have to give to the customer. There are three scenarios.

### First
Customer will pay more than the price and will get a change.

### Second
Customer will pay less than the price and will message that there are insufficient funds in the wallet.

### Third
Customer will pay more then there is in a register and will get a message that there are insufficient funds in register

## Usage
Just download or clone from repro and run HTML or you can change images with your currency. If some of your currency is under 1 ( exp 0.50, 0.25) make sure to calculate to the nearest hundreth deals with precision errors : 
```
change = Math.round(change * 100) / 100;
```

![alt text](https://res.cloudinary.com/sekenikola/image/upload/v1532906474/register_cszrnm.png)
