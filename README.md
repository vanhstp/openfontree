# Open Fontree

Open Fontree 是一个开源字体关系树通用数据存储库（JSON）。



## maps.jsonc

这里存储了所有字体以 ID 为值的关系映射数据。

```jsonc
[
    ["原字体 ID", "目标字体 ID", "描述"]
    // ...
]
```

## ids.jsonc

这里存储了所有可用 ID 和对应的字体，同样，也是 [ZeoSeven Fonts](https://fonts.zeoseven.com) 中的字体 ID 数据。

```jsonc
[
    {
        "id": 1,
        "name": "字体名称",
        "alias": ["别名1", "别名2"]
        // ...
    }
    // ...
]
```



## 🎈 贡献

Open Fontree 的字体关系数据仍然不足，欢迎大家提交 [Pull requests](https://github.com/zeoseven/openfontree/pulls)。

## ✨ 预览

[ZeoSeven Fonts Tree](https://fonts.zeoseven.com/tree/)

## 📄 许可证

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)