# WELCOME TO THE FACEBOOK ACCOUNT RUSHER

* IMPORTANT NOTE : *This program only can run on Linux (ELF binary)*
*If you are Windows user you can download WSL and install Linux and I recommend to use Debian/Ubuntu/*
*If you are MacOs user you can download Linux via VirtualBox and I recommend to use Debian/Ubuntu/*

* READ THIS CAREFULLY
*There's a bunch of Binary. Each binary has extension like .haswell, .zen1, zen4. It will running stable/optimized based on your CPU architecture*
*If your CPU architecture doesn't match with the file extension you can still run stable but not optimized*
*I recommend you to download the right extension based on your CPU architecture*

* LIST OF ARCHITECTURE

| CPU Brand | CPU Series | Gen Range   | Microarchitecture       | Binary Match        |
|-----------|------------|------------|------------------------|-------------------|
| Intel     | i3         | 1000       | Nehalem                | start.nehalem     |
| Intel     | i3         | 2000       | Sandy Bridge           | start.sandybridge |
| Intel     | i3         | 3000-4000  | Ivy Bridge/Haswell     | start.haswell     |
| Intel     | i3         | 5000-7000  | Skylake/Kaby Lake      | start.skylake     |
| Intel     | i3         | 8000-9000  | Coffee Lake            | start.coffee      |
| Intel     | i3         | 10000-11000| Comet/Rocket Lake      | start.skylake     |
| Intel     | i3         | 12000-13000| Alder/Raptor Lake      | start.alderlake   |
| Intel     | i5         | 1000-13000 | Nehalem → Raptor Lake  | .nehalem/ratpor   |
| Intel     | i7         | 1000-13000 | Nehalem → Raptor Lake  | .nehalem/raptor   |
| Intel     | i9         | 8000-13000 | Coffee → Raptor Lake   | start.raptorlake  |
| AMD       | Ryzen 3    | 1000       | Zen 1                  | start.zen1        |
| AMD       | Ryzen 3    | 2000       | Zen+                   | start.zen2        |
| AMD       | Ryzen 3    | 3000       | Zen 2                  | start.zen2        |
| AMD       | Ryzen 3    | 4000       | Zen 3                  | start.zen3        |
| AMD       | Ryzen 3    | 5000       | Zen 4                  | start.zen4        |
| AMD       | Ryzen 5    | 1000-5000  | Zen 1 → Zen 4          | .zen1/zen2/zen3/zen4|
| AMD       | Ryzen 7    | 1000-5000  | Zen 1 → Zen 4          | .zen1/zen2/zen3/zen4|
| AMD       | Ryzen 9    | 3000-5000  | Zen 2 → Zen 4          | .zen1/zen2/zen3/zen4|

# download and usage
*assume if your CPU architecture is haswell*
```bash
wget https://raw.githubusercontent.com/undergroundsLabos/FB-rusher/master/start.haswell

./start.haswell <yourgmail@gmail.com>
```

# IMPORTANT MESSAGE
Please use it wisely, don't harm others, and don't sell it freely. All of this is under the stated software license.
