# Template for simple projects using C++ and CMake

* `lib`: folder containing a library, with sublibraries `sublib1` and `sublib1`
* `app`: folder containing apps that use the library, `subapp1` and `subapp2`
* `test`: unit tests, generates executable test file using [Catch2](https://github.com/catchorg/Catch2)

To compile:

```
mkdir build
cd build
cmake ..
make
cd ..
```

To run:

```
./build/app/subapp1
./build/app/subapp2
```


Other scripts:

* `compile.sh`: run commands to compile
* `clean.sh`: delete all files in build folder
* `run_tests.sh`: run unit tests