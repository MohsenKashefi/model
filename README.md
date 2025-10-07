# 3D Model Collection

A curated collection of 3D models created with **Blender** and exported in GLB format for use in web applications, game development, AR/VR experiences, and 3D visualization projects.

## 📁 Models Included

This repository contains the following 3D models:

- **nike.glb** - Nike brand/model
- **Person.glb** - Human character model
- **tv.glb** - Television model
- **videowall1.glb** - Video wall display model

## 🎯 Usage

These GLB files can be used in various applications:

- **Web Development**: Load into Three.js, Babylon.js, or other WebGL frameworks
- **Game Development**: Import into Unity, Unreal Engine, or other game engines
- **3D Visualization**: Use in Blender, Maya, or other 3D software
- **AR Applications**: Perfect for Augmented Reality experiences on mobile devices
- **VR Applications**: Ideal for Virtual Reality environments and immersive experiences
- **3D Printing**: Convert to STL format for 3D printing applications
- **Architectural Visualization**: Use in CAD software and architectural presentations
- **Educational Content**: Great for interactive learning experiences

## 🚀 Getting Started

### For Web Development

```javascript
// Example with Three.js
import { GLTFLoader } from 'three/examples/jsm/loaders/GLTFLoader.js';

const loader = new GLTFLoader();
loader.load('./nike.glb', (gltf) => {
    scene.add(gltf.scene);
});
```

### For Unity

1. Download the desired GLB file
2. Import into your Unity project
3. The model will be automatically converted to Unity's format

### For AR Applications

```javascript
// Example with AR.js and Three.js
import { GLTFLoader } from 'three/examples/jsm/loaders/GLTFLoader.js';

const loader = new GLTFLoader();
loader.load('./Person.glb', (gltf) => {
    // Position model in AR space
    gltf.scene.position.set(0, 0, -1);
    arScene.add(gltf.scene);
});
```

### For Blender

1. Open Blender
2. Go to File > Import > glTF 2.0 (.glb/.gltf)
3. Select your desired GLB file
4. The model will be imported with materials and textures intact

## 📋 File Format

All models are provided in **GLB format** (GL Transmission Format Binary), which is:
- A compact, binary format for 3D scenes and models
- Self-contained (includes geometry, materials, textures, and animations)
- Optimized for web delivery
- Compatible with most modern 3D engines and viewers

## 🔧 Technical Details

- **Format**: GLB (GL Transmission Format Binary)
- **Created with**: Blender 3D modeling software
- **License**: Check individual model files for licensing information
- **Optimization**: Models are optimized for web use with reasonable file sizes
- **AR/VR Ready**: All models are compatible with AR frameworks like AR.js, ARCore, and ARKit
- **Mobile Friendly**: Optimized for mobile AR applications

## 📦 Download

You can download individual models or clone the entire repository:

```bash
git clone https://github.com/MohsenKashefi/model.git
```

## 🤝 Contributing

Contributions are welcome! If you have 3D models to add:

1. Fork the repository
2. Add your GLB files
3. Update this README with model descriptions
4. Submit a pull request

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What this means for you:

✅ **Commercial Use** - You can use these models in commercial projects  
✅ **Modification** - You can modify and adapt the models  
✅ **Distribution** - You can share and redistribute the models  
✅ **Private Use** - You can use them in private projects  
✅ **Attribution** - You must include the original license and copyright notice  

### Attribution

When using these models, please include attribution in your project:

```
3D Models by MohsenKashefi
https://github.com/MohsenKashefi/model
Licensed under MIT License
```

### Individual Model Rights

Some models may have additional restrictions or requirements. Please check individual model files for specific licensing information.

## 🔗 Related Links

- [GLB Format Specification](https://github.com/KhronosGroup/glTF/tree/master/specification/2.0)
- [Three.js GLTFLoader Documentation](https://threejs.org/docs/#examples/en/loaders/GLTFLoader)
- [Blender GLB Export Guide](https://docs.blender.org/manual/en/latest/addons/import_export/scene_gltf2.html)
- [AR.js Documentation](https://ar-js-org.github.io/AR.js-Docs/)
- [WebXR AR Tutorial](https://developers.google.com/ar/develop/web/quickstart)
- [Blender Official Website](https://www.blender.org/)

## 📞 Contact

For questions or support, please open an issue on this repository.

---

*Last updated: $(date)*
