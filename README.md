####Soundness proof and mechanisation:
https://github.com/WasmCert/WasmCert-Isabelle

- [Reduction and type system](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm.thy)
- [Type Checker](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Checker.thy)
- [Interpreter](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Interpreter.thy)

Lemmas:
- [e_type_consts](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Properties_Aux.thy#L1293)
- [store_extension_refl](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Properties_Aux.thy#L1395)
- [inst_typing_store_extension_inv](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Properties_Aux.thy#L1682)
- [frame_typing_store_extension_inv](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Properties_Aux.thy#L1733)
- [types_preserved_e2](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Properties.thy#L1542)
- [preservation](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Soundness.thy#L5)
- [progress_e](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Properties.thy#L2601)
- [progress_e1](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Properties.thy#L2998)
- [progress](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Soundness.thy#L24)
- [type checker correctness](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Checker_Properties.thy#L1630)
- [run_step_return_imp_lfilled](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Interpreter_Properties.thy#L1187)
- [run_step_break_imp_lfilled](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Interpreter_Properties.thy#L1132)
- [run_step_sound](https://github.com/WasmCert/WasmCert-Isabelle/blob/master/WebAssembly/Wasm_Interpreter_Properties.thy#L1769)

CT-Wasm:
https://github.com/PLSysSec/ct-wasm-proofs

Relaxed memory:
https://github.com/conrad-watt/repairing-and-mechanising-the-javascript-relaxed-memory-model

TODO: line numbers for lemmas
