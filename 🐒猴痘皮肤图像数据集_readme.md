---
Topic:
    - 医疗健康

License:
    - CC-BY-SA 4.0 署名-以相同方式共享

Ext:
    - .zip

DatasetUsage:
    - 422805206
---

## **背景描述**
使用网络抓取来收集猴痘、水痘、天花、牛痘和麻疹感染的皮肤以及健康的皮肤图像，以建立一个全面的图像数据库。
该数据集共有 804 张原始网络抓取图像（猴痘：117，水痘：178，天花：358，牛痘：54，麻疹：47，健康：50）和 39,396 张增强图像（猴痘：5733，水痘：8722，天花：17542，牛痘：2646，麻疹：2303，健康：2450）

## **数据说明**
该数据库包含五种不同疾病类别的皮肤病变/皮疹图像：(1) 猴痘、(2) 水痘、(3) 天花、(4) 牛痘和 (5) 麻疹，还包含 (6) 健康皮肤图像.
与其他类似数据库（可在“preprocessed_original_images”文件夹中找到）相比，该数据库在增强之前包含更多网络报废的痘和麻疹图像数据。
通过用黑框遮挡暴露的眼睛和私密部位来增强图像中患者的隐私。
使用各种增强技术将数据量增加了 49 倍（可以在“augmented_images”文件夹中找到）。
数据库中所有图像的来源，并将来源/信用列表显示为 Excel 表（即 image_list_with_sources_and_credits.xlxs）。

## **引用**
Towhidul Islam、Mohammad Arafat Hussain、Forhad Uddin Hasan Chowdhury、BM Riazul Islam，猴痘、水痘、天花、牛痘和麻疹的网络抓取皮肤图像数据库，bioRxiv 2022.08.01.502199；doi：https ://doi.org/10.1101/2022.08.01.502199


```
@article{islam2022aweb,
  title={A Web-scrapped Skin Image Database of Monkeypox, Chickenpox, Smallpox, Cowpox, and Measles},
  author={Islam, Towhidul and Hussain, Mohammad Arafat and Chowdhury, Forhad Uddin Hasan and Islam, B M Riazul},
  journal={bioRxiv 2022.08.01.502199},
  doi={https://doi.org/10.1101/2022.08.01.502199},
  year={2022}
}
```

## **问题描述**
该数据能解决什么问题？适用于什么场景

## **引用格式**
```
@misc{Monkeypox2544,
    title = { 🐒猴痘皮肤图像数据集 },
    author = { sosososo },
    howpublished = { \url{https://www.heywhale.com/mw/dataset/62eb75d6fef0903951b1f199} },
    year = { 2022 },
}
```