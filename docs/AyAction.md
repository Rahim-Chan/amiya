# AyAction

## 基础示例

AyAction 继承了 AyButton 所有属性。

```tsx
/**
 * title: 基础 Modal
 * desc: 这是 antd Modal 组件的基础示例
 */
import React, { useState } from 'react'
import { AyAction } from 'amiya'
import 'antd/dist/antd.min.css'

export default function Demo() {
  return <AyAction onClick={() => alert('按钮')}>修改</AyAction>
}
```

## 配合 AySearchTable

<code src="./Table/Demo.tsx" />
