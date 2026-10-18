English · [한국어](README.ko.md)

# ComfyUI-CustomNodes

This repository currently contains RemoteWorker. Additional ComfyUI custom nodes will be added as they are ready.

Each project is maintained in its own repository and linked here as a Git submodule.

| Project | Purpose |
| --- | --- |
| [RemoteWorker](https://github.com/pollux-o4/RemoteWorker) | Transfer conditioning between ComfyUI runtimes and use remote encoding and prompt generation. |

## Clone the collection

```sh
git clone --recurse-submodules https://github.com/pollux-o4/ComfyUI-CustomNodes.git
```

For an existing checkout:

```sh
git submodule update --init --recursive
```

## Install a project

To install RemoteWorker:

```sh
cd /path/to/ComfyUI/custom_nodes
git clone https://github.com/pollux-o4/RemoteWorker.git
```

## Update pinned versions

```sh
git submodule update --remote RemoteWorker
```

This fetches RemoteWorker's `user` branch. Commit the submodule pointer after checking the update.
