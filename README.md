## Clone

```
git clone --recurcive https://github.com/danissomo/remesher-gripper.git
```

## Apply patch
```
cd point2mesh
git apply ../point2mesh.patch
```

## Manifold 

install [this](https://github.com/hjwdzh/Manifold) and change [options.py](point2mesh/options.py)

```
6| MANIFOLD_DIR = r'/home/dan/Manifold/build' # path to manifold software (https://github.com/hjwdzh/Manifold)
```

[point2mesh README](point2mesh/README.md)