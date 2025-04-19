# [GPUs Unleashed! Make Your Games More Powerful With wasi-gfx](https://2025.wasm.io/sessions/gpus-unleashed-make-your-games-more-powerful-with-wasi-gfx/)
Wasm I/O 2025 Presentation and demo materials

The slides have been [uploaded here](https://github.com/renderlet/wasm-io-25/blob/main/wasmio-25.pdf).

The recording will be uploaded shortly to YouTube and the link will be updated here.

For more information on wasi-gfx, [see here](https://github.com/wasi-gfx/.github/blob/main/profile/README.md).

## Examples
To run the Bevy (or AI) demos, please see the notes [from WasmCon 2024 here](https://github.com/wasi-gfx/.github/blob/main/wasmcon-24.md).

To run the 3D buildings / lighting demo, please contact info@renderlet.com.

To run the Plugin / Adria example:
1. Use this [fork/branch](https://github.com/MendyBerger/Adria-DX12/tree/camera-position) of Adria.
2. Build the plugin guest from the [branch here](https://github.com/renderlet/glb-to-webgpu/blob/renderlet-plugin-runtime-camera-pos).
3. Use the prebuilt [plugin runtime here](https://rlt-playground.azureedge.net/public/onnx_basic_test_component.wasm).
4. Replace any paths in main.cpp in Adria to the plugin runtime dll and plugin guest wasm to your paths (and any necessary .h includes).
5. Note the plugin runtime is source-available. Please contact info@renderlet.com for more information.

Happy rendering!
