# ProgLeijianhei 补个类简黑
补个类简黑是基于[思源黑体](https://github.com/adobe-fonts/source-han-sans)，在[小合简化体 黑体](https://github.com/GuiWonder/XiaoheSimplifyFonts)的基础上修改而来的繁入简出的字体，对于未见于《简化字总表》《通用规范汉字表》的繁体字严格按照《简化字总表》的规则予以类推简化（故名），思源黑体中不存在的字套用[遍黑体](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic)或自行制作，自行制作的字形亦会用于贡献给遍黑体。

## 特性

- 支持BMP内所有汉字（即基本区与扩展A区）的繁入简出，其余平面汉字可能会填一些。
- 在注音字母的右下角会添加对应的汉语拼音，辅助阅读。
- 只计划制作Regular字重。
- 对于“一繁对多简”的字（如瞭—瞭了、乾—乾干、蘋—苹𬞟、噁—𫫇恶等），使用OpenType特性制作，确保有上下文的前提下显示正确。具体实现方法及其局限可参考[此文](https://ayaka.shn.hk/s2tfont/)。

## 更新日志

- 0.001版（2022-10-15）

    修正了小合简化体的一些错误，添加一些简繁对应关系，新造部分汉字，完整支持繁入简出《通用规范汉字表》内的汉字及类推简化字在扩展H区的汉字，支持了注音字母辅助阅读，其余汉字与特性有部分仍在制作中。

## 授权

本字体依1.1版的SIL Open Font License公开。

## 帮助完善

如有问题欢迎提issue。
