# gogo

## 🚀 Quick Start

### Install zipzod using the Go toolchain

```bash
go install github.com/xyz/zipzod@latest
```

## Run zipzod with an input directory and an output file

```bash
zipzod -i ./input -o ./output.zip
```

## 📖 Usage

Available flags:

* `-i` - The input file or directory
* `-o` - The output file or directory
* `-v` - Verbose output
* `-h` - Show help
* `-p` - The number of parallel workers to use (default 4)
* `-d` - The maximum depth to traverse (default 1)
* `-f` - The file extensions to include (default .txt, .md)

## Examples

Unzip a file

```bash
zipzod -i ./input.zip -o ./output
```

Zip with a different number of workers

```bash
zipzod -i ./input -o ./output.zip -p 8
```

## 🤝 Contributing

### Clone the repo

```bash
git clone https://github.com/xyz/zipzod@latest
cd zipzod
```

### Build the project

```bash
go build
```

### Run the project

```bash
./zipzod -i ./input -o ./output.zip
```

### Run the tests

```bash
go test ./...
```

### Submit a pull request

If you'd like to contribute, please fork the repository and open a pull request to the `main` branch.
