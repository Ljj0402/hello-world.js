# hello-world.js
try
var  five = require("johnny-five");
var board = new five.board();

board.on("ready", function(){
var led= new five.led(13);
led.blink(500);
});
