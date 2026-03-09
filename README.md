# js-lib-template
Node in 2025 implemented support for TS, no need for transpilers until release. This project runs ts natively, and exports ts via typescript compiler as JS module.

Used node:test for testing, so both tests and src code are using native nodes TS support. Very fast!

# instructions 

| code            | description                                                               |
|-----------------|---------------------------------------------------------------------------|
| `npm install`   | install dependencies                                                      |
| `nvm use`       | Use node version specified in projects .nvmrc file. (NVM needs installing)|
| `nvm run test`  | run node:test library                                                     |
| `nvm run build` | Build ES module using typescript compiler                                 |