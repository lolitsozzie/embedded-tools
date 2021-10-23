<template>
  <div class="about main-body left-align center-horizontal">
    <h4>example <span class="red">chart.js</span> implementation</h4>
    <blockquote class="pre">
        const config = {
        type: 'bar',
        data: data,
        options: {
                responsive: true,
                plugins: {
                legend: {
                    position: 'top',
                },
                title: {
                    display: true,
                    text: 'Chart.js Bar Chart'
                }
                }
            },
        };
    </blockquote>
  </div>
</template>

<style scoped>
.pre {
    background: #f4f4f4;
    border: 1px solid #ddd;
    border-left: 6px solid #42b983;
    color: #666;
    page-break-inside: avoid;
    font-family: monospace;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 1.6em;
    max-width: 100%;
    overflow: auto;
    padding: 1em 1.5em;
    display: block;
    word-wrap: break-word;
}
.left-align {
    text-align: left !important;
}
</style>