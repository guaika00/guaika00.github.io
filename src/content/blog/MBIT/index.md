---
title: MBTI Partner Compatibility
publishDate: 2025-09-18 15:43:20
description: 'MBTI Partner Compatibility'
tags:
  - Markdown
heroImage: { src: './thumbnail.jpg', color: '#B4C6DA' }
language: '中文'

---

## 内嵌 Astro 组件

<ECharts 
    option={{
      title: { text: '月度访问量统计' },
      tooltip: {},
      legend: { data: ['访问量'] },
      xAxis: { data: ['1月', '2月', '3月', '4月', '5月', '6月'] },
      yAxis: {},
      series: [
        {
          name: '访问量',
          type: 'bar',
          data: [120, 200, 150, 80, 70, 110]
        }
      ]
    }}
    style={{ width: '80%', height: '500px', margin: '0 auto' }}
  />

  <p>以下是一个折线图示例：</p>
  
  <!-- 再添加一个折线图 -->
  <ECharts 
    option={{
      title: { text: '用户增长趋势' },
      tooltip: {},
      xAxis: { data: ['1月', '2月', '3月', '4月', '5月', '6月'] },
      yAxis: {},
      series: [
        {
          name: '用户数',
          type: 'line',
          data: [100, 300, 500, 800, 1200, 1500]
        }
      ]
    }}
  />