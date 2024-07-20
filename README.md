# macserial-online
WebAssembly port of MacSerial from OpenCorePkg.

Source for the live site is provided in the staging branch.

Build: `emcc macserial.c -o macserial.js -s EXPORTED_RUNTIME_METHODS=['callMain']`
