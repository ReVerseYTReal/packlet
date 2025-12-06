# Packlet

**Tiny, Mighty, Installed.**  
Your personal open-source package manager — install, manage, and share packages easily.

---

## Features
- Install packages from a local or remote registry  
- List installed packages  
- Remove packages  
- Open-source and community-friendly  

---

## Installation
1. Clone the repo:
```bash
git clone https://github.com/<your-username>/packlet.git
cd packlet
````

2. Install dependencies (if any, optional for v1):

```bash
npm install
```

3. Link globally to use `packlet` command anywhere:

```bash
npm link
```

4. Verify:

```bash
packlet --help
```

---

## Usage

### Install a package

```bash
packlet install <package-name>
```

### List installed packages

```bash
packlet list
```

### Remove a package

```bash
packlet remove <package-name>
```

---

## Registry

* Packages are listed in `packlet-registry.json`
* You can add your own packages by editing the JSON file

Example:

```json
{
  "hello-world": { "version": "1.0.0", "url": "https://example.com/hello-world.zip" },
  "magic-tool": { "version": "2.0.0", "url": "https://example.com/magic-tool.zip" }
}
```

---

## License

Packlet is released under the [CC BY-NC-SA 4.0 License](LICENSE).

© 2025 ReVerse — You are free to use and modify Packlet, but you **cannot sell it**, and derivatives must remain under the sam
