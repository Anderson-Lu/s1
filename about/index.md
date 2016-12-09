---
title: 
date: 2016-10-30 13:43:57
mathjax: false
comments: false
---

### <i class="fa fa-map-signs" aria-hidden="true"></i> &nbsp;Blog background

Hello guys, I am a technology enthusiast from Guangdong China. You can call me Anderson. I just graduated from college. And now I am a backend programmer. Actually, this is my third personal website. I have tried to publish in a variety of blog platforms, but I'm tired of it later. So I use github & hexo to build my own blog. However, I don't like the UI style, so after several changes, I begin a new attempt. I hope that this can be sustained to maintain it.

### <i class="fa fa-spinner" aria-hidden="true"></i>&nbsp; Technology stack

{% echarts 400 '100%' %}

option = {
    tooltip: {
        trigger: 'item',
        formatter: "{a} <br/>{b}: {c} ({d}%)"
    },
    legend: {
        orient: 'vertical',
        x: 'left',
        data:['APS.net','Java','Javascript/JQuery','SQL','NoSQL','MongoDB','Oracle','MySQL','SQL Server','SVN','Git','Algorithm','Linux','Bash','Vue.js','Node.js','ASP.net','Redis']
    },
    series: [
        {
            name:'Technique',
            type:'pie',
            radius: ['50%', '70%'],
            avoidLabelOverlap: false,
            label: {
                normal: {
                    show: false,
                    position: 'center'
                },
                emphasis: {
                    show: true,
                    textStyle: {
                        fontSize: '30',
                        fontWeight: 'bold'
                    }
                }
            },
            labelLine: {
                normal: {
                    show: false
                }
            },
            data:[
                {value:25,name:'Java'},
                {value:3, name:'MongoDB'},
                {value:2, name:'Oracle'},
                {value:2, name:'MySQL'},
                {value:1, name:'SQL Server'},
                {value:3, name:'SVN'},
                {value:2, name:"Git"},
                {value:5, name:'Algorithm'},
                {value:24, name:'ASP.net'},
                {value:4, name:'Linux'},
                {value:2, name:'Bash'},
                {value:1, name:'Vue.js'},
                {value:3, name:'Node.js'},
                {value:5, name:'NoSQL'},
                {value:5, name:'SQL'},
                {value:1, name:'Redis'}
            ]
        }
    ]
};


{% endecharts %}

### <i class="fa fa-volume-control-phone" aria-hidden="true"></i> &nbsp; Contact information

If you have any suggestion or need help, please contact me ASAP. The following data is encrypted by SHA1.

<i class="fa fa-weixin" aria-hidden="true" title="Tencent Wechat"></i> &nbsp;&nbsp;4fa51c6a597183b33f6ffac76a4b1373f396dccb
<i class="fa fa-qq" aria-hidden="true" title="Tencent QQ"></i> &nbsp;&nbsp;d523975ff914b873efd36c33c14b901fc77d09a6

### <i class="fa fa-share-alt" aria-hidden="true"></i> &nbsp;&nbsp; Professional exchange

[github](https://github.com/Forward2015) | [stackoverflow](http://stackoverflow.com/users/6122412/anderson-lu?tab=profile) | [segmentfault](segmentfault.com/u/fullstacklover) | [csdn](http://blog.csdn.net/qq_29329775) | [jianshu](http://www.jianshu.com/users/ad780125e18f/latest_articles)

---




###### This blog is built by [Hexo](https://hexo.io/). And theme by [Cho](https://github.com/pagecho)