# CVPR_2025_workshops

本仓库集中整理 CVPR 2025 Workshops **冠层图** 与 **叶面斑块** 两个研究方向的公开 GitHub 参考项目，来自用户提供的 `开源代码清单(10).md` 和 `开源代码清单(20261125-002638).md`。

**清单统计：** 9 + 14 = 23 条项目记录，按 `owner/repo` 去重后有 **18 个唯一项目**，跨方向重复 **5 个**。重复项目为 `semanticsugarbeets`、`FLAR-SVD`、`imagine`、`CARN`、`MAI-2025-Workshop`，每个只保存一份。许可证核验后，**11 个**已按各自授权条件完成源码复制，**7 个**仅保存来源链接。

> 集中保存是项目文件快照，不是 GitHub 官方 Fork；不保留上游完整 Git 提交历史、外部权重或 Git LFS 实际对象。请在使用或再分发时遵守各项目独立许可证。

## 去重项目目录

| 文件夹 | Workshop 编号 | 研究方向 | 上游原仓库 | 许可证 | 保存状态 |
| --- | --- | --- | --- | --- | --- |
| [semanticsugarbeets](./semanticsugarbeets/) | W25-0717 | 冠层图；叶面斑块 | [semanticsugarbeets/semanticsugarbeets](https://github.com/semanticsugarbeets/semanticsugarbeets) | CC BY-NC-SA 4.0（非商业；署名；相同方式共享） | 已复制源码 |
| [ETS](./ETS/) | W25-0051 | 冠层图 | [jaychempan/ETS](https://github.com/jaychempan/ETS) | MIT | 已复制源码 |
| [X-Few-_CD-FSOD](./X-Few-_CD-FSOD/) | W25-0021 | 冠层图 | [johnmaijer/X-Few-_CD-FSOD](https://github.com/johnmaijer/X-Few-_CD-FSOD) | Apache-2.0 | 已复制源码 |
| [NTIRE2025_CDFSOD](./NTIRE2025_CDFSOD/) | W25-0016 | 冠层图 | [lovelyqian/NTIRE2025_CDFSOD](https://github.com/lovelyqian/NTIRE2025_CDFSOD) | 未发现可核实的仓库级再分发许可证 | 仅保存链接 |
| [FLAR-SVD](./FLAR-SVD/) | W25-0567 | 冠层图；叶面斑块 | [MoritzTho/FLAR-SVD](https://github.com/MoritzTho/FLAR-SVD) | CC0-1.0 | 已复制源码 |
| [imagine](./imagine/) | W25-0012 | 冠层图；叶面斑块 | [minyan8/imagine](https://github.com/minyan8/imagine) | 未发现可核实的仓库级再分发许可证 | 仅保存链接 |
| [CARN](./CARN/) | W25-0206 | 冠层图；叶面斑块 | [rrgaire/CARN](https://github.com/rrgaire/CARN) | MIT | 已复制源码 |
| [MAI-2025-Workshop](./MAI-2025-Workshop/) | W25-0560 | 冠层图；叶面斑块 | [aiff22/MAI-2025-Workshop](https://github.com/aiff22/MAI-2025-Workshop) | 未发现可核实的仓库级再分发许可证 | 仅保存链接 |
| [vit4v](./vit4v/) | W25-0719 | 冠层图 | [kernel-machine/vit4v](https://github.com/kernel-machine/vit4v) | CC BY-NC-ND 4.0（仅非商业；不得分发改编版本） | 已复制源码 |
| [banana-defect-segmentation](./banana-defect-segmentation/) | W25-0724 | 叶面斑块 | [manuelknott/banana-defect-segmentation](https://github.com/manuelknott/banana-defect-segmentation) | MIT | 已复制源码 |
| [SODDCNet](./SODDCNet/) | W25-0331 | 叶面斑块 | [VimsLab/SODDCNet](https://github.com/VimsLab/SODDCNet) | 未发现可核实的仓库级再分发许可证 | 仅保存链接 |
| [AL-CycleGAN](./AL-CycleGAN/) | W25-0777 | 叶面斑块 | [ganatma/AL-CycleGAN](https://github.com/ganatma/AL-CycleGAN) | MIT | 已复制源码 |
| [SK-RD4AD](./SK-RD4AD/) | W25-0779 | 叶面斑块 | [pej0918/SK-RD4AD](https://github.com/pej0918/SK-RD4AD) | 未发现可核实的仓库级再分发许可证 | 仅保存链接 |
| [moviad](./moviad/) | W25-0765 | 叶面斑块 | [AMCO-UniPD/moviad](https://github.com/AMCO-UniPD/moviad) | Apache-2.0 | 已复制源码 |
| [NExNet_Seg](./NExNet_Seg/) | W25-0533 | 叶面斑块 | [MAIN-Lab/NExNet_Seg](https://github.com/MAIN-Lab/NExNet_Seg) | MIT | 已复制源码 |
| [ShowOrTell](./ShowOrTell/) | W25-0871 | 叶面斑块 | [FocoosAI/ShowOrTell](https://github.com/FocoosAI/ShowOrTell) | 未发现可核实的仓库级再分发许可证 | 仅保存链接 |
| [viad-benchmark](./viad-benchmark/) | W25-0763 | 叶面斑块 | [abc-125/viad-benchmark](https://github.com/abc-125/viad-benchmark) | Apache-2.0 | 已复制源码 |
| [ITACLIP](./ITACLIP/) | W25-0866 | 叶面斑块 | [m-arda-aydn/ITACLIP](https://github.com/m-arda-aydn/ITACLIP) | 未发现可核实的仓库级再分发许可证 | 仅保存链接 |

## 许可及引用约束

- `semanticsugarbeets` 使用 **CC BY-NC-SA 4.0**：需要署名、非商业使用，并按相同方式共享适用的改编作品。
- `vit4v` 原仓库的 `LICENCE.md` 为 **CC BY-NC-ND 4.0**：仅按许可证共享未改动快照；不得公开分发改编版本，且使用限非商业。
- 其他已复制项目仍须保留原有 MIT、Apache-2.0 或 CC0-1.0 声明；第三方依赖与数据、模型权重可能另有条款。
- 没有明确许可证的 7 个项目只创建 `SOURCE.md` 来源档案，不在本公开仓库复制源码。
- 复制的是上游**默认分支的当前公开快照**，不代表论文当年精确对应版本。外部数据、Git submodule、Git LFS、模型权重及超大文件可能未被完整保存。
- 两份清单里的 `D:\mianyeman\paper\CVPR 2025 workshops\参考代码` 是计划的 Windows 本地存放位置，本次只操作 GitHub，不会修改用户本地计算机。

**导入核验：** 11 个项目的源码快照均已成功提交，7 个无明确再分发许可的项目仅保留链接。首次批量推送发生 GitHub 远端 Internal Server Error，已通过[逐项目恢复导入](https://github.com/FCYCY444/CVPR_2025_workshops/actions/runs/45518690532)完全补齐。完整结果见 [导入报告](./import-reports/cvpr2025-workshops-import.md)。

## 索引与执行记录

- [机器可读项目索引](./projects.csv)
- [源码导入清单](./.github/import-cvpr2025-workshops.tsv)
- [源码导入报告](./import-reports/cvpr2025-workshops-import.md)（11 个项目均已完成）
- [待核实论文/工具/项目来源](./unverified-sources.md)（与 18 个已核实主表项目分开存放）
