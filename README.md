<p align=center><img width="400" height="400" alt="JustFetch" src="assets/JustFetch.png"> </p>

# <p align=center>justfetch

A lightweight Bash-based system information tool for Linux, built as my first shell scripting project.

justfetch displays useful information about your system directly in the terminal, with custom colours and a few fun command-line options.

## Features

- Displays operating system information
- Shows kernel version and machine architecture
- Displays the current username
- Shows system uptime
- Displays used and total RAM
- Custom terminal colours
- Help and version options
- JSON output option
- Instagram link option
- Handles invalid command-line arguments

## Usage

Run justfetch from your terminal:

```bash
justfetch
```

### Available options

| Option | Description |
| --- | --- |
| `--help` | Display help information |
| `--version` | Display the current version |
| `--json` | Display JSON output along with System Information for verifications |
| `--logoconfig` | Steps to add your own logo |
| `--logo` | Add your own logo |
| `--follow` | Display my Instagram link |

Unsupported options display an error message.

## Requirements

- Linux
- Bash
- `hostnamectl` (provided by systemd)
- `[ascii-image-converter](https://github.com/TheZoraiz/ascii-image-converter)` (for converting images into ASCII logos)
- Standard Linux utilities, including `uname`, `uptime`, `free`, `cut`, `lshw`, and `awk`
- `pciutils` (for hardware information)

## Installation

Clone this repository:
```bash
git clone https://github.com/SriHariHaran-T/justfetch 
cd justfetch
```

Make the script executable:

```bash
chmod +x justfetch logo information
```

Run it:

```bash
./justfetch
```

To run justfetch from any directory, place the executable in a directory included in your `PATH`, such as `~/.local/bin`.

**Note:** The logo implementation currently supports only Arch Linux. Support for additional Linux distributions will be added in the future!

## Why I built this

justfetch started as a small project to practise Bash scripting on Arch Linux. While building it, I explored variables, command substitution, functions, conditionals, ANSI colours, command-line arguments, pipes, `awk`, and exit codes.

This project is a work in progress, and I plan to improve it as I continue learning Linux and shell scripting.

## Author

**Sri Hari Haran T**

- Instagram: [@heodoestech](https://www.instagram.com/heodoestech/)

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
