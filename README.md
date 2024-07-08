# Scripts for Server Benchmarking

This repository contains several scripts designed to benchmark server performance and download speeds on Dedicated Servers/VPS.

## Scripts Included:

### 1. Server Info Script
- **Description:** Provides detailed information about the server configuration.
- **Usage:** Run the script to display server specifications and configuration details.
```
wget -q https://cdn.ai.in/sh/sbtest.sh -O sbtest.sh && sh sbtest.sh -si
```

### 2. PHP Benchmark Script
- **Description:** Benchmarks PHP performance on the server.
- **Usage:** Execute the script to measure PHP execution time and other performance metrics.
```
wget -q https://cdn.ai.in/sh/sbtest.sh -O sbtest.sh && sh sbtest.sh -pb
```

- Test PHP efficiency with 1000x Difficulty load

```
wget -q https://cdn.ai.in/sh/sbtest.sh -O sbtest.sh && sh sbtest.sh -php -d=1000
```

### 3. Dedicated Server/VPS Download Speed Benchmark Script
- **Description:** Measures download speed from the server.
- **Usage:** Run the script to test and report the download speed from the server.
```
wget -q https://cdn.ai.in/sh/sbtest.sh -O sbtest.sh && sh sbtest.sh -ds
```

## How to Use

Copy and paste the command below in the command line:

```
wget -q https://cdn.ai.in/sh/sbtest.sh -O sbtest.sh && sh sbtest.sh
```
OR
```
curl -s -o sbtest.sh https://cdn.ai.in/sh/sbtest.sh && sh sbtest.sh
```

## Authors

- [@kevinpareek](https://www.github.com/kevinpareek)

## License

[MIT](https://choosealicense.com/licenses/mit/)