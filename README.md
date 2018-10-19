# Ethereum-AssemblyScript project

The Ethereum-AssemblyScript project (`etherts` for short) aims to develop a robust set of tools to allow the development, testing, and deployment of Ethereum smart contracts using AssemblyScript.

[AssemblyScript](https://github.com/AssemblyScript/assemblyscript) is a subset of TypeScript, a flavor of strictly-typed JavaScript. It compiles directly to "lean, mean WebAssembly modules." It should look and feel quite similar to any JavaScript developer, and is also a natural fit for Wasm since the Wasm runtime is based on the JavaScript runtime. It also uses existing JavaScript tooling such as `npm`.

## Writing smart contracts using AssemblyScript

Etherts uses existing AssemblyScript tooling. Check out the [Getting started](https://github.com/AssemblyScript/assemblyscript#getting-started) section in the main AS repo as a starting point.

An AssemblyScript contract interacts with Ethereum through the use of imported host functions which implement each of the [EEI (Ethereum environment interface) methods](https://github.com/ewasm/design/blob/master/eth_interface.md). Each EEI method is made available as an import from the `ethereum` namespace and has the same method signature as described in the design doc.

## Contributing

The etherts project is maintained by the [Ewasm](https://github.com/ewasm) team. Please see [Ewasm testnet contributing](https://github.com/ewasm/testnet#contributing) for information on joining or contributing to the project.
