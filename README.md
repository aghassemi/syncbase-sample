# Quick example using [Syncbase](https://github.com/vanadium/mojo.syncbase) Dart API and Mojo

## Prerequisite
[Mojo](https://github.com/domokit/mojo) must be setup and `$MOJO_DIR` must point to it.

## To run
1- `pub get`
2- `$MOJO_DIR/src/mojo/devtools/common/mojo_run https://mydartapp.mojoapps.io/main.dart --enable-multiprocess --map-origin="https://mydartapp.mojoapps.io/=$PWD" --args-for="https://mydartapp.mojoapps.io/packages/syncbase/mojo_services/linux_amd64/syncbase_server.mojo --v=1 --root-dir=$HOME/syncbasedata"`