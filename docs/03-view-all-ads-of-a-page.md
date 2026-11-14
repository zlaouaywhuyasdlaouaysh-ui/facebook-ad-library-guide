# 如何查看某个 Facebook 主页的全部广告

> 本章是 [33.ci](https://33.ci/?utm_source=github&utm_medium=referral&utm_campaign=fb-ad-library-guide) 教程《如何查看某个 Facebook 主页的全部广告》的精简版，完整图文版见文末链接。

三种方法进入一个主页的全部广告，主页透明度最准确。

## 方法一：主页透明度

打开主页 →「主页透明度」（电脑在左侧简介或「关于」，手机在简介下方）→「查看全部」→「前往广告资料库」。不会因重名出错，还能看创建日期、改名记录、管理员国家 / 地区。

## 方法二：搜索框选主页

在 `https://www.facebook.com/ads/library/` 选「所有国家 / 地区」，输入主页名，点下拉中带头像的一项，别按回车。

## 方法三：固定链接

```
https://www.facebook.com/ads/library/?active_status=all&ad_type=all&country=ALL&view_all_page_id=主页编号&search_type=page
```

主页编号见主页透明度或前两种方法的地址栏。

| 参数 | 含义 |
|-|-|
| `active_status` | `active` 投放中，`all` 含已停投 |
| `country` | `ALL` 所有，`US` 美国，`GB` 英国等 |
| `view_all_page_id` | 主页编号 |

## 怎么看

- 结果数：在投规模。
- 「投放中」看当前花钱的；「全部」含已停投（非欧盟停投后通常不显示）。
- 按平台、媒体类型筛选。
- 最新开始的 = 最近在测；最早开始仍在投的 = 长期主力。

## 常见情况

- **0 条**：没在投、用别的主页投，或不是公共主页。
- **上千条**：先筛「投放中」+「视频」，看跑得最久的。
- **看每日增减**：资料库无变化记录，需定期对比或用监控工具。

---

**相关章节**：[Facebook 广告资料库怎么用：从打开到看懂一条广告](01-facebook-ad-library-guide.md) · [为什么在广告资料库里搜不到某个主页或广告](05-why-ads-not-showing-in-ad-library.md) · [怎么找 Facebook 主页编号（Page ID）](10-find-facebook-page-id.md) · [怎么判断一条 Facebook 广告是不是爆款](11-how-to-spot-winning-facebook-ads.md)

**完整版**：[如何查看某个 Facebook 主页的全部广告](https://33.ci/guides/view-all-ads-of-a-page?utm_source=github&utm_medium=referral&utm_campaign=fb-ad-library-guide)
