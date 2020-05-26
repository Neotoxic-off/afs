# afs
Automated Files Sorter

## Install:
```
git clone https://github.com/Neotoxic-off/afs/
cp afs/afs /usr/bin/
cd <folder to sort>
```

## Usage:
```
cd <folder to sort>
afs
```

## Examples:
#### Before AFS
```
➜  Pictures tree
.
├── 13.jpg
├── test.png
├── issou_test.png
├── main.png
├── main and main_ are same.png
└── trying spaces.jpg
```
#### After AFS
```
➜  Pictures tree
.
├── 13.jpg
├── test
│   └── test_0.png
├── issou
│   └── issou_0.png
├── main
│   ├── main_0.png
│   └── main_1.png
└── tryingspaces
    └── tryingspaces_0.png
```
