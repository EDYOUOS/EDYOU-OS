# EDYOU OS – Open-Source School Linux OS

[![GPL licensed](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/EDYOU-Systems/EDYOU-OS/blob/main/LICENSE)
[![Discussions](https://img.shields.io/badge/discussions-join-blue)](https://github.com/EDYOU-Systems/EDYOU-OS/discussions)
![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fedyou-systems.github.io%2FEDYOUOS%2F)
![Latest Version](https://img.shields.io/badge/version-v1.0.0-red)


**EDYOU OS** is a modern, privacy-focused Linux operating system designed specifically for schools, educational institutions, and students.  
It delivers **freedom, performance, and reliability** without the limitations of traditional operating systems.

Built on **Ubuntu LTS**, EDYOU OS provides a **Windows-like interface** combined with the stability, speed, and openness only Linux can offer.  

For more details, visit the official website: [EDYOU OS Website](https://edyou-systems.github.io/EDYOUOS/)

---

## Key Features

- **Open-Source & Customizable** – fully free to modify and distribute  
- **Privacy-First** – no unnecessary tracking or telemetry  
- **Student-Friendly** – intuitive interface and educational tools included  
- **Lightweight & Fast** – optimized for performance on a wide range of hardware  
- **Stable Base** – built on Ubuntu LTS for long-term support and security  
- **Modern UI** – Windows-like interface for easy adoption in schools

---

## Installation Guide

1. **Download the EDYOU OS ISO** from the main website: [EDYOU OS Downloads](https://edyou-systems.github.io/EDYOUOS/#download)  
2. Create a bootable USB using tools like **Rufus** or **Etcher**  
3. Boot your system from the USB and follow the on-screen instructions  
4. Enjoy a fully open-source, privacy-focused school operating system!

### How to build

If you want to build EDYOU OS from source, use the provided `Makefile`. The common commands are:

```
make                 (or `make current`)   Build current language
make all                                    Build all languages
make fast                                   Build fast config languages
make clean                                  Remove build artifacts
make bootstrap                              Validate environment and dependencies
```

- Build parameters (language, timezone, mirrors, input methods, etc.) are configured in `./src/args.sh`. Edit that file to change the build behavior for each run.
- Built ISO images and related artifacts are written to `./src/dist`.

Run `make fast` to build the fast configuration (now configured for `de_DE` first, then `en_US`).

---

## Community & Support

Join the discussion, ask questions, or provide feedback here:  
[GitHub Discussions](https://github.com/edyou-systems/EDYOU-OS/discussions)

---

## About EDYOU OS

**EDYOU OS** – a next-generation school Linux operating system,  
built on **freedom**, powered by **education**, and focused on **privacy**.  

Perfect for students, teachers, and educational institutions looking for a modern, stable, and open-source computing environment.

---

## License

This project is licensed under the **GNU GENERAL PUBLIC LICENSE** – see the [LICENSE](LICENSE) file for details.
