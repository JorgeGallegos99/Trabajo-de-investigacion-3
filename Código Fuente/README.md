**ENTRADA DE DATOS**

var Gpio = require("onoff").Gpio; //paquete para controlar los pines

// Definicion de Variables

var led = new Gpio(4, "out");

var button = new Gpio(22, "in");

//estructura while

while(button.readSync() === 0) {

    led.writeSync(1);
    
    sleep(1000);
    
    led.writeSync(0);
    
}

**SALIDA DE DATOS**

var Gpio = require("onoff").Gpio;

var ledRed = new Gpio(4, "out");

var ledYellow = new Gpio(23,"out");

var ledGreen = new Gpio(24,"out");

for(i = 0; i < 2; i++) {

    console.log("Start " + (i+1))
    
    ledRed.writeSync(1);
    
    sleep(3000);
    
    ledRed.writeSync(0);
    
    ledYellow.writeSync(1);
    
    sleep(3000);
    
    ledYellow.writeSync(0);
    
    ledGreen.writeSync(1);
    
    sleep(3000);
    
    
    ledGreen.writeSync(0);

}

for(j = 0; j < 5; j++){
    
    console.log("Start " + (j + 1));
    
    ledYellow.writeSync(1);
    
    sleep(1000);
    
    ledYellow.writeSync(0);
    
    sleep(1000);

}


