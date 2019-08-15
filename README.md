# メッシュ画像
過去に作成したメッシュです。OpenFOAMケース形式で保存してあります。

## beer350
350mLビールのアルミ缶です。
![アルミ缶](https://github.com/inabower/myMeshes/blob/master/can350/beer350_1.png)


```checkMesh
Mesh stats
    points:           5637
    faces:            15034
    internal faces:   13334
    cells:            4728

Overall number of cells of each type:
    hexahedra:     4728

Checking geometry...
    Overall domain bounding box (-3.59869e-16 0 0) (0.033 0.033 0.12)
    Mesh has 3 geometric (non-empty/wedge) directions (1 1 1)
    Mesh has 3 solution (non-empty) directions (1 1 1)
    Boundary openness (-1.71026e-16 3.36002e-16 -4.00774e-17) OK.
    Max cell openness = 2.20339e-16 OK.
    Max aspect ratio = 3.71197 OK.
    Minimum face area = 1.88924e-06. Maximum face area = 1.69084e-05.  Face area magnitudes OK.
    Min volume = 3.7469e-09. Max volume = 3.84414e-08.  Total volume = 9.72549e-05.  Cell volumes OK.
    Mesh non-orthogonality Max: 45.062 average: 12.3307
    Non-orthogonality check OK.
    Face pyramids OK.
    Max skewness = 1.15241 OK.
    Coupled point location match (average 0) OK.
```

## skate
上から見た二人のスケート選手の周りの流れです（2D）
![スケート選手](https://github.com/inabower/myMeshes/blob/master/skate/skate_1.png)

```checkMesh
Mesh stats
    points:           48340
    faces:            95325
    internal faces:   46983
    cells:            23718

Overall number of cells of each type:
    hexahedra:     23718

Checking geometry...
    Overall domain bounding box (-3 0 0) (3 10 0.1)
    Mesh has 2 geometric (non-empty/wedge) directions (1 1 0)
    Mesh has 2 solution (non-empty) directions (1 1 0)
    Boundary openness (3.606138969e-18 2.958520293e-18 -2.199647452e-19) OK.
    Max cell openness = 2.149027517e-16 OK.
    Max aspect ratio = 6.300000063 OK.
    Minimum face area = 5.56211393e-05. Maximum face area = 0.007040779503.  Face area magnitudes OK.
    Min volume = 5.56211393e-06. Max volume = 0.0003454111773.  Total volume = 5.94200297.  Cell volumes OK.
    Mesh non-orthogonality Max: 58.59247269 average: 10.42039112
    Non-orthogonality check OK.
    Face pyramids OK.
    Max skewness = 1.622811096 OK.
    Coupled point location match (average 0) OK.
```

## messFlask
メスフラスコ内部の流れです。

![mess](https://github.com/inabower/myMeshes/blob/master/messFlask/messFlask_2.png)

```checkMesh
Mesh stats
    points:           32177
    faces:            93504
    internal faces:   90816
    cells:            30720

Overall number of cells of each type:
    hexahedra:     30720

Checking geometry...
    Overall domain bounding box (-0.0159472 -0.0159472 -2.54437e-31) (0.0159472 0.0159472 0.1)
    Mesh has 3 geometric (non-empty/wedge) directions (1 1 1)
    Mesh has 3 solution (non-empty) directions (1 1 1)
    Boundary openness (-2.49368e-16 -8.23499e-17 -1.16701e-16) OK.
    Max cell openness = 3.13935e-16 OK.
    Max aspect ratio = 9.01127 OK.
    Minimum face area = 9.85816e-08. Maximum face area = 7.42425e-06.  Face area magnitudes OK.
    Min volume = 3.35874e-11. Max volume = 3.98327e-09.  Total volume = 2.03581e-05.  Cell volumes OK.
    Mesh non-orthogonality Max: 54.177 average: 14.6506
    Non-orthogonality check OK.
    Face pyramids OK.
    Max skewness = 0.899658 OK.
    Coupled point location match (average 0) OK.
```

## wineAndGlass
ワインとワイングラスです。
![wineandglass](https://github.com/inabower/myMeshes/blob/master/wineAndGlass/wineglass.png)

- wine

```checkMesh
Mesh stats
    points:           44566
    faces:            126822
    internal faces:   120282
    cells:            41184

Overall number of cells of each type:
    hexahedra:     41184

Checking geometry...
    Overall domain bounding box (0 0 -20) (60.8613 60.8613 75)
    Mesh has 3 geometric (non-empty/wedge) directions (1 1 1)
    Mesh has 3 solution (non-empty) directions (1 1 1)
    Boundary openness (-1.12136e-15 -1.44007e-16 3.04849e-16) OK.
    Max cell openness = 2.97461e-16 OK.
    Max aspect ratio = 5.88254 OK.
    Minimum face area = 0.880476. Maximum face area = 13.4825.  Face area magnitudes OK.
    Min volume = 1.47876. Max volume = 12.7951.  Total volume = 194069.  Cell volumes OK.
    Mesh non-orthogonality Max: 42.0869 average: 14.117
    Non-orthogonality check OK.
    Face pyramids OK.
    Max skewness = 0.832373 OK.
    Coupled point location match (average 0) OK.

```

- glass

```checkMesh
Mesh stats
    points:           30910
    faces:            78876
    internal faces:   65700
    cells:            24096

Overall number of cells of each type:
    hexahedra:     24096

Checking geometry...
    Overall domain bounding box (-2.40741e-35 0 -75) (61.6576 61.6576 75.506)
    Mesh has 3 geometric (non-empty/wedge) directions (1 1 1)
    Mesh has 3 solution (non-empty) directions (1 1 1)
    Boundary openness (-3.92097e-16 1.95016e-16 -4.36485e-16) OK.
    Max cell openness = 3.10911e-16 OK.
    Max aspect ratio = 11.8486 OK.
    Minimum face area = 0.06. Maximum face area = 6.76117.  Face area magnitudes OK.
    Min volume = 0.059168. Max volume = 4.05733.  Total volume = 13999.3.  Cell volumes OK.
    Mesh non-orthogonality Max: 60.795 average: 13.1767
    Non-orthogonality check OK.
    Face pyramids OK.
    Max skewness = 1.80906 OK.
    Coupled point location match (average 0) OK.

```

## golfBall
ゴルフボール周りの空気です。
![golf](https://github.com/inabower/myMeshes/blob/master/golf/golf_1.png)

```checkMesh
Mesh stats
    points:           1650909
    faces:            4657576
    internal faces:   4406912
    cells:            1503456

Overall number of cells of each type:
    hexahedra:     1489640
    polyhedra:     13816

Checking geometry...
    Overall domain bounding box (-0.2 -0.1 -0.1) (0.3 0.1 0.1)
    Mesh has 3 geometric (non-empty/wedge) directions (1 1 1)
    Mesh has 3 solution (non-empty) directions (1 1 1)
    Boundary openness (-9.57862e-17 4.62466e-16 4.12264e-16) OK.
    Max cell openness = 3.24423e-16 OK.
    Max aspect ratio = 6.85826 OK.
    Minimum face area = 2.95482e-08. Maximum face area = 3.3335e-05.  Face area magnitudes OK.
    Min volume = 1.26418e-11. Max volume = 1.66675e-07.  Total volume = 0.0199604.  Cell volumes OK.
    Mesh non-orthogonality Max: 54.4129 average: 17.4334
    Non-orthogonality check OK.
    Face pyramids OK.
    Max skewness = 0.997401 OK.
    Coupled point location match (average 0) OK.

```
