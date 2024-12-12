# Relaxed Packages 项目文档

## 项目概述

Relaxed Packages 是一个基于 monorepo 架构的工具集合，旨在提供高质量的 Vue3 工具函数和通用开发工具。项目采用 TypeScript 开发，确保类型安全和开发体验。

## 核心包说明

### 1. @relaxed/hook - Vue3 组合式 API 工具集

提供一系列实用的 Vue3 Composition API 工具函数，帮助开发者更高效地管理组件状态和逻辑。

**当前功能:**

- `useBoolean`: 布尔值状态管理钩子，提供便捷的切换功能

 
  ```ts
  const { bool, toggle } = useBoolean(false)
  ```

### 2. @relaxed/tsconfig - TypeScript 配置模板

提供标准化的 TypeScript 配置模板，确保项目中的 TypeScript 代码风格统一。

**主要特性:**

- 严格的类型检查
- 现代化的模块解析
- 自动生成类型声明文件
- ESModule 优先

### 3. @relaxed/utils - 通用工具函数库

提供常用的工具函数集合，提高开发效率。

**当前功能:**

- `Accumulation`: 数值累加计算
- `Multiplication`: 数值累乘计算

## 快速开始

### 安装

1. 克隆项目
