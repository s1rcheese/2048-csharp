# 2048 [![AppVeyor](https://img.shields.io/appveyor/ci/s1rcheese/2048/master.svg?maxAge=60)](https://ci.appveyor.com/project/s1rcheese/2048)

My take the 2048 game in C#. Console version. The implementation is pretty customizable. You can tweak the size of the canvas and the probabilities of 2s and 4s, etc. Just compile and run from console. Should work with both .NET and Mono.

Here's how it looks like: ![screenshot](doc/screenshot.png "Screenshot")

# Building and Running
First clone the repo:
```shell
git clone https://github.com/s1rcheese/2048.git
cd 2048
```

To update the source code:
```shell
git pull
```

## Building
If you only want to build the source code:
```shell
dotnet build
```

## Running
If you want to run the project via your command line:
```shell
dotnet run --project 2048
```

# Stuff to do
~~Add a black background to the numbers so that other command lines (that is not the one Windows comes with)(ex. Ubuntu Terminal) can see the numbers better.
~~
