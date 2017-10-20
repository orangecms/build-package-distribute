class: center, middle

# Build 🏗, Package 📦, Distribute 🎉

Daniel Maslowski |
![Twitter](img/twitter.png) [@orangecms](https://twitter.com/orangecms) |
![GitHub](img/github.png) [orangecms](https://github.com/orangecms)

---

# ToC

1. Introduction
2. Distribution
3. Packaging
4. Building

---

class: center, middle

## Introduction

---

### Software

--

💻 +🕹  = ❤

--

![Computer Game](img/pc-game.jpg)

--

💻 + 📦 = 💕


___
[`https://www.wikihow.com/Find-a-Lost-Computer-Game`](https://www.wikihow.com/Find-a-Lost-Computer-Game#/Image:Find-a-Lost-Computer-Game-Step-4.jpg)

---

### Package Management

--

- installation


--

- configuration


--

- tracking / database


--

- upgrading


--

- removal

---

class: center, middle

## Distribution

---

### OS Distributions
___

#### ![FreeBSD](img/freebsd.png) FreeBSD (freezes, except TrueOS)
  1. Binary repository
  2. Ports tree

--

#### ![Arch Linux](img/arch_linux.png) Arch Linux (rolling release GNU/Linux)
  1. Binary repositories
  2. AUR

--

#### ![Gentoo](img/gentoo.png) Gentoo (rolling release meta-distro)
  1. Portage
  2. Overlays

---

### CLI Tools
___

#### ![FreeBSD](img/freebsd.png)
  -  `pkg`

--

#### ![Arch Linux](img/arch_linux.png)
  - `pacman`

--

#### ![Gentoo](img/gentoo.png)
  - `emerge`

---

### Synchronization
___

#### ![FreeBSD](img/freebsd.png)
  - `pkg update`
  - [`portsnap fetch update`](https://www.freebsd.org/doc/handbook/ports-using.html)

--

#### ![Arch Linux](img/arch_linux.png)
  - `pacman -Sy`

--

#### ![Gentoo](img/gentoo.png) 
  - `emerge --sync`
  - `layman -S`

---

### Automated Installation
___

#### ![FreeBSD](img/freebsd.png)
  - `pkg install package-name`

--

#### ![Arch Linux](img/arch_linux.png)
  - `pacman -S package-name`

--

#### ![Gentoo](img/gentoo.png) 
  - `emerge package-name`

---

### Manual Installation
___

#### ![FreeBSD](img/freebsd.png)
  - `make install`

--

#### ![Arch Linux](img/arch_linux.png)
  - [`makepkg`](https://wiki.archlinux.org/index.php/Makepkg)

--

#### ![Gentoo](img/gentoo.png) 
  - `ebuild package-name-1.2.3.ebuild merge`

---

class: center, middle

## Packaging

---

### Steps

- fetch / download sources
- verify integrity
- calculate version
- unpack
- prepare / patch
- compile
- test
- archive
- install

---

### Porting and Portability

--

- POSIX


--

- configure scripts
- autotools, `cmake`, `qmake`

--


- `diff` and `patch`
- `sed`, `awk`, `grep`

--


- platform-specific files
  - udev rules
  - init system files

---

### Metadata

- name
- version
- license
- dependencies

---

### Dependencies

- shared libraries, runtimes, static resources (assets)
- versions, releases
- tree
  - resolution
  - SAT-solver

---

class: center, middle

## Building

---

### General Tools

- module system
- taskrunner
- compiler
- linker

---

### Specific Dependency Managers

--

- JavaScript
  - npm
  - bower

--


- Ruby
  - gem
  - bundler

--


- Python
  - pip

--


- Java
  - maven

---

class: center, middle
# Thanks, that's it! 😸
