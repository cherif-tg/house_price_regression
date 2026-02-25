1. Analyse du dataset

-Analyse de forme:
    .Il s'agit d'un dataset de 1460 lignes et 81 colonnes
    .La target est le prix de vente SalePrice
    .Il y'a 80 features
    .Il y'a des variables qui possedent des valeurs manquantes
    (
        Electrical       0.000685
        MasVnrArea       0.005479
        BsmtFinType1     0.025342
        BsmtQual         0.025342
        BsmtCond         0.025342
        BsmtFinType2     0.026027
        BsmtExposure     0.026027
        GarageQual       0.055479
        GarageYrBlt      0.055479
        GarageFinish     0.055479
        GarageType       0.055479
        GarageCond       0.055479
        LotFrontage      0.177397
        FireplaceQu      0.472603
        MasVnrType       0.597260
        Fence            0.807534
        Alley            0.937671
        MiscFeature      0.963014
        PoolQC           0.995205
    )

-Analyse de fond:
    -Anlyse de la target et des features:
        .Ne cotient pas de valeurs manquentes
        .Les variables ne somt pas normalisées


    -Analyse des relations Variables/target
        .Certaines variables sont mieux corrélées a la target que d'autres
        OverallQual      0.790982
        GrLivArea        0.708624
        GarageCars       0.640409
        GarageArea       0.623431
        TotalBsmtSF      0.613581
        1stFlrSF         0.605852
        FullBath         0.560664
        TotRmsAbvGrd     0.533723
        YearBuilt        0.522897
        YearRemodAdd     0.507101
        GarageYrBlt      0.486362
        MasVnrArea       0.477493
        Fireplaces       0.466929
        BsmtFinSF1       0.386420
        LotFrontage      0.351799
        WoodDeckSF       0.324413
        2ndFlrSF         0.319334
        OpenPorchSF      0.315856
        HalfBath         0.284108
        LotArea          0.263843
        BsmtFullBath     0.227122
        BsmtUnfSF        0.214479
        BedroomAbvGr     0.168213
        ScreenPorch      0.111447
        PoolArea         0.092404
        MoSold           0.046432
        3SsnPorch        0.044584

        .
        .


    -Analyse des relations Variables/Variables
        .
        .


    -Analyse des valeurs null