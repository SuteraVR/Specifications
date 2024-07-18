# ワールド

現在ワールドは静的なオブジェクトに限定されています

```yaml
metadata:
  type: sutera-scene@0.1.0
  name: sutera world
  version: 0.2.0
specs:
  spawn_point:
      x:
      y:
      z:
  border: # 越えたらリスポーン
      x_min:
      x_max:
      y_min:
      y_max:
      z_min:
      z_max:
  objects: # 配列
  - name: sofa
    model:
      type: gltf
      path: models/sofa.gltf
    material:
      type: sbsar
      path: materials/sofa.sbsar
    location:
        x:
        y:
        z:
    rotation:
        x:
        y:
        z:
        w:
    scale:
        x:
        y:
        z:
    physics:
      colliders:
      - type: box　　　
      gravity:
        mass: 5000
  - name: ball # 最小構成
    model:
       type: sphere # 基本図形はgltfなしで可能
    material: 
       type: diffuse_bsdf # 単色もファイルなしで可能
       color: 0x6833cf
```
