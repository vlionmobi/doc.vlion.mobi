---
sidebar_position: 1
---

# Docs Introduction

## Markdown 额外特性

[详情](https://docusaurus.io/zh-CN/docs/markdown-features)

### 选项卡示例

``` jsx title="选项卡示例代码"
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
  <TabItem value="apple" label="苹果" default>
    这是个苹果 🍎
  </TabItem>
  <TabItem value="orange" label="橙子">
    这是个橙子 🍊
  </TabItem>
  <TabItem value="banana" label="香蕉">
    这是个香蕉 🍌
  </TabItem>
</Tabs>
```

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
  <TabItem value="apple" label="苹果" default>
    这是个苹果 🍎
  </TabItem>
  <TabItem value="orange" label="橙子">
    这是个橙子 🍊
  </TabItem>
  <TabItem value="banana" label="香蕉">
    这是个香蕉 🍌
  </TabItem>
</Tabs>

### Details 元素示例

``` jsx title="Details 示例代码"
<details>
  <summary>点我！</summary>
  <div>
    <div>这是详情内容</div>
    <br/>
    <details>
      <summary>
        嵌套的下拉栏！ 内含惊喜……
      </summary>
      <div>
        😲😲😲😲😲
      </div>
    </details>
  </div>
</details>
```

<details>
  <summary>点我！</summary>
  <div>
    <div>这是详情内容</div>
    <br/>
    <details>
      <summary>
        嵌套的下拉栏！ 内含惊喜……
      </summary>
      <div>
        😲😲😲😲😲
      </div>
    </details>
  </div>
</details>