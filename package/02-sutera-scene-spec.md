# シーン

Sutera VR にアップロードするシーンの情報を記述します。
現在シーンは静的なオブジェクトに限定されています。

## 情報

### medatdata.id

ワールドの ID を記述します。

### medatdata.type

ワールドのタイプを記述します。

### medatdata.name

ワールドの名前を記述します。この項目は任意の値を設定することが出来ます。

### medatdata.version

ワールドのバージョンを記述します。

## スペック

### specs.spawn_point

ユーザーがワールドに入場した際のスポーンポイントを記述します。

### specs.border

ワールドの境界を記述します。ここで設定された値を越えた際、ユーザーはリスポーンします。

### specs.objects

ワールドを構成するオブジェクトの情報を記述します。

#### specs.objects.id

オブジェクトの ID を記述します。

#### specs.objects.name

オブジェクトの名前を記述します。

##### specs.objects.path

オブジェクトが保存されているパスを記述します。

#### specs.objects.location

オブジェクトを配置する場所を記述します。

#### specs.objects.rotation

オブジェクトを配置する際の回転情報を記述します。

#### specs.objects.scale

オブジェクトを配置する際のスケーリング情報を記述します。
