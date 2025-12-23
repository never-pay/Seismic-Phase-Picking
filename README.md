# Seismic-Phase-Picking
我的模型与sciprismax比较
修改 HTML 配置：打开 index.html，在 datasetConfigs 数组里添加一行：
code
JavaScript
datasetConfigs: [
    { name: 'ETHZ Dataset', url: './data/ethz.json' },
    { name: 'PNW Dataset', url: './data/pnw.json' },
    { name: 'SCEDC Dataset', url: './data/scedc.json' },
    { name: 'Iquique Dataset', url: './data/iquique.json' } // 新加这一行
],