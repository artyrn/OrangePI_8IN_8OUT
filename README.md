# OrangePI_8IN_8OUT
OrangePI 8 входов и 8 выходов используется node red.

Для входов и выходов используется микросхема MCP23017 
подключенная к OrangePI по I2C. 

Входы имеют опторозвязку, исползуются счетверенные оптроны TLP292-4. 
Конвертор уровней собран на TXS0108E.

В palette node-red-contrib-mcp23017chip добавил возможность выбора 
i2c0 или i2c1 по умолчанию выбирался i2c1
