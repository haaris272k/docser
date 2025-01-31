# Docser

Docser is a credential scanning tool similar to gitleaks custom tailored for document git repositories which are prone to have a lot of false positives.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/0xFTW/docser/pulls)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/0xFTW/)


## Installation
```
$ git clone https://github.com/0xFTW/docser

$ cd docser 

$ go install

$ go build
```

### Adding to path 

```
$ sudo mv docser /usr/local/bin/

$ chmod 755 /usr/local/bin/docser
```

### Usage

```
$ docser -h
Usage: docser -d /path/to/directory
  -d string
        Directory to be scanned. (Default is current directory)
  -h    Displays help menu
```

## Plans for future

- [ ] Logic to parse finding and show in similar to gitleaks.
- [ ] Multi threading / concurrency for faster processing.
- [ ] Support for remote git repository.
- [ ] Support for toml files for custom configuration

## Contributing

- Contributions make the open source community such an amazing place to learn, inspire, and create.
- Any contributions you make are truly appreciated.
- Check out our [contribution guidelines](/CONTRIBUTING.md) for more information.

---

## 🛡 License

[Docser](https://github.com/0xFTW/docser) is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---