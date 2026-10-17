# Provenance / 来源说明

The morphology images are real outputs of archived LocalGrowthNPA models saved at 30,000 parameter updates. They were not made with image-generation software. The new evaluations use each checkpoint's stored scientific configuration and weights in a restored compatible implementation. All three historical evaluation seeds are shown separately from the fresh seed-101 runs.

形态图来自30000次参数更新保存的真实LocalGrowthNPA模型，不由图像生成软件制作。新推理在恢复后的兼容实现中使用权重自带的科学配置和参数。全部三个历史独立种子与新的种子101运行分开展示。

The evaluated checkpoints use 24 state channels, a 98-component continuous perception vector, a 110-component lifecycle input, width-128 continuous and width-64 lifecycle networks, and 23,494 trainable parameters. Later fine-geometry and lifecycle changes in the private development tree are not evaluated by these figures. Historical target-dependent rendering uses the factor min(1, reference point count / particle count); this is not an input to the lifecycle network.

评估的权重使用24维状态、98维连续感知、110维生死输入、128维连续网络隐藏层和64维生死网络隐藏层，共23494个可训练参数。这些图没有验证私有开发代码后来新增的细几何与生死机制。历史渲染使用min(1,参考点数/当前粒子数)系数，该系数不作为生死网络输入。

The work is based on **Neural Particle Automata: Learning Self-Organizing Particle Dynamics**, Hyunsoo Kim, Ehsan Pajouheshgar, Sabine Süsstrunk, Wenzel Jakob, and Jinah Park, [arXiv:2601.16096](https://arxiv.org/abs/2601.16096). The official implementation is [TheDevilWillBeBee/NPA](https://github.com/TheDevilWillBeBee/NPA). The current public showcase does not redistribute that source code, training target files, compiled operators, or model weights, and does not assign a blanket license to those materials.

本工作基于上述NPA论文及其官方实现。本公开展示仓库不再分发原始代码、训练目标文件、编译算子或模型权重，也不为这些材料指定统一许可证。

The author supplied and authorized publication of the WeChat contact image. That image is copied without modification. The affiliation follows the university's English [description](https://en.lnu.edu.cn/About_LNU1/About_Liaoning_University.htm), which uses “Faculty of Information”.

作者提供并授权公开微信联系图片，该图片未经修改直接复制。单位英文采用学校英文[介绍](https://en.lnu.edu.cn/About_LNU1/About_Liaoning_University.htm)使用的“Faculty of Information”（信息学部）。

For research code, checkpoints, or additional materials, contact [Zheng Fang / 方正](mailto:1640691243@qq.com).

如需研究代码、模型权重或其他补充材料，请通过邮箱联系方正。
