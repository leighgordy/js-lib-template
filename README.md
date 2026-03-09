# js-lib-template
Node in 2025 implemented support for TS, no need for compilers. This project runs ts natively, and exports ts as an untranspiled library for use in other TS projects. Not recommended for use as a public NPM library as it would need to be transpiled to js.

Also used node:test for testing. So both tests and src code are using TS out of the box no transpiler. Very fast!

# instructions 

| code            | description                                                               |
|-----------------|---------------------------------------------------------------------------|
| `npm install`   | install dependencies                                                      |
| `nvm use`       | Use node version specified in projects .nvmrc file. (NVM needs installing)|
| `nvm run test`  | run node:test library                                                     |
| `nvm run build` | Build ES module using typescript compiler                                 |