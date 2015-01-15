# threejs-x3dloader
X3D Loader for ThreeJS

Doesn't support a lot of things. If you have a feature request or bug report, please feel free to ping me (submit an issue or pull request, as appropriate)

# Usage
```
var loader = new THREE.X3DLoader();
loader.load("/assets/plane.x3d", function(obj) {
	// scene is just a THREE.Scene()
	scene.add(obj);
});
```
Loads /assets/plane.x3d and adds it to the scene.

# Roadmap
- Nothing yet!
