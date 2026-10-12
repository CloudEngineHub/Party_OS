# Party OS

**ROBO PARTY | LAB** 面向人形机器人的系统与能力演进路线。

Party OS 从数据生成、动作重定向和无本体数采做起，接上监督学习与无监督学习，再向上展开人–物交互（HOI：低动态的搬运与移动、高动态的球类）和人–系统交互（HSI），最后进入规划、执行、验证，以及评估、调优、部署。

## Roadmap

<p align="center">
  <img src="assets/party-os-roadmap.png" alt="Party OS Roadmap" width="100%">
</p>

## 子项目

按 Roadmap 从数据采集、学习、交互到规划与部署展开：

<table>
  <thead>
    <tr>
      <th>层级</th>
      <th>模块</th>
      <th>说明</th>
      <th>仓库</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Know-how 文档</strong></td>
      <td>知识库</td>
      <td>ROBO PARTY 技术 Know-how 与文档汇总</td>
      <td><a href="https://roboparty.feishu.cn/wiki/GvUxwKVeNiGa7kku6vEcvqfKn87">《人形机器人运动控制Know-how》</a></td>
    </tr>
    <tr>
      <td rowspan="3"><strong>数据</strong></td>
      <td>数据生成 (generate)</td>
      <td>数据生成</td>
      <td>即将开源</td>
    </tr>
    <tr>
      <td>重定向 (hhtools)</td>
      <td>人体 / 机器人动作到任意人形的快速重定向</td>
      <td><a href="https://github.com/Roboparty/human-humanoid-tools">Roboparty/human-humanoid-tools</a></td>
    </tr>
    <tr>
      <td>无本体数采 (ego humanoid)</td>
      <td>无本体数据采集</td>
      <td>即将开源</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>学习</strong></td>
      <td>监督学习 (MimicLite)</td>
      <td>运动模仿：加载、跟踪、训练、评估与部署衔接</td>
      <td><a href="https://github.com/Roboparty/MimicLite">Roboparty/MimicLite</a></td>
    </tr>
    <tr>
      <td>无监督学习 (UFO)</td>
      <td>无监督学习框架</td>
      <td><a href="https://github.com/Roboparty/UFO">Roboparty/UFO</a></td>
    </tr>
    <tr>
      <td rowspan="3"><strong>交互</strong></td>
      <td>低动态交互 (HOI)</td>
      <td>搬运、移动</td>
      <td>—</td>
    </tr>
    <tr>
      <td>高动态交互 (HOI)</td>
      <td>球类</td>
      <td>—</td>
    </tr>
    <tr>
      <td>HSI</td>
      <td>人–系统交互</td>
      <td>—</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>规划到部署</strong></td>
      <td>规划、执行、验证</td>
      <td>规划、执行与验证</td>
      <td>—</td>
    </tr>
    <tr>
      <td>评估、调优、部署</td>
      <td>评估、调优与部署</td>
      <td>—</td>
    </tr>
  </tbody>
</table>


## 许可证

本仓库采用 [GNU General Public License v3.0 (GPL-3.0)](LICENSE)。各子项目保留各自的许可证，使用前请查阅对应仓库说明。
