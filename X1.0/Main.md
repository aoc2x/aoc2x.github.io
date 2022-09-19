**CFG.smali**
```smali
.method private static final showAndroidKeyboard()V

    .registers 3

    sget-object v0, Lage/of/civilizations2/jakowski/lukasz/AoCGame;->mLinkHandler:Lage/of/civilizations2/jakowski/lukasz/LinkHandler;

    const-string v1, "showKeyboard"

    const/4 v2, 0x0

    invoke-interface {v0, v1, v2}, Lage/of/civilizations2/jakowski/lukasz/LinkHandler;->openPage(Ljava/lang/String;Ljava/lang/String;)V

    return-void

.end method
```
