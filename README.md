# MeshViewer
OBJ / glTF2 mesh viewer for Windows and macOS.

# Features

- Support Windows and macOS
- Loading OBJ meshes through [syoyo/tinyobjloader](https://github.com/syoyo/tinyobjloader)
- Loading glTF2 meshes through [syoyo/tinygltf](https://github.com/syoyo/tinygltf)
- PBR rendering w/ modified shaders from [KhronosGroup/glTF-WebGL-PBR](https://github.com/KhronosGroup/glTF-WebGL-PBR/tree/master/shaders)

# TODO
- Implement skinning animation
- Implement morph animation
- Support Linux
- Support mobile platforms
- Support Sketchfab download API

# To build this project, you need:

* [Cinder](https://github.com/cinder/Cinder)
* [Cinder-VNM](https://github.com/jing-interactive/Cinder-VNM)
* [Cinder-Nodes](https://github.com/jing-interactive/Cinder-Nodes)

The folder structure should appear like this:

```
Cinder/
    blocks/
        Cinder-VNM/
        Cinder-Nodes/
    include/
MeshViewer/
    assets/
        Cube/
            Cube.gltf
        Amazing-gltf-files/
            scene.gltf
            scene.bin
        Symbolic-link-is-also-supported