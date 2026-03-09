# js-lib-template
Node in 2025 implemented support for TS, no need for compilers. This project runs ts natively, and exports ts as an untranspiled library for use in other TS projects. Not recommended for use as a public NPM library as it would need to be transpiled as a es module or common js module. I know how to configure my downstream projects to use native TS, so this does not bother me.

# instructions 

| code       | description                                                               |
|------------|---------------------------------------------------------------------------|
| `nvm use`  | Use node version specified in projects .nvmrc file. (NVM needs installing)|