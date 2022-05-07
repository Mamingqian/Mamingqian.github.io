---
layout: post
title:  "Week 5 Report"
categories: DCE report
tags: DCE
---

## 周报 Week5

1. 细读打车/拼车相关论文 3篇

   1. Optimal Vehicle Dispatching for Ride-sharing Platforms via Dynamic Pricing

      目标: 有效的算法来计算准确的收入最优l定价方案.

      数据集: 某大型打车平台数据集

      问题: 价格和调度方案应**地域**相关； 应考虑环境中的**动态**供需

      移动调度的特点： 1. 可以动态定价 2. 客户立即决定是否接受订单

      方法: Markov Decision Process (polytime)

   2. Spatial transition Learning on Road Networks with Deep Probabilistic Models

      目标: 基于实时交通在线规划路径

      模型: DeepST

      数据集: 滴滴公布的过往数据集

      影响因素: 过往路径, 目的地, 实施交通情况

   3. Preference-Aware Task Assignment in On-Demand Taxi Dispatching: An Online Stable Matching Approach

      创新点：同时考虑了司机和乘客的满意程度

      假设：任务到达的分布相同且已知（KIID）

      优化目标：1. 最大期望总收益 2. 最少期望blocking pairs

      blocking pair: 在匹配中有司机um与乘客vm匹配，司机更偏好另一乘客的同时乘客更偏好另一司机称为一对blocking pair

      约束：算法本身约束

      算法：Linear Programming

2. 扫一遍其他十几篇相关打车的论文的算法和场景，想改进方案

3. 写申请书网约车项目简介、目的、内容、国内外研究现状（需要改内容）