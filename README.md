# qualia

### what is qualia?
Qualia is a voxel engine designed for first person multiplayer or
singleplayer experiences. It uses a high performance design coupled
with elaborate modding tools to provide endless possibilities.

### how does it work?
It uses concurrent designs to enable opportunitistic multithreaded
game logic. Game ticks are performed over many cores and synchronised
using techniques like RCU. All game assets are provided via the modding
system which is designed from the ground up to allow easier identification 
of multithreading optimisations.

### Planned features
- secure mod loading (all code is sandboxed)
- Open networking API
- Clients retrieve mods from server (clients don't download mods independently)

### progress?
#### Server
- [ ] Mod file specification document
- [ ] Voxel map implementation
- [ ] Benchmarking tools
- [ ] multithreaded workers
#### Client
- [ ] Qualia3D Engine
