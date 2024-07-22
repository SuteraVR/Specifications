# ワールド

sutera VR にアップロードするワールドの情報を記述します。
現在ワールドは静的なオブジェクトに限定されています。

## 情報

### medatdata.type

yaml の種類を記述します。

### medatdata.name

ワールドの名前を記述します。

### medatdata.version

ワールドのバージョンを記述します。

## スペック

### specs.spawn_point

ユーザーがワールドに入場した際のスポーンポイントを記述します。

### specs.border

ワールドの境界を記述します。ここで設定された値を越えた際、ユーザーはリスポーンします。

### specs.objects

ワールドを構成するオブジェクトの情報を記述します。

#### specs.objects.name

オブジェクトの名前を記述します。

##### specs.objects.model.type

オブジェクトの形式を記述します。

##### specs.objects.model.path

オブジェクトが保存されているパスを記述します。

#### specs.objects.material

オブジェクトが利用するマテリアルの情報を記述します。

##### specs.objects.material.type

マテリアルの形式を記述します。

##### specs.objects.material.path

マテリアルが保存されているパスを記述します。

#### specs.objects.location

オブジェクトを配置する場所を記述します。

#### specs.objects.rotation

オブジェクトを配置する際の回転情報を記述します。

#### specs.objects.scale

オブジェクトを配置する際のスケーリング情報を記述します。

#### specs.objects.physics

オブジェクトの物理情報を記述します。

##### specs.objects.colliders

オブジェクトのコライダー情報を記述します。

##### specs.objects.gravity

オブジェクトの重力情報を記述します。
