# 软件测试与维护大作业 - 基于 SockShop 的微服务系统部署、测试与维护

## 项目简介

本项目是《软件测试与维护》课程（2025~2026学年第一学期）的大作业，围绕微服务系统的部署、测试和维护进行实践。小组选择部署开源微服务系统 **SockShop**，并在本地 Minikube 集群上完成容器化部署。

## 小组成员

| 姓名 | 学号 | 负责内容 |
|------|------|----------|
| 汪孟坤 | 2313277 | 阶段一：微服务系统部署与论文阅读 |
| 王建雄 | 2311653 | 阶段二：Prometheus & Grafana 数据采集与维护 |
| 马嘉皓 | 2311565 | 阶段三：Selenium 功能测试 |
| 覃庆浩 | 2310904 | 阶段三：JMeter 性能测试 |
| 张世隆 | 2313877 | 阶段四：MARINA 算法复现 |
| 宋炳臻 | 2311740 | 加分项：SLIM 与 BARO 论文复现 |

**指导老师：** 张圣林

## 技术栈

- **微服务系统：** SockShop
- **容器编排：** Docker, Kubernetes, Minikube
- **监控工具：** Prometheus, Grafana
- **故障注入：** ChaosMesh
- **功能测试：** Selenium
- **性能测试：** JMeter
- **算法复现：** MARINA, SLIM, BARO

## 项目结构

```
.
├── labx.tex              # LaTeX 报告源文件
├── labx.pdf              # 生成的 PDF 报告
├── mcode.sty             # MATLAB 代码高亮宏包
├── figure/               # 报告图片资源
│   ├── nankai.jpg        # 南开大学校徽
│   ├── calculator.png
│   └── PIC2.png
├── docs/                 # 参考资料
│   ├── 覃庆浩/           # JMeter 性能测试资料
│   │   ├── 测试计划.md
│   │   ├── 测试结果分析.md
│   │   ├── *.jmx         # JMeter 测试脚本
│   │   └── *.png         # 测试截图
│   └── 软件测试与维护（2026年春）大作业要求.md
└── README.md             # 本文件
```

## 报告内容

1. **项目概述** - 项目背景与目标
2. **阶段一：微服务系统部署与论文阅读** - SockShop 部署、论文阅读
3. **阶段二：Prometheus & Grafana 数据采集与维护** - 监控配置与数据采集
4. **阶段三：Selenium & JMeter 测试** - 功能测试与性能测试
5. **阶段四：MARINA 算法复现与验证** - KPI 异常检测算法复现
6. **加分项：SLIM 与 BARO 论文复现与对比** - 日志异常检测与根因分析

## 编译说明

### 环境要求

- **MiKTeX** (推荐) 或 TeX Live
- **XeLaTeX** 编译器

### 编译命令

```bash
# 使用 XeLaTeX 编译（需编译两次以解决交叉引用）
xelatex labx.tex
xelatex labx.tex
```

### 使用 LaTeX Workshop (VS Code)

1. 安装 VS Code 扩展 `LaTeX Workshop`
2. 打开 `labx.tex`
3. 使用 `Ctrl+Alt+B` 编译（确保编译器设置为 XeLaTeX）

## 许可证

本项目为课程作业，仅供学习参考使用。
