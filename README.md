```

███╗   ██╗        ███╗   ███╗██████╗ ██╗   ██╗ █████╗ ██████╗ ██╗       ██████╗██╗     ██╗
████╗  ██║        ████╗ ████║╚════██╗██║   ██║██╔══██╗██╔══██╗██║      ██╔════╝██║     ██║
██╔██╗ ██║        ██╔████╔██║ █████╔╝██║   ██║╚█████╔╝██║  ██║██║█████╗██║     ██║     ██║
██║╚██╗██║        ██║╚██╔╝██║ ╚═══██╗██║   ██║██╔══██╗██║  ██║██║╚════╝██║     ██║     ██║
██║ ╚████║███████╗██║ ╚═╝ ██║██████╔╝╚██████╔╝╚█████╔╝██████╔╝███████╗ ╚██████╗███████╗██║
╚═╝  ╚═══╝╚══════╝╚═╝     ╚═╝╚═════╝  ╚═════╝  ╚════╝ ╚═════╝ ╚══════╝  ╚═════╝╚══════╝╚═╝
                                                                                          
```
---
[![img](https://img.shields.io/github/stars/nilaoda/N_m3u8DL-CLI?label=%E7%82%B9%E8%B5%9E)](https://github.com/nilaoda/N_m3u8DL-CLI)  [![img](https://img.shields.io/github/last-commit/nilaoda/N_m3u8DL-CLI?label=%E6%9C%80%E8%BF%91%E6%8F%90%E4%BA%A4)](https://github.com/nilaoda/N_m3u8DL-CLI)  [![img](https://img.shields.io/github/release/nilaoda/N_m3u8DL-CLI?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/nilaoda/N_m3u8DL-CLI/releases)  [![img](https://img.shields.io/github/license/nilaoda/N_m3u8DL-CLI?label=%E8%AE%B8%E5%8F%AF%E8%AF%81)](https://github.com/nilaoda/N_m3u8DL-CLI)  [![img](https://img.shields.io/badge/URL-%E7%94%A8%E6%88%B7%E6%96%87%E6%A1%A3-blue)](https://nilaoda.github.io/N_m3u8DL-CLI/)


# [ENGLISH VERSION](https://github.com/nilaoda/N_m3u8DL-CLI/blob/master/README_ENG.md)
 
# 关于开源
本项目已与2019年10月9日开源，采用MIT许可证，各取所需。

# 关于跨平台
本项目已通过`.NET Core`实现跨平台，理论支持Mac、Linux、Windows等平台，请移步：https://github.com/nilaoda/N_m3u8DL-CLI_Core

# N_m3u8DL-CLI
一个**简单易用的**m3u8下载器，下载地址：https://github.com/nilaoda/N_m3u8DL-CLI/releases  

支持下载m3u8链接或文件为`mp4`或`ts`格式，并提供丰富的命令行选项。
  * 支持`AES-128`加密自动解密
  * 支持多线程下载
  * 支持下载限速
  * 支持断点续传
  * 支持`Master List`
  * 支持直播流录制(`BETA`)
  * 支持腾讯、爱奇艺、优酷的`杜比视界m3u8`下载
  * 支持自定义`HTTP Headers`
  * 支持自动合并 (二进制合并或使用ffmpeg合并)
  * 支持选择下载`m3u8`中的指定时间段/分片内容
  * 支持下载路径为网络驱动器的情况
  * 支持下载外挂字幕轨道、音频轨道
  * 支持仅合并为音频
  * 自动使用系统代理（可禁止）
  * 针对国内视频网站`m3u8`进行了优化
  * 提供SimpleG简易的`GUI`生成常用参数



![运行截图](https://nilaoda.github.io/N_m3u8DL-CLI/source/images/%E7%9B%B4%E6%8E%A5%E4%BD%BF%E7%94%A8.gif)  

# 命令行选项
```
N_m3u8DL-CLI.exe <URL|JSON|FILE> [OPTIONS]  

    --workDir    Directory      设定程序工作目录
    --saveName   Filename       设定存储文件名(不包括后缀)
    --baseUrl    BaseUrl        设定Baseurl
    --headers    headers        设定请求头，格式 key:value 使用|分割不同的key&value
    --maxThreads Thread         设定程序的最大线程数(默认为32)
    --minThreads Thread         设定程序的最小线程数(默认为16)
    --retryCount Count          设定程序的重试次数(默认为15)
    --timeO


<!DOCTYPE HTML>
<html lang="zh-hans" >
    <head>
        <meta charset="UTF-8">
        <meta content="text/html; charset=utf-8" http-equiv="Content-Type">
        <title>JS获取m3u8 · N_m3u8DL-CLI文档</title>
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="description" content="">
        <meta name="generator" content="GitBook 3.2.3">
        <meta name="author" content="nilaoda">
        
        
    
    <link rel="stylesheet" href="gitbook/style.css">

    
            
                
                <link rel="stylesheet" href="gitbook/gitbook-plugin-donate/plugin.css">
                
            
                
                <link rel="stylesheet" href="gitbook/gitbook-plugin-highlight/website.css">
                
            
                
                <link rel="stylesheet" href="gitbook/gitbook-plugin-search/search.css">
                
            
                
                <link rel="stylesheet" href="gitbook/gitbook-plugin-fontsettings/website.css">
                
            
        

    

    
        
    
        
    
        
    
        
    
        
    
        
    

        
    
    
    
    <meta name="HandheldFriendly" content="true"/>
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <link rel="apple-touch-icon-precomposed" sizes="152x152" href="gitbook/images/apple-touch-icon-precomposed-152.png">
    <link rel="shortcut icon" href="gitbook/images/favicon.ico" type="image/x-icon">

    
    <link rel="next" href="LinetvParser.html" />
    
    

    <style>
    @media only screen and (max-width: 640px) {
        .book-header .hidden-mobile {
            display: none;
        }
    }
    </style>
    <script>
        window["gitbook-plugin-github-buttons"] = {"buttons":[{"user":"nilaoda","repo":"N_m3u8DL-CLI","type":"star","size":"small","count":true}]};
    </script>

    </head>
    <body>
        
<div class="book">
    <div class="book-summary">
        
            
<div id="book-search-input" role="search">
    <input type="text" placeholder="输入并搜索" />
</div>

            
                <nav role="navigation">
                


<ul class="summary">
    
    

    

    
        
        
    
        <li class="chapter " data-level="1.1" >
            
                <span>
            
                    
                    简介
            
                </span>
            

            
            <ul class="articles">
                
    
        <li class="chapter " data-level="1.1.1" data-path="./">
            
                <a href="./">
            
                    
                    简介
            
                </a>
            

            
        </li>
    

            </ul>
            
        </li>
    

    
        
        <li class="divider"></li>
        
        
    
        <li class="chapter " data-level="2.1" >
            
                <span>
            
                    
                    入门
            
                </span>
            

            
            <ul class="articles">
                
    
        <li class="chapter " data-level="2.1.1" data-path="Introductory.html">
            
                <a href="Introductory.html">
            
                    
                    使用入门
            
                </a>
            

            
        </li>
    

            </ul>
            
        </li>
    

    
        
        <li class="divider"></li>
        
        
    
        <li class="chapter " data-level="3.1" >
            
                <span>
            
                    
                    进阶
            
                </span>
            

            
            <ul class="articles">
                
    
        <li class="chapter " data-level="3.1.1" data-path="Advanced.html">
            
                <a href="Advanced.html">
            
                    
                    命令行参数
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="3.1.2" data-path="SimpleGUI.html">
            
                <a href="SimpleGUI.html">
            
                    
                    SimpleGUI
            
                </a>
            

            
        </li>
    

            </ul>
            
        </li>
    

    
        
        <li class="divider"></li>
        
        
    
        <li class="chapter " data-level="4.1" >
            
                <span>
            
                    
                    辅助
            
                </span>
            

            
            <ul class="articles">
                
    
        <li class="chapter active" data-level="4.1.1" data-path="GetM3u8.html">
            
                <a href="GetM3u8.html">
            
                    
                    JS获取m3u8
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="4.1.2" data-path="LinetvParser.html">
            
                <a href="LinetvParser.html">
            
                    
                    LinetvParser
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="4.1.3" data-path="ViuParser.html">
            
                <a href="ViuParser.html">
            
                    
                    ViuParser
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="4.1.4" data-path="VikiParser.html">
            
                <a href="VikiParser.html">
            
                    
                    VikiParser
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="4.1.5" data-path="M3U8URL2File.html">
            
                <a href="M3U8URL2File.html">
            
                    
                    M3U8URL2File
            
                </a>
            

            
        </li>
    

            </ul>
            
        </li>
    

    
        
        <li class="divider"></li>
        
        
    
        <li class="chapter " data-level="5.1" >
            
                <span>
            
                    
                    教程
            
                </span>
            

            
            <ul class="articles">
                
    
        <li class="chapter " data-level="5.1.1" data-path="qiqiuyun.html">
            
                <a href="qiqiuyun.html">
            
                    
                    气球云
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="5.1.2" data-path="aliyunEdu.html">
            
                <a href="aliyunEdu.html">
            
                    
                    阿里云大学
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="5.1.3" data-path="163study.html">
            
                <a href="163study.html">
            
                    
                    网易云课堂
            
                </a>
            

            
        </li>
    
        <li class="chapter " data-level="5.1.4" data-path="youku.html">
            
                <a href="youku.html">
            
                    
                    优酷视频DRM
            
                </a>
            

            
        </li>
    

            </ul>
            
        </li>
    

    

    <li class="divider"></li>

    <li>
        <a href="https://www.gitbook.com" target="blank" class="gitbook-link">
            本书使用 GitBook 发布
        </a>
    </li>
</ul>


                </nav>
            
        
    </div>

    <div class="book-body">
        
            <div class="body-inner">
                
                    

<div class="book-header" role="navigation">
    

    <!-- Title -->
    <h1>
        <i class="fa fa-circle-o-notch fa-spin"></i>
        <a href="." >JS获取m3u8</a>
    </h1>
</div>




                    <div class="page-wrapper" tabindex="-1" role="main">
                        <div class="page-inner">
                            
<div id="book-search-results">
    <div class="search-noresults">
    
                                <section class="normal markdown-section">
                                
                                <h1 id="&#x4F7F;&#x7528;javascript&#x83B7;&#x53D6;m3u8">&#x4F7F;&#x7528;Javascript&#x83B7;&#x53D6;m3u8</h1>
<p>&#x672C;&#x9875;&#x5C06;&#x63D0;&#x4F9B;&#x4E00;&#x4E9B;JS&#x4EE3;&#x7801;&#xFF0C;&#x5728;&#x60A8;&#x7684;&#x6D4F;&#x89C8;&#x5668;&#x8FD0;&#x884C;&#x8FD9;&#x4E9B;&#x4EE3;&#x7801;&#x6709;&#x52A9;&#x4E8E;&#x66F4;&#x5FEB;&#x7684;&#x83B7;&#x53D6;&#x5230;m3u8&#x94FE;&#x63A5;&#x7528;&#x4EE5;&#x4E0B;&#x8F7D;&#x3002;<br>&#x4E3A;&#x4E86;&#x65B9;&#x4FBF;&#x4F7F;&#x7528;&#xFF0C;&#x6700;&#x597D;&#x5C06;&#x4E0B;&#x9762;&#x7684;JS&#x4EE3;&#x7801;&#x5B58;&#x4E3A;&#x4E66;&#x7B7E;&#x3002; </p>
<p><strong>&#x6CE8;&#x610F;</strong>&#xFF1A;</p>
<ul>
<li>&#x6240;&#x6709;&#x4EE3;&#x7801;&#x4EC5;&#x4F9B;&#x5B66;&#x4E60;&#xFF0C;&#x8BF7;&#x52FF;&#x7528;&#x4E8E;&#x4EFB;&#x4F55;&#x8FDD;&#x6CD5;&#x9014;&#x5F84;   </li>
<li>&#x672C;&#x9875;Javascript&#x4EE3;&#x7801;&#x66F4;&#x65B0;&#x4E8E;2020&#x5E74;2&#x6708;27&#x65E5;&#xFF0C;&#x6D4B;&#x8BD5;&#x4E8E;360&#x6781;&#x901F;&#x6D4F;&#x89C8;&#x5668;&#xFF0C;&#x5176;&#x4ED6;&#x6D4F;&#x89C8;&#x5668;&#x4E0D;&#x4FDD;&#x8BC1;&#x6B63;&#x5E38;&#x4F7F;&#x7528;</li>
</ul>
<h2 id="&#x817E;&#x8BAF;&#x89C6;&#x9891;">&#x817E;&#x8BAF;&#x89C6;&#x9891;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:var a=prompt(PLAYER._DownloadMonitor.context.dataset.title,PLAYER._DownloadMonitor.context.dataset.ckc?PLAYER._DownloadMonitor.context.dataset.currentVideoUrl:PLAYER._DownloadMonitor.context.dataset.currentVideoUrl.replace(/:.*qq.com/g,&quot;://defaultts.tc.qq.com/defaultts.tc.qq.com&quot;));" target="_blank">&#x817E;&#x8BAF;&#x89C6;&#x9891;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> a=prompt(PLAYER._DownloadMonitor.context.dataset.title,PLAYER._DownloadMonitor.context.dataset.ckc?PLAYER._DownloadMonitor.context.dataset.currentVideoUrl:PLAYER._DownloadMonitor.context.dataset.currentVideoUrl.replace(<span class="hljs-regexp">/:.*qq.com/g</span>,<span class="hljs-string">&quot;://defaultts.tc.qq.com/defaultts.tc.qq.com&quot;</span>));
</code></pre>
<h2 id="&#x817E;&#x8BAF;&#x89C6;&#x9891;drm&#x5185;&#x5BB9;">&#x817E;&#x8BAF;&#x89C6;&#x9891;(DRM&#x5185;&#x5BB9;)</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:var m3u8Content=PLAYER._DownloadMonitor.context.dataset.playList[0].m3u8;var blob=new Blob([m3u8Content],{type:&quot;text/plain&quot;});var url=URL.createObjectURL(blob);var title=PLAYER._DownloadMonitor.context.dataset.title+&quot;.m3u8&quot;;var aLink=document.createElement(&quot;a&quot;);aLink.href=url;aLink.download=title;aLink.style.display=&quot;none&quot;;var event;if(window.MouseEvent){event=new MouseEvent(&quot;click&quot;)}else{event=document.createEvent(&quot;MouseEvents&quot;);event.initMouseEvent(&quot;click&quot;,true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event);" target="_blank">&#x817E;&#x8BAF;&#x89C6;&#x9891;(DRM&#x5185;&#x5BB9;)</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> m3u8Content=PLAYER._DownloadMonitor.context.dataset.playList[<span class="hljs-number">0</span>].m3u8;<span class="hljs-keyword">var</span> blob=<span class="hljs-keyword">new</span> Blob([m3u8Content],{type:<span class="hljs-string">&quot;text/plain&quot;</span>});<span class="hljs-keyword">var</span> url=URL.createObjectURL(blob);<span class="hljs-keyword">var</span> title=PLAYER._DownloadMonitor.context.dataset.title+<span class="hljs-string">&quot;[v+a].m3u8&quot;</span>;<span class="hljs-keyword">var</span> aLink=<span class="hljs-built_in">document</span>.createElement(<span class="hljs-string">&quot;a&quot;</span>);aLink.href=url;aLink.download=title;aLink.style.display=<span class="hljs-string">&quot;none&quot;</span>;<span class="hljs-keyword">var</span> event;<span class="hljs-keyword">if</span>(<span class="hljs-built_in">window</span>.MouseEvent){event=<span class="hljs-keyword">new</span> MouseEvent(<span class="hljs-string">&quot;click&quot;</span>)}<span class="hljs-keyword">else</span>{event=<span class="hljs-built_in">document</span>.createEvent(<span class="hljs-string">&quot;MouseEvents&quot;</span>);event.initMouseEvent(<span class="hljs-string">&quot;click&quot;</span>,<span class="hljs-literal">true</span>,<span class="hljs-literal">false</span>,<span class="hljs-built_in">window</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">null</span>)}aLink.dispatchEvent(event);
</code></pre>
<h2 id="&#x4F18;&#x9177;&#x89C6;&#x9891;">&#x4F18;&#x9177;&#x89C6;&#x9891;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:var url;var size=0;Array.from(videoPlayer.getData()._playlistData.stream).forEach(function(element,index,array){if(element.audio_lang==videoPlayer.getConfig().language&amp;&amp;element.size&gt;size){url=element.m3u8_url;size=element.size}});/*nilaoda*/var a=prompt(videoPlayer.getData()._videoData.title+&quot;_&quot;+videoPlayer.getConfig().language+&quot;_&quot;+(size/1024/1024).toFixed(2)+&quot;MB&quot;,url);" target="_blank">&#x4F18;&#x9177;&#x89C6;&#x9891;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> url;<span class="hljs-keyword">var</span> size=<span class="hljs-number">0</span>;<span class="hljs-built_in">Array</span>.from(videoPlayer.getData()._playlistData.stream).forEach(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">element,index,array</span>)</span>{<span class="hljs-keyword">if</span>(element.audio_lang==videoPlayer.getConfig().language&amp;&amp;element.size&gt;size){url=element.m3u8_url;size=element.size}});<span class="hljs-comment">/*nilaoda*/</span><span class="hljs-keyword">var</span> a=prompt(videoPlayer.getData()._videoData.title+<span class="hljs-string">&quot;_&quot;</span>+videoPlayer.getConfig().language+<span class="hljs-string">&quot;_&quot;</span>+(size/<span class="hljs-number">1024</span>/<span class="hljs-number">1024</span>).toFixed(<span class="hljs-number">2</span>)+<span class="hljs-string">&quot;MB&quot;</span>,url);
</code></pre>
<p><strong>&#x8865;&#x5145;&#x8BF4;&#x660E; (20200223)</strong>&#xFF1A;    </p>
<p>&#x76EE;&#x524D;&#x90E8;&#x5206;&#x4F18;&#x9177;&#x89C6;&#x9891;&#x4F7F;&#x7528;&#x4E86;&#x5176;&#x81EA;&#x6709;<code>Copyright DRM</code>&#x52A0;&#x5BC6;&#xFF0C;&#x4F7F;&#x7528;&#x672C;&#x8F6F;&#x4EF6;<code>2.5.0</code>&#x53CA;&#x4EE5;&#x4E0A;&#x7248;&#x672C;&#x53EF;&#x4EE5;&#x89E3;&#x5BC6;&#x3002;&#x4F7F;&#x7528;&#x4EE5;&#x4E0B;<code>JS</code>&#x83B7;&#x53D6;&#x4E13;&#x7528;&#x89E3;&#x5BC6;<code>KEY</code></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> a=prompt(videoPlayer.getData()._videoData.title + <span class="hljs-string">&quot;key&quot;</span>, btoa(<span class="hljs-built_in">String</span>.fromCharCode.apply(<span class="hljs-literal">null</span>, ____hexA)));
</code></pre>
<p>&#x90E8;&#x5206;&#x89C6;&#x9891;&#x4E3A;<code>cmaf</code>&#x52A0;&#x5BC6;&#xFF0C;&#x53C2;&#x8003;&#xFF1A;<a href="https://github.com/nilaoda/Blog/issues/19" target="_blank">https://github.com/nilaoda/Blog/issues/19</a></p>
<h2 id="&#x7231;&#x5947;&#x827A;&#x611B;&#x5947;&#x85DD;&#x89C6;&#x9891;">&#x7231;&#x5947;&#x827A;/&#x611B;&#x5947;&#x85DD;&#x89C6;&#x9891;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:try{var info=playerObject._player._core._movieinfo.originalData.data.program.video;info.forEach(function(item,index){if(item._selected){var m3u8Content=&quot;&quot;;if(item.m3u8==undefined){try{if(typeof(eval(cmd5x))==&quot;function&quot;){}}catch(e){var req1=new XMLHttpRequest();req1.open(&quot;GET&quot;,&quot;https://static.iqiyi.com/js/common/f6a3054843de4645b34d205a9f377d25.js&quot;,false);req1.onload=function(){var script=document.createElement(&quot;script&quot;);script.text=req1.responseText;document.getElementsByTagName(&quot;head&quot;)[0].appendChild(script)};req1.send(null)}var fs=item.fs;var content=&quot;#EXTM3U\n&quot;;fs.forEach(function(fs_i,fs_index){var url=fs_i.l;var prefix=&quot;https://data.video.iqiyi.com/videos&quot;;var api=prefix+url;try{var t=playerObject._player._core._movieinfo.originalData.data.boss.data.t;api=prefix+url+&quot;&#x2717;domain=1&amp;t=&quot;+t+&quot;&amp;QY00001=&quot;+/qd_uid=(\d+)/g.exec(url)[1]+&quot;&amp;ib=4&amp;ptime=0&amp;ibt=&quot;+cmd5x(t+/\/(\w{10,})/g.exec(url)[1])}catch(err){}var req=new XMLHttpRequest();req.overrideMimeType(&quot;application/json&quot;);req.open(&quot;GET&quot;,api,false);req.onload=function(){var jsonResponse=JSON.parse(req.responseText);content+=&quot;#EXTINF:0\n&quot;+jsonResponse[&quot;l&quot;]+&quot;\n&quot;};req.send(null)});content+=&quot;#EXT-X-ENDLIST&quot;;m3u8Content=content}else{m3u8Content=item.m3u8}var blob=new Blob([m3u8Content],{type:&quot;text/plain&quot;});var url=URL.createObjectURL(blob);var title=(document.title.indexOf(&quot;-&quot;)!=-1?document.title.substring(0,document.title.indexOf(&quot;-&quot;)):document.title.replace(/\s/,&quot;&quot;))+&quot;_&quot;+item.scrsz+&quot;_&quot;+(item.code==2?&quot;H264&quot;:&quot;H265&quot;)+&quot;_&quot;+document.getElementsByClassName(&quot;iqp-time-dur&quot;)[0].innerText.replace(/:/,&quot;.&quot;)+&quot;_&quot;+(item.vsize/1024/1024).toFixed(2)+&quot;MB.m3u8&quot;;var aLink=document.createElement(&quot;a&quot;);aLink.href=url;aLink.download=title;aLink.style.display=&quot;none&quot;;var event;if(window.MouseEvent){event=new MouseEvent(&quot;click&quot;)}else{event=document.createEvent(&quot;MouseEvents&quot;);event.initMouseEvent(&quot;click&quot;,true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)}})}catch(err){var info1=playerObject._player.package.engine.adproxy.engine.movieinfo.vidl;info1.forEach(function(item1,index1){if(item1.responseData!=undefined){var info=item1.responseData.data.program.video;info.forEach(function(item,index){if(item._selected){var m3u8Content=&quot;&quot;;if(item.m3u8==undefined){try{if(typeof(eval(cmd5x))==&quot;function&quot;){}}catch(e){var req1=new XMLHttpRequest();req1.open(&quot;GET&quot;,&quot;https://static.iqiyi.com/js/common/f6a3054843de4645b34d205a9f377d25.js&quot;,false);req1.onload=function(){var script=document.createElement(&quot;script&quot;);script.text=req1.responseText;document.getElementsByTagName(&quot;head&quot;)[0].appendChild(script)};req1.send(null)}var fs=item.fs;var content=&quot;#EXTM3U\n&quot;;fs.forEach(function(fs_i,fs_index){var url=fs_i.l;var prefix=&quot;https://data.video.iqiyi.com/videos&quot;;var api=prefix+url;try{var t=playerObject._player.package.engine.adproxy.engine.movieinfo.current.boss.data.t;api=prefix+url+&quot;&#x2717;domain=1&amp;t=&quot;+t+&quot;&amp;QY00001=&quot;+/qd_uid=(\d+)/g.exec(url)[1]+&quot;&amp;ib=4&amp;ptime=0&amp;ibt=&quot;+cmd5x(t+/\/(\w{10,})/g.exec(url)[1])}catch(err){console.error(err)}var req=new XMLHttpRequest();req.overrideMimeType(&quot;application/json&quot;);req.open(&quot;GET&quot;,api,false);req.onload=function(){var jsonResponse=JSON.parse(req.responseText);content+=&quot;#EXTINF:0\n&quot;+jsonResponse[&quot;l&quot;]+&quot;\n&quot;};req.send(null)});content+=&quot;#EXT-X-ENDLIST&quot;;m3u8Content=content}else{m3u8Content=item.m3u8}var blob=new Blob([m3u8Content],{type:&quot;text/plain&quot;});var url=URL.createObjectURL(blob);var title=(document.title.indexOf(&quot;-&quot;)!=-1?document.title.substring(0,document.title.indexOf(&quot;-&quot;)):document.title.replace(/\s/,&quot;&quot;))+&quot;_&quot;+item.scrsz+&quot;_&quot;+(item.code==2?&quot;H264&quot;:&quot;H265&quot;)+&quot;_&quot;+document.getElementsByClassName(&quot;iqp-time-dur&quot;)[0].innerText.replace(/:/,&quot;.&quot;)+&quot;_&quot;+(item.vsize/1024/1024).toFixed(2)+&quot;MB.m3u8&quot;;/*nilaoda*/var aLink=document.createElement(&quot;a&quot;);aLink.href=url;aLink.download=title;aLink.style.display=&quot;none&quot;;var event;if(window.MouseEvent){event=new MouseEvent(&quot;click&quot;)}else{event=document.createEvent(&quot;MouseEvents&quot;);event.initMouseEvent(&quot;click&quot;,true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)}})}})}" target="_blank">&#x7231;&#x5947;&#x827A;&#x89C6;&#x9891;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">try</span>{<span class="hljs-keyword">var</span> info=playerObject._player._core._movieinfo.originalData.data.program.video;info.forEach(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">item,index</span>)</span>{<span class="hljs-keyword">if</span>(item._selected){<span class="hljs-keyword">var</span> m3u8Content=<span class="hljs-string">&quot;&quot;</span>;<span class="hljs-keyword">if</span>(item.m3u8==<span class="hljs-literal">undefined</span>){<span class="hljs-keyword">try</span>{<span class="hljs-keyword">if</span>(<span class="hljs-keyword">typeof</span>(<span class="hljs-built_in">eval</span>(cmd5x))==<span class="hljs-string">&quot;function&quot;</span>){}}<span class="hljs-keyword">catch</span>(e){<span class="hljs-keyword">var</span> req1=<span class="hljs-keyword">new</span> XMLHttpRequest();req1.open(<span class="hljs-string">&quot;GET&quot;</span>,<span class="hljs-string">&quot;https://static.iqiyi.com/js/common/f6a3054843de4645b34d205a9f377d25.js&quot;</span>,<span class="hljs-literal">false</span>);req1.onload=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">var</span> script=<span class="hljs-built_in">document</span>.createElement(<span class="hljs-string">&quot;script&quot;</span>);script.text=req1.responseText;<span class="hljs-built_in">document</span>.getElementsByTagName(<span class="hljs-string">&quot;head&quot;</span>)[<span class="hljs-number">0</span>].appendChild(script)};req1.send(<span class="hljs-literal">null</span>)}<span class="hljs-keyword">var</span> fs=item.fs;<span class="hljs-keyword">var</span> content=<span class="hljs-string">&quot;#EXTM3U\n&quot;</span>;fs.forEach(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">fs_i,fs_index</span>)</span>{<span class="hljs-keyword">var</span> url=fs_i.l;<span class="hljs-keyword">var</span> prefix=<span class="hljs-string">&quot;https://data.video.iqiyi.com/videos&quot;</span>;<span class="hljs-keyword">var</span> api=prefix+url;<span class="hljs-keyword">try</span>{<span class="hljs-keyword">var</span> t=playerObject._player._core._movieinfo.originalData.data.boss.data.t;api=prefix+url+<span class="hljs-string">&quot;&amp;cross-domain=1&amp;t=&quot;</span>+t+<span class="hljs-string">&quot;&amp;QY00001=&quot;</span>+<span class="hljs-regexp">/qd_uid=(\d+)/g</span>.exec(url)[<span class="hljs-number">1</span>]+<span class="hljs-string">&quot;&amp;ib=4&amp;ptime=0&amp;ibt=&quot;</span>+cmd5x(t+<span class="hljs-regexp">/\/(\w{10,})/g</span>.exec(url)[<span class="hljs-number">1</span>])}<span class="hljs-keyword">catch</span>(err){}<span class="hljs-keyword">var</span> req=<span class="hljs-keyword">new</span> XMLHttpRequest();req.overrideMimeType(<span class="hljs-string">&quot;application/json&quot;</span>);req.open(<span class="hljs-string">&quot;GET&quot;</span>,api,<span class="hljs-literal">false</span>);req.onload=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">var</span> jsonResponse=<span class="hljs-built_in">JSON</span>.parse(req.responseText);content+=<span class="hljs-string">&quot;#EXTINF:0\n&quot;</span>+jsonResponse[<span class="hljs-string">&quot;l&quot;</span>]+<span class="hljs-string">&quot;\n&quot;</span>};req.send(<span class="hljs-literal">null</span>)});content+=<span class="hljs-string">&quot;#EXT-X-ENDLIST&quot;</span>;m3u8Content=content}<span class="hljs-keyword">else</span>{m3u8Content=item.m3u8}<span class="hljs-keyword">var</span> blob=<span class="hljs-keyword">new</span> Blob([m3u8Content],{type:<span class="hljs-string">&quot;text/plain&quot;</span>});<span class="hljs-keyword">var</span> url=URL.createObjectURL(blob);<span class="hljs-keyword">var</span> title=(<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)!=<span class="hljs-number">-1</span>?<span class="hljs-built_in">document</span>.title.substring(<span class="hljs-number">0</span>,<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)):<span class="hljs-built_in">document</span>.title.replace(<span class="hljs-regexp">/\s/</span>,<span class="hljs-string">&quot;&quot;</span>))+<span class="hljs-string">&quot;_&quot;</span>+item.scrsz+<span class="hljs-string">&quot;_&quot;</span>+(item.code==<span class="hljs-number">2</span>?<span class="hljs-string">&quot;H264&quot;</span>:<span class="hljs-string">&quot;H265&quot;</span>)+<span class="hljs-string">&quot;_&quot;</span>+<span class="hljs-built_in">document</span>.getElementsByClassName(<span class="hljs-string">&quot;iqp-time-dur&quot;</span>)[<span class="hljs-number">0</span>].innerText.replace(<span class="hljs-regexp">/:/</span>,<span class="hljs-string">&quot;.&quot;</span>)+<span class="hljs-string">&quot;_&quot;</span>+(item.vsize/<span class="hljs-number">1024</span>/<span class="hljs-number">1024</span>).toFixed(<span class="hljs-number">2</span>)+<span class="hljs-string">&quot;MB.m3u8&quot;</span>;<span class="hljs-keyword">var</span> aLink=<span class="hljs-built_in">document</span>.createElement(<span class="hljs-string">&quot;a&quot;</span>);aLink.href=url;aLink.download=title;aLink.style.display=<span class="hljs-string">&quot;none&quot;</span>;<span class="hljs-keyword">var</span> event;<span class="hljs-keyword">if</span>(<span class="hljs-built_in">window</span>.MouseEvent){event=<span class="hljs-keyword">new</span> MouseEvent(<span class="hljs-string">&quot;click&quot;</span>)}<span class="hljs-keyword">else</span>{event=<span class="hljs-built_in">document</span>.createEvent(<span class="hljs-string">&quot;MouseEvents&quot;</span>);event.initMouseEvent(<span class="hljs-string">&quot;click&quot;</span>,<span class="hljs-literal">true</span>,<span class="hljs-literal">false</span>,<span class="hljs-built_in">window</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">null</span>)}aLink.dispatchEvent(event)}})}<span class="hljs-keyword">catch</span>(err){<span class="hljs-keyword">var</span> info1=playerObject._player.package.engine.adproxy.engine.movieinfo.vidl;info1.forEach(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">item1,index1</span>)</span>{<span class="hljs-keyword">if</span>(item1.responseData!=<span class="hljs-literal">undefined</span>){<span class="hljs-keyword">var</span> info=item1.responseData.data.program.video;info.forEach(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">item,index</span>)</span>{<span class="hljs-keyword">if</span>(item._selected){<span class="hljs-keyword">var</span> m3u8Content=<span class="hljs-string">&quot;&quot;</span>;<span class="hljs-keyword">if</span>(item.m3u8==<span class="hljs-literal">undefined</span>){<span class="hljs-keyword">try</span>{<span class="hljs-keyword">if</span>(<span class="hljs-keyword">typeof</span>(<span class="hljs-built_in">eval</span>(cmd5x))==<span class="hljs-string">&quot;function&quot;</span>){}}<span class="hljs-keyword">catch</span>(e){<span class="hljs-keyword">var</span> req1=<span class="hljs-keyword">new</span> XMLHttpRequest();req1.open(<span class="hljs-string">&quot;GET&quot;</span>,<span class="hljs-string">&quot;https://static.iqiyi.com/js/common/f6a3054843de4645b34d205a9f377d25.js&quot;</span>,<span class="hljs-literal">false</span>);req1.onload=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">var</span> script=<span class="hljs-built_in">document</span>.createElement(<span class="hljs-string">&quot;script&quot;</span>);script.text=req1.responseText;<span class="hljs-built_in">document</span>.getElementsByTagName(<span class="hljs-string">&quot;head&quot;</span>)[<span class="hljs-number">0</span>].appendChild(script)};req1.send(<span class="hljs-literal">null</span>)}<span class="hljs-keyword">var</span> fs=item.fs;<span class="hljs-keyword">var</span> content=<span class="hljs-string">&quot;#EXTM3U\n&quot;</span>;fs.forEach(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">fs_i,fs_index</span>)</span>{<span class="hljs-keyword">var</span> url=fs_i.l;<span class="hljs-keyword">var</span> prefix=<span class="hljs-string">&quot;https://data.video.iqiyi.com/videos&quot;</span>;<span class="hljs-keyword">var</span> api=prefix+url;<span class="hljs-keyword">try</span>{<span class="hljs-keyword">var</span> t=playerObject._player.package.engine.adproxy.engine.movieinfo.current.boss.data.t;api=prefix+url+<span class="hljs-string">&quot;&amp;cross-domain=1&amp;t=&quot;</span>+t+<span class="hljs-string">&quot;&amp;QY00001=&quot;</span>+<span class="hljs-regexp">/qd_uid=(\d+)/g</span>.exec(url)[<span class="hljs-number">1</span>]+<span class="hljs-string">&quot;&amp;ib=4&amp;ptime=0&amp;ibt=&quot;</span>+cmd5x(t+<span class="hljs-regexp">/\/(\w{10,})/g</span>.exec(url)[<span class="hljs-number">1</span>])}<span class="hljs-keyword">catch</span>(err){<span class="hljs-built_in">console</span>.error(err)}<span class="hljs-keyword">var</span> req=<span class="hljs-keyword">new</span> XMLHttpRequest();req.overrideMimeType(<span class="hljs-string">&quot;application/json&quot;</span>);req.open(<span class="hljs-string">&quot;GET&quot;</span>,api,<span class="hljs-literal">false</span>);req.onload=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">var</span> jsonResponse=<span class="hljs-built_in">JSON</span>.parse(req.responseText);content+=<span class="hljs-string">&quot;#EXTINF:0\n&quot;</span>+jsonResponse[<span class="hljs-string">&quot;l&quot;</span>]+<span class="hljs-string">&quot;\n&quot;</span>};req.send(<span class="hljs-literal">null</span>)});content+=<span class="hljs-string">&quot;#EXT-X-ENDLIST&quot;</span>;m3u8Content=content}<span class="hljs-keyword">else</span>{m3u8Content=item.m3u8}<span class="hljs-keyword">var</span> blob=<span class="hljs-keyword">new</span> Blob([m3u8Content],{type:<span class="hljs-string">&quot;text/plain&quot;</span>});<span class="hljs-keyword">var</span> url=URL.createObjectURL(blob);<span class="hljs-keyword">var</span> title=(<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)!=<span class="hljs-number">-1</span>?<span class="hljs-built_in">document</span>.title.substring(<span class="hljs-number">0</span>,<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)):<span class="hljs-built_in">document</span>.title.replace(<span class="hljs-regexp">/\s/</span>,<span class="hljs-string">&quot;&quot;</span>))+<span class="hljs-string">&quot;_&quot;</span>+item.scrsz+<span class="hljs-string">&quot;_&quot;</span>+(item.code==<span class="hljs-number">2</span>?<span class="hljs-string">&quot;H264&quot;</span>:<span class="hljs-string">&quot;H265&quot;</span>)+<span class="hljs-string">&quot;_&quot;</span>+<span class="hljs-built_in">document</span>.getElementsByClassName(<span class="hljs-string">&quot;iqp-time-dur&quot;</span>)[<span class="hljs-number">0</span>].innerText.replace(<span class="hljs-regexp">/:/</span>,<span class="hljs-string">&quot;.&quot;</span>)+<span class="hljs-string">&quot;_&quot;</span>+(item.vsize/<span class="hljs-number">1024</span>/<span class="hljs-number">1024</span>).toFixed(<span class="hljs-number">2</span>)+<span class="hljs-string">&quot;MB.m3u8&quot;</span>;<span class="hljs-comment">/*nilaoda*/</span><span class="hljs-keyword">var</span> aLink=<span class="hljs-built_in">document</span>.createElement(<span class="hljs-string">&quot;a&quot;</span>);aLink.href=url;aLink.download=title;aLink.style.display=<span class="hljs-string">&quot;none&quot;</span>;<span class="hljs-keyword">var</span> event;<span class="hljs-keyword">if</span>(<span class="hljs-built_in">window</span>.MouseEvent){event=<span class="hljs-keyword">new</span> MouseEvent(<span class="hljs-string">&quot;click&quot;</span>)}<span class="hljs-keyword">else</span>{event=<span class="hljs-built_in">document</span>.createEvent(<span class="hljs-string">&quot;MouseEvents&quot;</span>);event.initMouseEvent(<span class="hljs-string">&quot;click&quot;</span>,<span class="hljs-literal">true</span>,<span class="hljs-literal">false</span>,<span class="hljs-built_in">window</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">null</span>)}aLink.dispatchEvent(event)}})}})}
</code></pre>
<h2 id="&#x7231;&#x5947;&#x827A;&#x611B;&#x5947;&#x85DD;-&#x675C;&#x6BD4;&#x97F3;&#x8F68;">&#x7231;&#x5947;&#x827A;/&#x611B;&#x5947;&#x85DD; &#x675C;&#x6BD4;&#x97F3;&#x8F68;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;3 B=A 1k();B.1j(&quot;1h&quot;,&quot;R://2I.M.C/1c/1Q/2b.1c&quot;,9);B.1b=7(){3 a=6.Q(&quot;19&quot;);a.1m=B.Z;6.V(&quot;U&quot;)[0].S(a)};B.18(z);7 G(a){3 b=6.2S.14(&quot;; &quot;);1K(3 i=0;i&lt;b.1Y;i++){3 c=b[i].14(&quot;=&quot;);J(a==c[0])K 1d(c[1])}K z}7 N(a,b){3 c=A 1U(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.22(c);J(r!=z){K 1d(r[2])}K z}3 L=8.2T.15.O(&quot;1L.M.C&quot;)!=-1?&quot;1M&quot;:&quot;1O&quot;;3 F=1R.1S.1T.1a.1X.1a.F;3 P=&quot;/1Z/20?1e=&quot;+F.1e+&quot;&amp;24=26&amp;27=28&amp;D=&quot;+F.D+&quot;&amp;L=&quot;+L+&quot;&amp;2d=0&amp;2e=1&amp;2h=&quot;+G(&quot;2i&quot;)+&quot;&amp;2x=2y&amp;2E=0&amp;T=&quot;+G(&quot;2M&quot;)+&quot;&amp;2R=0&amp;d=0&amp;s=&amp;1n=&amp;1o=&amp;1p=&amp;1q=1&amp;1r=0&amp;1s=0&amp;1t=&quot;+G(&quot;1u&quot;)+&quot;&amp;1v=1w&amp;1x=0&amp;1y=2&amp;1z=&quot;+(A 2Z()).1B()+&quot;&amp;1C=a&amp;1D=0&amp;1E=1F&amp;1G=1H&amp;1I=1&amp;1J=W&amp;Y=1&amp;Y=5&quot;;8.I=&quot;R://1N.11.M.C&quot;+P+&quot;&amp;1P=&quot;+12(P);13(8.I);7 13(a){3 b=6.V(&quot;U&quot;)[0];3 c=6.Q(&quot;19&quot;);c.L=a;b.S(c)}7 W(e){3 x=e.H.1V.1W;3 y=0;x.17(7(m,n){J(m.21){3 o=m.23;3 p=&quot;#25\\n&quot;;o.17(7(b,c){3 f=b.l;y+=b.b;3 h=&quot;R://H.11.M.C/29&quot;;3 i=h+f;2a{3 t=e.H.2c.H.t;3 j=N(&quot;D&quot;,8.I);3 k=N(&quot;T&quot;,8.I);i=h+f+&quot;&amp;t=&quot;+t+&quot;&amp;D=&quot;+j+&quot;&amp;2f=&quot;+/2g=(\\d+)/g.1f(f)[1]+&quot;&amp;2j=&quot;+k+&quot;&amp;2k=4&amp;2l=&quot;+12(t+/\\/(\\w{10,})/g.1f(f)[1])+&quot;&amp;2m=0&quot;}2n(2o){}3 l=A 1k();l.2p(&quot;2q/2r&quot;);l.1j(&quot;1h&quot;,i,9);l.1b=7(){3 a=2s.2t(l.Z);p+=&quot;#2u:0\\n&quot;+a[&quot;l&quot;]+&quot;\\n&quot;};l.18(z)});p+=&quot;#2v-X-2w&quot;;1g=p;3 q=A 2z([1g],{2A:&quot;1m/2B&quot;});3 r=2C.2D(q);3 s=(6.E.O(&quot;-&quot;)!=-1?6.E.2F(0,6.E.O(&quot;-&quot;)):6.E.2G(/\\s/,&quot;&quot;))+&quot;2H&quot;+(y/1i/1i).2J(2)+&quot;2K.2L&quot;;3 u=6.Q(&quot;a&quot;);u.15=r;u.2N=s;u.2O.2P=&quot;2Q&quot;;3 v;J(8.1l){v=A 1l(&quot;16&quot;)}2U{v=6.2V(&quot;2W&quot;);v.2X(&quot;16&quot;,2Y,9,8,0,0,0,0,0,9,9,9,9,0,z)}u.1A(v)}})}&apos;,62,186,&apos;|||var|||document|function|window|false||||||||||||||||||||||||||null|new|req1|com|vid|title|movieinfo|getCookie|data|dashUrl|if|return|src|iqiyi|getQueryString|indexOf|params|createElement|https|appendChild|k_uid|head|getElementsByTagName|NILAODA||ut|responseText||video|cmd5x|loadScript|split|href|click|forEach|send|script|engine|onload|js|unescape|tvid|exec|m3u8Content|GET|1024|open|XMLHttpRequest|MouseEvent|text|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|dispatchEvent|getTime|qdy|qds|k_ft1|1354994433|k_ft4|8196|k_ft5|callback|for|tw|01010031010010000000|cache|01010031010000000000|vf|common|playerObject|_player|package|RegExp|program|audio|adproxy|length|jp|dash|_selected|match|fs|bid|EXTM3U|300|abid|500|videos|try|f6a3054843de4645b34d205a9f377d25|boss_ts|vt|rs|QY00001|qd_uid|uid|P00003|su|ib|ibt|ptime|catch|err|overrideMimeType|application|json|JSON|parse|EXTINF|EXT|ENDLIST|ori|pcw|Blob|type|plain|URL|createObjectURL|ps|substring|replace|_dolby_|static|toFixed|MB|m3u8|QC005|download|style|display|none|pt|cookie|location|else|createEvent|MouseEvents|initMouseEvent|true|Date&apos;.split(&apos;|&apos;),0,{}))" target="_blank">&#x7231;&#x5947;&#x827A;&#x675C;&#x6BD4;&#x97F3;&#x8F68;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;3 B=A 1k();B.1j(&quot;1h&quot;,&quot;R://2I.M.C/1c/1Q/2b.1c&quot;,9);B.1b=7(){3 a=6.Q(&quot;19&quot;);a.1m=B.Z;6.V(&quot;U&quot;)[0].S(a)};B.18(z);7 G(a){3 b=6.2S.14(&quot;; &quot;);1K(3 i=0;i&lt;b.1Y;i++){3 c=b[i].14(&quot;=&quot;);J(a==c[0])K 1d(c[1])}K z}7 N(a,b){3 c=A 1U(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.22(c);J(r!=z){K 1d(r[2])}K z}3 L=8.2T.15.O(&quot;1L.M.C&quot;)!=-1?&quot;1M&quot;:&quot;1O&quot;;3 F=1R.1S.1T.1a.1X.1a.F;3 P=&quot;/1Z/20?1e=&quot;+F.1e+&quot;&amp;24=26&amp;27=28&amp;D=&quot;+F.D+&quot;&amp;L=&quot;+L+&quot;&amp;2d=0&amp;2e=1&amp;2h=&quot;+G(&quot;2i&quot;)+&quot;&amp;2x=2y&amp;2E=0&amp;T=&quot;+G(&quot;2M&quot;)+&quot;&amp;2R=0&amp;d=0&amp;s=&amp;1n=&amp;1o=&amp;1p=&amp;1q=1&amp;1r=0&amp;1s=0&amp;1t=&quot;+G(&quot;1u&quot;)+&quot;&amp;1v=1w&amp;1x=0&amp;1y=2&amp;1z=&quot;+(A 2Z()).1B()+&quot;&amp;1C=a&amp;1D=0&amp;1E=1F&amp;1G=1H&amp;1I=1&amp;1J=W&amp;Y=1&amp;Y=5&quot;;8.I=&quot;R://1N.11.M.C&quot;+P+&quot;&amp;1P=&quot;+12(P);13(8.I);7 13(a){3 b=6.V(&quot;U&quot;)[0];3 c=6.Q(&quot;19&quot;);c.L=a;b.S(c)}7 W(e){3 x=e.H.1V.1W;3 y=0;x.17(7(m,n){J(m.21){3 o=m.23;3 p=&quot;#25\\n&quot;;o.17(7(b,c){3 f=b.l;y+=b.b;3 h=&quot;R://H.11.M.C/29&quot;;3 i=h+f;2a{3 t=e.H.2c.H.t;3 j=N(&quot;D&quot;,8.I);3 k=N(&quot;T&quot;,8.I);i=h+f+&quot;&amp;t=&quot;+t+&quot;&amp;D=&quot;+j+&quot;&amp;2f=&quot;+/2g=(\\d+)/g.1f(f)[1]+&quot;&amp;2j=&quot;+k+&quot;&amp;2k=4&amp;2l=&quot;+12(t+/\\/(\\w{10,})/g.1f(f)[1])+&quot;&amp;2m=0&quot;}2n(2o){}3 l=A 1k();l.2p(&quot;2q/2r&quot;);l.1j(&quot;1h&quot;,i,9);l.1b=7(){3 a=2s.2t(l.Z);p+=&quot;#2u:0\\n&quot;+a[&quot;l&quot;]+&quot;\\n&quot;};l.18(z)});p+=&quot;#2v-X-2w&quot;;1g=p;3 q=A 2z([1g],{2A:&quot;1m/2B&quot;});3 r=2C.2D(q);3 s=(6.E.O(&quot;-&quot;)!=-1?6.E.2F(0,6.E.O(&quot;-&quot;)):6.E.2G(/\\s/,&quot;&quot;))+&quot;2H&quot;+(y/1i/1i).2J(2)+&quot;2K.2L&quot;;3 u=6.Q(&quot;a&quot;);u.15=r;u.2N=s;u.2O.2P=&quot;2Q&quot;;3 v;J(8.1l){v=A 1l(&quot;16&quot;)}2U{v=6.2V(&quot;2W&quot;);v.2X(&quot;16&quot;,2Y,9,8,0,0,0,0,0,9,9,9,9,0,z)}u.1A(v)}})}&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">186</span>,<span class="hljs-string">&apos;|||var|||document|function|window|false||||||||||||||||||||||||||null|new|req1|com|vid|title|movieinfo|getCookie|data|dashUrl|if|return|src|iqiyi|getQueryString|indexOf|params|createElement|https|appendChild|k_uid|head|getElementsByTagName|NILAODA||ut|responseText||video|cmd5x|loadScript|split|href|click|forEach|send|script|engine|onload|js|unescape|tvid|exec|m3u8Content|GET|1024|open|XMLHttpRequest|MouseEvent|text|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|dispatchEvent|getTime|qdy|qds|k_ft1|1354994433|k_ft4|8196|k_ft5|callback|for|tw|01010031010010000000|cache|01010031010000000000|vf|common|playerObject|_player|package|RegExp|program|audio|adproxy|length|jp|dash|_selected|match|fs|bid|EXTM3U|300|abid|500|videos|try|f6a3054843de4645b34d205a9f377d25|boss_ts|vt|rs|QY00001|qd_uid|uid|P00003|su|ib|ibt|ptime|catch|err|overrideMimeType|application|json|JSON|parse|EXTINF|EXT|ENDLIST|ori|pcw|Blob|type|plain|URL|createObjectURL|ps|substring|replace|_dolby_|static|toFixed|MB|m3u8|QC005|download|style|display|none|pt|cookie|location|else|createEvent|MouseEvents|initMouseEvent|true|Date&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="&#x7231;&#x5947;&#x827A;&#x611B;&#x5947;&#x85DD;-4k-h264">&#x7231;&#x5947;&#x827A;/&#x611B;&#x5947;&#x85DD; 4K H264</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;3 j=k 1e();j.1E(&quot;1J&quot;,&quot;S://14.y.x/N/1K/1W.N&quot;,7);j.11=6(){3 a=5.w(&quot;E&quot;);a.z=j.2i;5.L(&quot;F&quot;)[0].B(a)};j.1f(9);6 m(a){3 b=5.1P.G(&quot;; &quot;);1Y(3 i=0;i&lt;b.W;i++){3 c=b[i].G(&quot;=&quot;);q(a==c[0])t R(c[1])}t 9}6 1g(a,b){3 c=k 1C(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1G(c);q(r!=9){t R(r[2])}t 9}3 p=8.1V.P.u(&quot;1Z.y.x&quot;)!=-1?&quot;2a&quot;:&quot;2d&quot;;3 n=2j.2k.V.A.X.A.n;3 v=&quot;/Z/10?C=&quot;+n.C+&quot;&amp;12=13&amp;D=&quot;+n.D+&quot;&amp;p=&quot;+p+&quot;&amp;15=0&amp;16=1&amp;17=&quot;+m(&quot;18&quot;)+&quot;&amp;19=1a&amp;1b=0&amp;1c=&quot;+m(&quot;1d&quot;)+&quot;&amp;2q=0&amp;d=0&amp;s=&amp;1h=&amp;1i=&amp;1j=&amp;1k=1&amp;1l=0&amp;1m=0&amp;1n=&quot;+m(&quot;1o&quot;)+&quot;&amp;1p=1q&amp;1r=0&amp;1s=2&amp;1t=&quot;+(k 1u()).1v()+&quot;&amp;1w=a&amp;1x=0&amp;1y=1z&amp;1A=4&amp;1B=H&amp;1D=1&quot;;8.I=&quot;S://1F.J.y.x&quot;+v+&quot;&amp;1H=&quot;+1I(v);K(8.I);6 K(a){3 b=5.L(&quot;F&quot;)[0];3 c=5.w(&quot;E&quot;);c.p=a;b.B(c)}6 H(e){3 i=e.1L.1M.J;i.1N(6(a,b){q(a.1O){3 c=a.M;3 d=k 1Q([c],{1R:&quot;z/1S&quot;});3 e=1T.1U(d);3 f=(5.o.u(&quot;-&quot;)!=-1?5.o.1X(0,5.o.u(&quot;-&quot;)):5.o.O(/\\s/,&quot;&quot;))+&quot;l&quot;+a.20+&quot;l&quot;+(a.21==2?&quot;22&quot;:&quot;23&quot;)+&quot;l&quot;+5.24(&quot;25-26-27&quot;)[0].28.O(/:/,&quot;.&quot;)+&quot;l&quot;+(a.29/Q/Q).2b(2)+&quot;2c.M&quot;;3 g=5.w(&quot;a&quot;);g.P=e;g.2e=f;g.2f.2g=&quot;2h&quot;;3 h;q(8.T){h=k T(&quot;U&quot;)}2l{h=5.2m(&quot;2n&quot;);h.2o(&quot;U&quot;,2p,7,8,0,0,0,0,0,7,7,7,7,0,9)}g.Y(h)}})}&apos;,62,151,&apos;|||var||document|function|false|window|null||||||||||req1|new|_|getCookie|movieinfo|title|src|if|||return|indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|800|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|QC005|XMLHttpRequest|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8196|k_ft4|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|pt&apos;.split(&apos;|&apos;),0,{}))" target="_blank">&#x7231;&#x5947;&#x827A;4K_H264</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;3 j=k 1e();j.1E(&quot;1J&quot;,&quot;S://14.y.x/N/1K/1W.N&quot;,7);j.11=6(){3 a=5.w(&quot;E&quot;);a.z=j.2i;5.L(&quot;F&quot;)[0].B(a)};j.1f(9);6 m(a){3 b=5.1P.G(&quot;; &quot;);1Y(3 i=0;i&lt;b.W;i++){3 c=b[i].G(&quot;=&quot;);q(a==c[0])t R(c[1])}t 9}6 1g(a,b){3 c=k 1C(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1G(c);q(r!=9){t R(r[2])}t 9}3 p=8.1V.P.u(&quot;1Z.y.x&quot;)!=-1?&quot;2a&quot;:&quot;2d&quot;;3 n=2j.2k.V.A.X.A.n;3 v=&quot;/Z/10?C=&quot;+n.C+&quot;&amp;12=13&amp;D=&quot;+n.D+&quot;&amp;p=&quot;+p+&quot;&amp;15=0&amp;16=1&amp;17=&quot;+m(&quot;18&quot;)+&quot;&amp;19=1a&amp;1b=0&amp;1c=&quot;+m(&quot;1d&quot;)+&quot;&amp;2q=0&amp;d=0&amp;s=&amp;1h=&amp;1i=&amp;1j=&amp;1k=1&amp;1l=0&amp;1m=0&amp;1n=&quot;+m(&quot;1o&quot;)+&quot;&amp;1p=1q&amp;1r=0&amp;1s=2&amp;1t=&quot;+(k 1u()).1v()+&quot;&amp;1w=a&amp;1x=0&amp;1y=1z&amp;1A=4&amp;1B=H&amp;1D=1&quot;;8.I=&quot;S://1F.J.y.x&quot;+v+&quot;&amp;1H=&quot;+1I(v);K(8.I);6 K(a){3 b=5.L(&quot;F&quot;)[0];3 c=5.w(&quot;E&quot;);c.p=a;b.B(c)}6 H(e){3 i=e.1L.1M.J;i.1N(6(a,b){q(a.1O){3 c=a.M;3 d=k 1Q([c],{1R:&quot;z/1S&quot;});3 e=1T.1U(d);3 f=(5.o.u(&quot;-&quot;)!=-1?5.o.1X(0,5.o.u(&quot;-&quot;)):5.o.O(/\\s/,&quot;&quot;))+&quot;l&quot;+a.20+&quot;l&quot;+(a.21==2?&quot;22&quot;:&quot;23&quot;)+&quot;l&quot;+5.24(&quot;25-26-27&quot;)[0].28.O(/:/,&quot;.&quot;)+&quot;l&quot;+(a.29/Q/Q).2b(2)+&quot;2c.M&quot;;3 g=5.w(&quot;a&quot;);g.P=e;g.2e=f;g.2f.2g=&quot;2h&quot;;3 h;q(8.T){h=k T(&quot;U&quot;)}2l{h=5.2m(&quot;2n&quot;);h.2o(&quot;U&quot;,2p,7,8,0,0,0,0,0,7,7,7,7,0,9)}g.Y(h)}})}&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">151</span>,<span class="hljs-string">&apos;|||var||document|function|false|window|null||||||||||req1|new|_|getCookie|movieinfo|title|src|if|||return|indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|800|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|QC005|XMLHttpRequest|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8196|k_ft4|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|pt&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="&#x7231;&#x5947;&#x827A;&#x611B;&#x5947;&#x85DD;-4k-h265">&#x7231;&#x5947;&#x827A;/&#x611B;&#x5947;&#x85DD; 4K H265</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;3 9=j 1c();9.1C(&quot;1H&quot;,&quot;R://13.x.w/M/1I/1U.M&quot;,6);9.10=5(){3 a=4.v(&quot;D&quot;);a.y=9.2g;4.K(&quot;E&quot;)[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F(&quot;; &quot;);1W(3 i=0;i&lt;b.V;i++){3 c=b[i].F(&quot;=&quot;);p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t(&quot;1X.x.w&quot;)!=-1?&quot;28&quot;:&quot;2b&quot;;3 m=2h.2i.U.z.W.z.m;3 u=&quot;/Y/Z?B=&quot;+m.B+&quot;&amp;11=12&amp;C=&quot;+m.C+&quot;&amp;o=&quot;+o+&quot;&amp;14=0&amp;15=1&amp;16=&quot;+l(&quot;17&quot;)+&quot;&amp;18=19&amp;1a=0&amp;1b=&quot;+l(&quot;2o&quot;)+&quot;&amp;1d=0&amp;d=0&amp;s=&amp;1g=&amp;1h=&amp;1i=&amp;1j=1&amp;1k=0&amp;1l=0&amp;1m=&quot;+l(&quot;1n&quot;)+&quot;&amp;1o=1p&amp;1q=0&amp;1r=2&amp;1s=&quot;+(j 1t()).1u()+&quot;&amp;1v=a&amp;1w=0&amp;1x=1y&amp;1z=G&amp;1B=1&quot;;7.H=&quot;R://1D.I.x.w&quot;+u+&quot;&amp;1F=&quot;+1G(u);J(7.H);5 J(a){3 b=4.K(&quot;E&quot;)[0];3 c=4.v(&quot;D&quot;);c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:&quot;y/1Q&quot;});3 e=1R.1S(d);3 f=(4.n.t(&quot;-&quot;)!=-1?4.n.1V(0,4.n.t(&quot;-&quot;)):4.n.N(/\\s/,&quot;&quot;))+&quot;k&quot;+a.1Y+&quot;k&quot;+(a.1Z==2?&quot;20&quot;:&quot;21&quot;)+&quot;k&quot;+4.22(&quot;23-24-25&quot;)[0].26.N(/:/,&quot;.&quot;)+&quot;k&quot;+(a.27/P/P).29(2)+&quot;2a.L&quot;;3 g=4.v(&quot;a&quot;);g.O=e;g.2c=f;g.2d.2e=&quot;2f&quot;;3 h;p(7.S){h=j S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}&apos;,62,149,&apos;|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|800|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005&apos;.split(&apos;|&apos;),0,{}))" target="_blank">&#x7231;&#x5947;&#x827A;4K_H265</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;3 9=j 1c();9.1C(&quot;1H&quot;,&quot;R://13.x.w/M/1I/1U.M&quot;,6);9.10=5(){3 a=4.v(&quot;D&quot;);a.y=9.2g;4.K(&quot;E&quot;)[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F(&quot;; &quot;);1W(3 i=0;i&lt;b.V;i++){3 c=b[i].F(&quot;=&quot;);p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t(&quot;1X.x.w&quot;)!=-1?&quot;28&quot;:&quot;2b&quot;;3 m=2h.2i.U.z.W.z.m;3 u=&quot;/Y/Z?B=&quot;+m.B+&quot;&amp;11=12&amp;C=&quot;+m.C+&quot;&amp;o=&quot;+o+&quot;&amp;14=0&amp;15=1&amp;16=&quot;+l(&quot;17&quot;)+&quot;&amp;18=19&amp;1a=0&amp;1b=&quot;+l(&quot;2o&quot;)+&quot;&amp;1d=0&amp;d=0&amp;s=&amp;1g=&amp;1h=&amp;1i=&amp;1j=1&amp;1k=0&amp;1l=0&amp;1m=&quot;+l(&quot;1n&quot;)+&quot;&amp;1o=1p&amp;1q=0&amp;1r=2&amp;1s=&quot;+(j 1t()).1u()+&quot;&amp;1v=a&amp;1w=0&amp;1x=1y&amp;1z=G&amp;1B=1&quot;;7.H=&quot;R://1D.I.x.w&quot;+u+&quot;&amp;1F=&quot;+1G(u);J(7.H);5 J(a){3 b=4.K(&quot;E&quot;)[0];3 c=4.v(&quot;D&quot;);c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:&quot;y/1Q&quot;});3 e=1R.1S(d);3 f=(4.n.t(&quot;-&quot;)!=-1?4.n.1V(0,4.n.t(&quot;-&quot;)):4.n.N(/\\s/,&quot;&quot;))+&quot;k&quot;+a.1Y+&quot;k&quot;+(a.1Z==2?&quot;20&quot;:&quot;21&quot;)+&quot;k&quot;+4.22(&quot;23-24-25&quot;)[0].26.N(/:/,&quot;.&quot;)+&quot;k&quot;+(a.27/P/P).29(2)+&quot;2a.L&quot;;3 g=4.v(&quot;a&quot;);g.O=e;g.2c=f;g.2d.2e=&quot;2f&quot;;3 h;p(7.S){h=j S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">149</span>,<span class="hljs-string">&apos;|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|800|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="&#x7231;&#x5947;&#x827A;&#x611B;&#x5947;&#x85DD;-1080p-h265-&#x4F4E;&#x7801;">&#x7231;&#x5947;&#x827A;/&#x611B;&#x5947;&#x85DD; 1080P H265 (&#x4F4E;&#x7801;)</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;3 9=j 1c();9.1C(&quot;1H&quot;,&quot;R://13.x.w/M/1I/1U.M&quot;,6);9.10=5(){3 a=4.v(&quot;D&quot;);a.y=9.2g;4.K(&quot;E&quot;)[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F(&quot;; &quot;);1W(3 i=0;i&lt;b.V;i++){3 c=b[i].F(&quot;=&quot;);p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t(&quot;1X.x.w&quot;)!=-1?&quot;28&quot;:&quot;2b&quot;;3 m=2h.2i.U.z.W.z.m;3 u=&quot;/Y/Z?B=&quot;+m.B+&quot;&amp;11=12&amp;C=&quot;+m.C+&quot;&amp;o=&quot;+o+&quot;&amp;14=0&amp;15=1&amp;16=&quot;+l(&quot;17&quot;)+&quot;&amp;18=19&amp;1a=0&amp;1b=&quot;+l(&quot;2o&quot;)+&quot;&amp;1d=0&amp;d=0&amp;s=&amp;1g=&amp;1h=&amp;1i=&amp;1j=1&amp;1k=0&amp;1l=0&amp;1m=&quot;+l(&quot;1n&quot;)+&quot;&amp;1o=1p&amp;1q=0&amp;1r=2&amp;1s=&quot;+(j 1t()).1u()+&quot;&amp;1v=a&amp;1w=0&amp;1x=1y&amp;1z=G&amp;1B=1&quot;;7.H=&quot;R://1D.I.x.w&quot;+u+&quot;&amp;1F=&quot;+1G(u);J(7.H);5 J(a){3 b=4.K(&quot;E&quot;)[0];3 c=4.v(&quot;D&quot;);c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:&quot;y/1Q&quot;});3 e=1R.1S(d);3 f=(4.n.t(&quot;-&quot;)!=-1?4.n.1V(0,4.n.t(&quot;-&quot;)):4.n.N(/\\s/,&quot;&quot;))+&quot;k&quot;+a.1Y+&quot;k&quot;+(a.1Z==2?&quot;20&quot;:&quot;21&quot;)+&quot;k&quot;+4.22(&quot;23-24-25&quot;)[0].26.N(/:/,&quot;.&quot;)+&quot;k&quot;+(a.27/P/P).29(2)+&quot;2a.L&quot;;3 g=4.v(&quot;a&quot;);g.O=e;g.2c=f;g.2d.2e=&quot;2f&quot;;3 h;p(7.S){h=j S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}&apos;,62,149,&apos;|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|600|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005&apos;.split(&apos;|&apos;),0,{}))" target="_blank">&#x7231;&#x5947;&#x827A;1080P_H265(&#x4F4E;&#x7801;)</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;3 9=j 1c();9.1C(&quot;1H&quot;,&quot;R://13.x.w/M/1I/1U.M&quot;,6);9.10=5(){3 a=4.v(&quot;D&quot;);a.y=9.2g;4.K(&quot;E&quot;)[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F(&quot;; &quot;);1W(3 i=0;i&lt;b.V;i++){3 c=b[i].F(&quot;=&quot;);p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t(&quot;1X.x.w&quot;)!=-1?&quot;28&quot;:&quot;2b&quot;;3 m=2h.2i.U.z.W.z.m;3 u=&quot;/Y/Z?B=&quot;+m.B+&quot;&amp;11=12&amp;C=&quot;+m.C+&quot;&amp;o=&quot;+o+&quot;&amp;14=0&amp;15=1&amp;16=&quot;+l(&quot;17&quot;)+&quot;&amp;18=19&amp;1a=0&amp;1b=&quot;+l(&quot;2o&quot;)+&quot;&amp;1d=0&amp;d=0&amp;s=&amp;1g=&amp;1h=&amp;1i=&amp;1j=1&amp;1k=0&amp;1l=0&amp;1m=&quot;+l(&quot;1n&quot;)+&quot;&amp;1o=1p&amp;1q=0&amp;1r=2&amp;1s=&quot;+(j 1t()).1u()+&quot;&amp;1v=a&amp;1w=0&amp;1x=1y&amp;1z=G&amp;1B=1&quot;;7.H=&quot;R://1D.I.x.w&quot;+u+&quot;&amp;1F=&quot;+1G(u);J(7.H);5 J(a){3 b=4.K(&quot;E&quot;)[0];3 c=4.v(&quot;D&quot;);c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:&quot;y/1Q&quot;});3 e=1R.1S(d);3 f=(4.n.t(&quot;-&quot;)!=-1?4.n.1V(0,4.n.t(&quot;-&quot;)):4.n.N(/\\s/,&quot;&quot;))+&quot;k&quot;+a.1Y+&quot;k&quot;+(a.1Z==2?&quot;20&quot;:&quot;21&quot;)+&quot;k&quot;+4.22(&quot;23-24-25&quot;)[0].26.N(/:/,&quot;.&quot;)+&quot;k&quot;+(a.27/P/P).29(2)+&quot;2a.L&quot;;3 g=4.v(&quot;a&quot;);g.O=e;g.2c=f;g.2d.2e=&quot;2f&quot;;3 h;p(7.S){h=j S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">149</span>,<span class="hljs-string">&apos;|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|600|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="&#x7231;&#x5947;&#x827A;&#x611B;&#x5947;&#x85DD;-1080p-h265-&#x4E2D;&#x7801;">&#x7231;&#x5947;&#x827A;/&#x611B;&#x5947;&#x85DD; 1080P H265 (&#x4E2D;&#x7801;)</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;3 9=j 1c();9.1C(&quot;1H&quot;,&quot;R://13.x.w/M/1I/1U.M&quot;,6);9.10=5(){3 a=4.v(&quot;D&quot;);a.y=9.2g;4.K(&quot;E&quot;)[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F(&quot;; &quot;);1W(3 i=0;i&lt;b.V;i++){3 c=b[i].F(&quot;=&quot;);p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t(&quot;1X.x.w&quot;)!=-1?&quot;28&quot;:&quot;2b&quot;;3 m=2h.2i.U.z.W.z.m;3 u=&quot;/Y/Z?B=&quot;+m.B+&quot;&amp;11=12&amp;C=&quot;+m.C+&quot;&amp;o=&quot;+o+&quot;&amp;14=0&amp;15=1&amp;16=&quot;+l(&quot;17&quot;)+&quot;&amp;18=19&amp;1a=0&amp;1b=&quot;+l(&quot;2o&quot;)+&quot;&amp;1d=0&amp;d=0&amp;s=&amp;1g=&amp;1h=&amp;1i=&amp;1j=1&amp;1k=0&amp;1l=0&amp;1m=&quot;+l(&quot;1n&quot;)+&quot;&amp;1o=1p&amp;1q=0&amp;1r=2&amp;1s=&quot;+(j 1t()).1u()+&quot;&amp;1v=a&amp;1w=0&amp;1x=1y&amp;1z=G&amp;1B=1&quot;;7.H=&quot;R://1D.I.x.w&quot;+u+&quot;&amp;1F=&quot;+1G(u);J(7.H);5 J(a){3 b=4.K(&quot;E&quot;)[0];3 c=4.v(&quot;D&quot;);c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:&quot;y/1Q&quot;});3 e=1R.1S(d);3 f=(4.n.t(&quot;-&quot;)!=-1?4.n.1V(0,4.n.t(&quot;-&quot;)):4.n.N(/\\s/,&quot;&quot;))+&quot;k&quot;+a.1Y+&quot;k&quot;+(a.1Z==2?&quot;20&quot;:&quot;21&quot;)+&quot;k&quot;+4.22(&quot;23-24-25&quot;)[0].26.N(/:/,&quot;.&quot;)+&quot;k&quot;+(a.27/P/P).29(2)+&quot;2a.L&quot;;3 g=4.v(&quot;a&quot;);g.O=e;g.2c=f;g.2d.2e=&quot;2f&quot;;3 h;p(7.S){h=j S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}&apos;,62,149,&apos;|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|620|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005&apos;.split(&apos;|&apos;),0,{}))" target="_blank">&#x7231;&#x5947;&#x827A;1080P_H265(&#x4E2D;&#x7801;)</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;3 9=j 1c();9.1C(&quot;1H&quot;,&quot;R://13.x.w/M/1I/1U.M&quot;,6);9.10=5(){3 a=4.v(&quot;D&quot;);a.y=9.2g;4.K(&quot;E&quot;)[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F(&quot;; &quot;);1W(3 i=0;i&lt;b.V;i++){3 c=b[i].F(&quot;=&quot;);p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t(&quot;1X.x.w&quot;)!=-1?&quot;28&quot;:&quot;2b&quot;;3 m=2h.2i.U.z.W.z.m;3 u=&quot;/Y/Z?B=&quot;+m.B+&quot;&amp;11=12&amp;C=&quot;+m.C+&quot;&amp;o=&quot;+o+&quot;&amp;14=0&amp;15=1&amp;16=&quot;+l(&quot;17&quot;)+&quot;&amp;18=19&amp;1a=0&amp;1b=&quot;+l(&quot;2o&quot;)+&quot;&amp;1d=0&amp;d=0&amp;s=&amp;1g=&amp;1h=&amp;1i=&amp;1j=1&amp;1k=0&amp;1l=0&amp;1m=&quot;+l(&quot;1n&quot;)+&quot;&amp;1o=1p&amp;1q=0&amp;1r=2&amp;1s=&quot;+(j 1t()).1u()+&quot;&amp;1v=a&amp;1w=0&amp;1x=1y&amp;1z=G&amp;1B=1&quot;;7.H=&quot;R://1D.I.x.w&quot;+u+&quot;&amp;1F=&quot;+1G(u);J(7.H);5 J(a){3 b=4.K(&quot;E&quot;)[0];3 c=4.v(&quot;D&quot;);c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:&quot;y/1Q&quot;});3 e=1R.1S(d);3 f=(4.n.t(&quot;-&quot;)!=-1?4.n.1V(0,4.n.t(&quot;-&quot;)):4.n.N(/\\s/,&quot;&quot;))+&quot;k&quot;+a.1Y+&quot;k&quot;+(a.1Z==2?&quot;20&quot;:&quot;21&quot;)+&quot;k&quot;+4.22(&quot;23-24-25&quot;)[0].26.N(/:/,&quot;.&quot;)+&quot;k&quot;+(a.27/P/P).29(2)+&quot;2a.L&quot;;3 g=4.v(&quot;a&quot;);g.O=e;g.2c=f;g.2d.2e=&quot;2f&quot;;3 h;p(7.S){h=j S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">149</span>,<span class="hljs-string">&apos;|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|620|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="&#x7231;&#x5947;&#x827A;&#x611B;&#x5947;&#x85DD;-1080p&#x9AD8;&#x5E27;&#x7387;">&#x7231;&#x5947;&#x827A;/&#x611B;&#x5947;&#x85DD; 1080P_&#x9AD8;&#x5E27;&#x7387;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;3 7=8 U();7.V(&quot;W&quot;,&quot;y://X.t.u/z/Y/Z.z&quot;,5);7.10=6(){3 a=4.v(&quot;A&quot;);a.B=7.11;4.C(&quot;D&quot;)[0].E(a)};7.12(9);6 k(a){3 b=4.13.F(&quot;; &quot;);14(3 i=0;i&lt;b.15;i++){3 c=b[i].F(&quot;=&quot;);l(a==c[0])m G(c[1])}m 9}6 16(a,b){3 c=8 17(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.18(c);l(r!=9){m G(r[2])}m 9}3 n=j.19.H.w(&quot;1a.t.u&quot;)!=-1?&quot;1b&quot;:&quot;1c&quot;;3 o=1d.1e.1f.I.1g.I.o;3 x=&quot;/1h/1i?J=&quot;+o.J+&quot;&amp;1j=1k&amp;K=&quot;+o.K+&quot;&amp;n=&quot;+n+&quot;&amp;1l=0&amp;1m=1&amp;1n=&quot;+k(&quot;1o&quot;)+&quot;&amp;1p=1q&amp;1r=0&amp;1s=&quot;+k(&quot;1t&quot;)+&quot;&amp;1u=0&amp;d=0&amp;s=&amp;1v=&amp;1w=&amp;1x=&amp;1y=1&amp;1z=0&amp;1A=0&amp;1B=&quot;+k(&quot;1C&quot;)+&quot;&amp;1D=1E&amp;1F=0&amp;1G=2&amp;1H=&quot;+(8 1I()).1J()+&quot;&amp;1K=a&amp;1L=0&amp;1M=1N&amp;1O=L&amp;1P=1&quot;;j.M=&quot;y://1Q.N.t.u&quot;+x+&quot;&amp;1R=&quot;+1S(x);O(j.M);6 O(a){3 b=4.C(&quot;D&quot;)[0];3 c=4.v(&quot;A&quot;);c.n=a;b.E(c)}6 L(e){3 i=e.1T.1U.N;i.1V(6(a,b){l(a.1W){3 c=a.P;3 d=8 1X([c],{1Y:&quot;B/1Z&quot;});3 e=20.21(d);3 f=(4.p.w(&quot;-&quot;)!=-1?4.p.22(0,4.p.w(&quot;-&quot;)):4.p.Q(/\\s/,&quot;&quot;))+&quot;q&quot;+a.23+&quot;q&quot;+(a.24==2?&quot;25&quot;:&quot;26&quot;)+&quot;q&quot;+4.27(&quot;28-29-2a&quot;)[0].2b.Q(/:/,&quot;.&quot;)+&quot;q&quot;+(a.2c/R/R).2d(2)+&quot;2e.P&quot;;3 g=4.v(&quot;a&quot;);g.H=e;g.2f=f;g.2g.2h=&quot;2i&quot;;3 h;l(j.S){h=8 S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,5,j,0,0,0,0,0,5,5,5,5,0,9)}g.2o(h)}})}&apos;,62,149,&apos;|||var|document|false|function|req1|new|null||||||||||window|getCookie|if|return|src|movieinfo|title|_|||iqiyi|com|createElement|indexOf|params|https|js|script|text|getElementsByTagName|head|appendChild|split|unescape|href|engine|tvid|vid|NILAODA|dashUrl|video|loadScript|m3u8|replace|1024|MouseEvent|click|XMLHttpRequest|open|GET|static|common|f6a3054843de4645b34d205a9f377d25|onload|responseText|send|cookie|for|length|getQueryString|RegExp|match|location|tw|03020031010010000000|03020031010000000000|playerObject|_player|package|adproxy|jp|dash|bid|610|vt|rs|uid|P00003|ori|pcw|ps|k_uid|QC005|pt|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft1|706504940322820|callback|ut|cache|vf|cmd5x|data|program|forEach|_selected|Blob|type|plain|URL|createObjectURL|substring|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|toFixed|MB|download|style|display|none|else|createEvent|MouseEvents|initMouseEvent|true|dispatchEvent&apos;.split(&apos;|&apos;),0,{}))" target="_blank">&#x7231;&#x5947;&#x827A;1080P_&#x9AD8;&#x5E27;&#x7387;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;3 7=8 U();7.V(&quot;W&quot;,&quot;y://X.t.u/z/Y/Z.z&quot;,5);7.10=6(){3 a=4.v(&quot;A&quot;);a.B=7.11;4.C(&quot;D&quot;)[0].E(a)};7.12(9);6 k(a){3 b=4.13.F(&quot;; &quot;);14(3 i=0;i&lt;b.15;i++){3 c=b[i].F(&quot;=&quot;);l(a==c[0])m G(c[1])}m 9}6 16(a,b){3 c=8 17(\&apos;(^|&amp;)\&apos;+a+\&apos;=([^&amp;]*)(&amp;|$)\&apos;,\&apos;i\&apos;);3 r=b.18(c);l(r!=9){m G(r[2])}m 9}3 n=j.19.H.w(&quot;1a.t.u&quot;)!=-1?&quot;1b&quot;:&quot;1c&quot;;3 o=1d.1e.1f.I.1g.I.o;3 x=&quot;/1h/1i?J=&quot;+o.J+&quot;&amp;1j=1k&amp;K=&quot;+o.K+&quot;&amp;n=&quot;+n+&quot;&amp;1l=0&amp;1m=1&amp;1n=&quot;+k(&quot;1o&quot;)+&quot;&amp;1p=1q&amp;1r=0&amp;1s=&quot;+k(&quot;1t&quot;)+&quot;&amp;1u=0&amp;d=0&amp;s=&amp;1v=&amp;1w=&amp;1x=&amp;1y=1&amp;1z=0&amp;1A=0&amp;1B=&quot;+k(&quot;1C&quot;)+&quot;&amp;1D=1E&amp;1F=0&amp;1G=2&amp;1H=&quot;+(8 1I()).1J()+&quot;&amp;1K=a&amp;1L=0&amp;1M=1N&amp;1O=L&amp;1P=1&quot;;j.M=&quot;y://1Q.N.t.u&quot;+x+&quot;&amp;1R=&quot;+1S(x);O(j.M);6 O(a){3 b=4.C(&quot;D&quot;)[0];3 c=4.v(&quot;A&quot;);c.n=a;b.E(c)}6 L(e){3 i=e.1T.1U.N;i.1V(6(a,b){l(a.1W){3 c=a.P;3 d=8 1X([c],{1Y:&quot;B/1Z&quot;});3 e=20.21(d);3 f=(4.p.w(&quot;-&quot;)!=-1?4.p.22(0,4.p.w(&quot;-&quot;)):4.p.Q(/\\s/,&quot;&quot;))+&quot;q&quot;+a.23+&quot;q&quot;+(a.24==2?&quot;25&quot;:&quot;26&quot;)+&quot;q&quot;+4.27(&quot;28-29-2a&quot;)[0].2b.Q(/:/,&quot;.&quot;)+&quot;q&quot;+(a.2c/R/R).2d(2)+&quot;2e.P&quot;;3 g=4.v(&quot;a&quot;);g.H=e;g.2f=f;g.2g.2h=&quot;2i&quot;;3 h;l(j.S){h=8 S(&quot;T&quot;)}2j{h=4.2k(&quot;2l&quot;);h.2m(&quot;T&quot;,2n,5,j,0,0,0,0,0,5,5,5,5,0,9)}g.2o(h)}})}&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">149</span>,<span class="hljs-string">&apos;|||var|document|false|function|req1|new|null||||||||||window|getCookie|if|return|src|movieinfo|title|_|||iqiyi|com|createElement|indexOf|params|https|js|script|text|getElementsByTagName|head|appendChild|split|unescape|href|engine|tvid|vid|NILAODA|dashUrl|video|loadScript|m3u8|replace|1024|MouseEvent|click|XMLHttpRequest|open|GET|static|common|f6a3054843de4645b34d205a9f377d25|onload|responseText|send|cookie|for|length|getQueryString|RegExp|match|location|tw|03020031010010000000|03020031010000000000|playerObject|_player|package|adproxy|jp|dash|bid|610|vt|rs|uid|P00003|ori|pcw|ps|k_uid|QC005|pt|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft1|706504940322820|callback|ut|cache|vf|cmd5x|data|program|forEach|_selected|Blob|type|plain|URL|createObjectURL|substring|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|toFixed|MB|download|style|display|none|else|createEvent|MouseEvents|initMouseEvent|true|dispatchEvent&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="&#x8292;&#x679C;tv">&#x8292;&#x679C;TV</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:try{prompt(MGTVPlayer.VIDEOINFO.title,MGTVPlayer.player.cms.sourceInfo.info)}catch(err){var blob=new Blob([MGTVPlayer.player.cms.fakeMasterPlaylist],{type:&quot;text/plain&quot;});var url=URL.createObjectURL(blob);var title=MGTVPlayer.VIDEOINFO.title+&quot;.m3u8&quot;;var aLink=document.createElement(&quot;a&quot;);aLink.href=url;aLink.download=title;aLink.style.display=&quot;none&quot;;var event;if(window.MouseEvent){event=new MouseEvent(&quot;click&quot;)}else{event=document.createEvent(&quot;MouseEvents&quot;);event.initMouseEvent(&quot;click&quot;,true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)}" target="_blank">&#x8292;&#x679C;TV</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">try</span>{prompt(MGTVPlayer.VIDEOINFO.title,MGTVPlayer.player.cms.sourceInfo.info)}<span class="hljs-keyword">catch</span>(err){<span class="hljs-keyword">var</span> blob=<span class="hljs-keyword">new</span> Blob([MGTVPlayer.player.cms.fakeMasterPlaylist],{type:<span class="hljs-string">&quot;text/plain&quot;</span>});<span class="hljs-keyword">var</span> url=URL.createObjectURL(blob);<span class="hljs-keyword">var</span> title=MGTVPlayer.VIDEOINFO.title+<span class="hljs-string">&quot;.m3u8&quot;</span>;<span class="hljs-keyword">var</span> aLink=<span class="hljs-built_in">document</span>.createElement(<span class="hljs-string">&quot;a&quot;</span>);aLink.href=url;aLink.download=title;aLink.style.display=<span class="hljs-string">&quot;none&quot;</span>;<span class="hljs-keyword">var</span> event;<span class="hljs-keyword">if</span>(<span class="hljs-built_in">window</span>.MouseEvent){event=<span class="hljs-keyword">new</span> MouseEvent(<span class="hljs-string">&quot;click&quot;</span>)}<span class="hljs-keyword">else</span>{event=<span class="hljs-built_in">document</span>.createEvent(<span class="hljs-string">&quot;MouseEvents&quot;</span>);event.initMouseEvent(<span class="hljs-string">&quot;click&quot;</span>,<span class="hljs-literal">true</span>,<span class="hljs-literal">false</span>,<span class="hljs-built_in">window</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">null</span>)}aLink.dispatchEvent(event)}
</code></pre>
<h2 id="&#x641C;&#x72D0;&#x89C6;&#x9891;">&#x641C;&#x72D0;&#x89C6;&#x9891;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:var dur=document.getElementsByClassName(&quot;x-time-duration&quot;)[0].innerText;var ti=document.getElementById(&quot;vinfobox&quot;).getElementsByTagName(&quot;h2&quot;)[0].innerText;var dfn=document.getElementsByClassName(&quot;x-resolution-btn&quot;)[0].innerText;var content=&quot;#EXTM3U\n&quot;;_player.p2pkernel.dispatchUrlArr.forEach(function(item,index){var url=item[&quot;0&quot;];$.ajaxSettings.async=false;$.get(url,function(data,status){content+=&quot;#EXTINF:0\n&quot;+data[&quot;servers&quot;][0][&quot;url&quot;]+&quot;\n&quot;});$.ajaxSettings.async=true});content+=&quot;#EXT-X-ENDLIST&quot;;var blob=new Blob([content],{type:&quot;text/plain&quot;});var url=URL.createObjectURL(blob);var aLink=document.createElement(&quot;a&quot;);aLink.href=url;aLink.download=ti+&quot;_&quot;+dfn+&quot;_&quot;+dur.replace(/:/,&quot;.&quot;)+&quot;.m3u8&quot;;/*nilaoda*/aLink.style.display=&quot;none&quot;;var event;if(window.MouseEvent){event=new MouseEvent(&quot;click&quot;)}else{event=document.createEvent(&quot;MouseEvents&quot;);event.initMouseEvent(&quot;click&quot;,true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)" target="_blank">&#x641C;&#x72D0;&#x89C6;&#x9891;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> dur=<span class="hljs-built_in">document</span>.getElementsByClassName(<span class="hljs-string">&quot;x-time-duration&quot;</span>)[<span class="hljs-number">0</span>].innerText;<span class="hljs-keyword">var</span> ti=<span class="hljs-built_in">document</span>.getElementById(<span class="hljs-string">&quot;vinfobox&quot;</span>).getElementsByTagName(<span class="hljs-string">&quot;h2&quot;</span>)[<span class="hljs-number">0</span>].innerText;<span class="hljs-keyword">var</span> dfn=<span class="hljs-built_in">document</span>.getElementsByClassName(<span class="hljs-string">&quot;x-resolution-btn&quot;</span>)[<span class="hljs-number">0</span>].innerText;<span class="hljs-keyword">var</span> content=<span class="hljs-string">&quot;#EXTM3U\n&quot;</span>;_player.p2pkernel.dispatchUrlArr.forEach(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">item,index</span>)</span>{<span class="hljs-keyword">var</span> url=item[<span class="hljs-string">&quot;0&quot;</span>];$.ajaxSettings.async=<span class="hljs-literal">false</span>;$.get(url,<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">data,status</span>)</span>{content+=<span class="hljs-string">&quot;#EXTINF:0\n&quot;</span>+data[<span class="hljs-string">&quot;servers&quot;</span>][<span class="hljs-number">0</span>][<span class="hljs-string">&quot;url&quot;</span>]+<span class="hljs-string">&quot;\n&quot;</span>});$.ajaxSettings.async=<span class="hljs-literal">true</span>});content+=<span class="hljs-string">&quot;#EXT-X-ENDLIST&quot;</span>;<span class="hljs-keyword">var</span> blob=<span class="hljs-keyword">new</span> Blob([content],{type:<span class="hljs-string">&quot;text/plain&quot;</span>});<span class="hljs-keyword">var</span> url=URL.createObjectURL(blob);<span class="hljs-keyword">var</span> aLink=<span class="hljs-built_in">document</span>.createElement(<span class="hljs-string">&quot;a&quot;</span>);aLink.href=url;aLink.download=ti+<span class="hljs-string">&quot;_&quot;</span>+dfn+<span class="hljs-string">&quot;_&quot;</span>+dur.replace(<span class="hljs-regexp">/:/</span>,<span class="hljs-string">&quot;.&quot;</span>)+<span class="hljs-string">&quot;.m3u8&quot;</span>;<span class="hljs-comment">/*nilaoda*/</span>aLink.style.display=<span class="hljs-string">&quot;none&quot;</span>;<span class="hljs-keyword">var</span> event;<span class="hljs-keyword">if</span>(<span class="hljs-built_in">window</span>.MouseEvent){event=<span class="hljs-keyword">new</span> MouseEvent(<span class="hljs-string">&quot;click&quot;</span>)}<span class="hljs-keyword">else</span>{event=<span class="hljs-built_in">document</span>.createEvent(<span class="hljs-string">&quot;MouseEvents&quot;</span>);event.initMouseEvent(<span class="hljs-string">&quot;click&quot;</span>,<span class="hljs-literal">true</span>,<span class="hljs-literal">false</span>,<span class="hljs-built_in">window</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-literal">false</span>,<span class="hljs-number">0</span>,<span class="hljs-literal">null</span>)}aLink.dispatchEvent(event)
</code></pre>
<h2 id="&#x7231;&#x5947;&#x827A;&#x5B57;&#x5E55;&#x4E0B;&#x8F7D;">&#x7231;&#x5947;&#x827A;&#x5B57;&#x5E55;&#x4E0B;&#x8F7D;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:var tvid=playerObject._player.package.engine.adproxy.engine.movieinfo.tvid;var oData=playerObject._player.package.engine.adproxy.engine.episode.EpisodeStore[tvid].movieInfo.originalData;var prefix=oData.data.dstl;var subUrl=oData.data.program.stl[0].webvtt;var title=(document.title.indexOf(&quot;-&quot;)!=-1?document.title.substring(0,document.title.indexOf(&quot;-&quot;)):document.title.replace(/\s/,&quot;&quot;));prompt(title+&quot; [webvtt]&quot;,prefix+subUrl);" target="_blank">&#x7231;&#x5947;&#x827A;&#x5B57;&#x5E55;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> tvid=playerObject._player.package.engine.adproxy.engine.movieinfo.tvid;<span class="hljs-keyword">var</span> oData=playerObject._player.package.engine.adproxy.engine.episode.EpisodeStore[tvid].movieInfo.originalData;<span class="hljs-keyword">var</span> prefix=oData.data.dstl;<span class="hljs-keyword">var</span> subUrl=oData.data.program.stl[<span class="hljs-number">0</span>].webvtt;<span class="hljs-keyword">var</span> title=(<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)!=<span class="hljs-number">-1</span>?<span class="hljs-built_in">document</span>.title.substring(<span class="hljs-number">0</span>,<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)):<span class="hljs-built_in">document</span>.title.replace(<span class="hljs-regexp">/\s/</span>,<span class="hljs-string">&quot;&quot;</span>));prompt(title+<span class="hljs-string">&quot; [webvtt]&quot;</span>,prefix+subUrl);
</code></pre>
<h2 id="wetv-&#x5B57;&#x5E55;&#x4E0B;&#x8F7D;">Wetv &#x5B57;&#x5E55;&#x4E0B;&#x8F7D;</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;!6(){G{17(15(13(2))==&quot;6&quot;){}}12(e){4 c=u x();c.9(&quot;h&quot;,&quot;i://j.k.l/2/3.0.1/11/Q/2.q&quot;,r);c.s=6(){4 a=5.v(&quot;P&quot;);a.K=&quot;y/q&quot;;a.W=c.A;5.B(&quot;C&quot;)[0].p(a)};c.E(D);4 d=u x();d.9(&quot;h&quot;,&quot;i://j.k.l/2/3.0.1/2.H.I&quot;,r);d.s=6(){4 a=5.v(&quot;J&quot;);a.y=d.A;5.B(&quot;C&quot;)[0].p(a)};d.E(D)};4 f=5.L(&quot;M N O&quot;)[0].w;4 g=&quot;&quot;;R.S.T.U.V.F.X(6(a,b){g+=\&apos;&lt;a Y=&quot;\&apos;+a.Z+\&apos;&quot; 10=&quot;\&apos;+f+\&apos;7\&apos;+a.o+&quot;7&quot;+a.m+&quot;7&quot;+a.t+\&apos;.14\&apos;+\&apos;&quot;&gt;\&apos;+a.o+&quot;  &quot;+a.m+&quot;  &quot;+a.t+\&apos;&lt;/a&gt;\\n&lt;8&gt;\&apos;});2.9({w:&quot;&#x5B57;&#x5E55;&#x4E0B;&#x8F7D;&quot;,16:&quot;&lt;z&gt;&quot;+f+&quot;&lt;/z&gt;&lt;8&gt;&lt;8&gt;&quot;+g,18:19});g=&quot;&quot;}();&apos;,62,72,&apos;||layer||var|document|function|_|br|open||||||||GET|https|cdn|bootcss|com|id||langName|appendChild|css|false|onload|lang|new|createElement|title|XMLHttpRequest|text|strong|responseText|getElementsByTagName|head|null|send|list|try|min|js|script|type|getElementsByClassName|video_episode|flex_center|video_current|style|default|PLAYER|_DownloadMonitor|context|dataset|subtitleList|innerText|forEach|href|url|download|skin|catch|eval|srt|typeof|content|if|maxWidth|260&apos;.split(&apos;|&apos;),0,{}))" target="_blank">Wetv&#x5B57;&#x5E55;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;!6(){G{17(15(13(2))==&quot;6&quot;){}}12(e){4 c=u x();c.9(&quot;h&quot;,&quot;i://j.k.l/2/3.0.1/11/Q/2.q&quot;,r);c.s=6(){4 a=5.v(&quot;P&quot;);a.K=&quot;y/q&quot;;a.W=c.A;5.B(&quot;C&quot;)[0].p(a)};c.E(D);4 d=u x();d.9(&quot;h&quot;,&quot;i://j.k.l/2/3.0.1/2.H.I&quot;,r);d.s=6(){4 a=5.v(&quot;J&quot;);a.y=d.A;5.B(&quot;C&quot;)[0].p(a)};d.E(D)};4 f=5.L(&quot;M N O&quot;)[0].w;4 g=&quot;&quot;;R.S.T.U.V.F.X(6(a,b){g+=\&apos;&lt;a Y=&quot;\&apos;+a.Z+\&apos;&quot; 10=&quot;\&apos;+f+\&apos;7\&apos;+a.o+&quot;7&quot;+a.m+&quot;7&quot;+a.t+\&apos;.14\&apos;+\&apos;&quot;&gt;\&apos;+a.o+&quot;  &quot;+a.m+&quot;  &quot;+a.t+\&apos;&lt;/a&gt;\\n&lt;8&gt;\&apos;});2.9({w:&quot;&#x5B57;&#x5E55;&#x4E0B;&#x8F7D;&quot;,16:&quot;&lt;z&gt;&quot;+f+&quot;&lt;/z&gt;&lt;8&gt;&lt;8&gt;&quot;+g,18:19});g=&quot;&quot;}();&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">72</span>,<span class="hljs-string">&apos;||layer||var|document|function|_|br|open||||||||GET|https|cdn|bootcss|com|id||langName|appendChild|css|false|onload|lang|new|createElement|title|XMLHttpRequest|text|strong|responseText|getElementsByTagName|head|null|send|list|try|min|js|script|type|getElementsByClassName|video_episode|flex_center|video_current|style|default|PLAYER|_DownloadMonitor|context|dataset|subtitleList|innerText|forEach|href|url|download|skin|catch|eval|srt|typeof|content|if|maxWidth|260&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="viki">VIKI</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c&lt;a?&apos;&apos;:e(parseInt(c/a)))+((c=c%a)&gt;35?String.fromCharCode(c+29):c.toString(36))};if(!&apos;&apos;.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return&apos;\\w+&apos;};c=1};while(c--)if(k[c])p=p.replace(new RegExp(&apos;\\b&apos;+e(c)+&apos;\\b&apos;,&apos;g&apos;),k[c]);return p}(&apos;!6(){U{V(X(Y(4))==&quot;6&quot;){}}Z(e){5 c=l m();c.h(&quot;n&quot;,&quot;o://p.q.r/4/3.0.1/10/11/4.t&quot;,u);c.v=6(){5 a=7.w(&quot;8&quot;);a.12=&quot;x/t&quot;;a.y=c.z;13.14(&quot;15&quot;,a.y);7.A(&quot;B&quot;)[0].C(a)};c.D(E);5 d=l m();d.h(&quot;n&quot;,&quot;o://p.q.r/4/3.0.1/4.16.17&quot;,u);d.v=6(){5 a=7.w(&quot;18&quot;);a.x=d.z;7.A(&quot;B&quot;)[0].C(a)};d.D(E)};5 f=7.F.i(/\\W-.*/,\&apos;\&apos;);5 g=&quot;&quot;;G.9.9.H.I.J.K.19.1a(6(a,b){g+=\&apos;&lt;a 8=&quot;j:#L&quot; M=&quot;\&apos;+a.N+\&apos;&quot; O=&quot;\&apos;+f+&quot;1b&quot;+a.P.i(/\\W&lt;s.*/,\&apos;\&apos;)+\&apos;.1c\&apos;+\&apos;&quot;&gt;\&apos;+a.P.i(/\\W&lt;s.*\\\\&gt;(.*)&lt;/,\&apos;$1\&apos;)+(b%2==0?\&apos;&amp;k;&amp;k;&amp;k;\&apos;:\&apos;\&apos;)+\&apos;&lt;/a&gt;   \&apos;+(b%2!=0?\&apos;&lt;Q&gt;\&apos;:\&apos;\&apos;)});4.h({F:&quot;1d&#x4E0B;&#x8F7D;&quot;,1e:&quot;&lt;R 8=\&apos;j:1f\&apos;&gt;&lt;S&gt;&quot;+f+&quot;&lt;/S&gt;&quot;+\&apos;&amp;1g;[&lt;a 8=&quot;j:#L&quot; M=&quot;\&apos;+G.9.9.H.I.J.K.1h[1].N+\&apos;&quot; O=&quot;\&apos;+f+\&apos;.T\&apos;+\&apos;&quot;&gt;T&#x5730;&#x5740;&lt;/a&gt;]&lt;Q&gt;&lt;1i&gt;\&apos;+g+&quot;&lt;/R&gt;&quot;,1j:1k});g=&quot;&quot;}();&apos;,62,83,&apos;||||layer|var|function|document|style|player||||||||open|replace|color|emsp|new|XMLHttpRequest|GET|https|cdn|bootcss|com||css|false|onload|createElement|text|innerText|responseText|getElementsByTagName|head|appendChild|send|null|title|html5player|player_|customSubtitle|options_|playerOptions|2e8ded|href|src|download|label|br|div|strong|m3u8|try|if||typeof|eval|catch|skin|default|type|localStorage|setItem|layerCSS|min|js|script|sortedSubtitles|forEach|_|vtt|VIKI|content|black|nbsp|sources|hr|maxWidth|370&apos;.split(&apos;|&apos;),0,{}))" target="_blank">VIKI&#x4E0B;&#x8F7D;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-built_in">eval</span>(<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">p,a,c,k,e,r</span>)</span>{e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">c</span>)</span>{<span class="hljs-keyword">return</span>(c&lt;a?<span class="hljs-string">&apos;&apos;</span>:e(<span class="hljs-built_in">parseInt</span>(c/a)))+((c=c%a)&gt;<span class="hljs-number">35</span>?<span class="hljs-built_in">String</span>.fromCharCode(c+<span class="hljs-number">29</span>):c.toString(<span class="hljs-number">36</span>))};<span class="hljs-keyword">if</span>(!<span class="hljs-string">&apos;&apos;</span>.replace(<span class="hljs-regexp">/^/</span>,<span class="hljs-built_in">String</span>)){<span class="hljs-keyword">while</span>(c--)r[e(c)]=k[c]||e(c);k=[<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params">e</span>)</span>{<span class="hljs-keyword">return</span> r[e]}];e=<span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>)</span>{<span class="hljs-keyword">return</span><span class="hljs-string">&apos;\\w+&apos;</span>};c=<span class="hljs-number">1</span>};<span class="hljs-keyword">while</span>(c--)<span class="hljs-keyword">if</span>(k[c])p=p.replace(<span class="hljs-keyword">new</span> <span class="hljs-built_in">RegExp</span>(<span class="hljs-string">&apos;\\b&apos;</span>+e(c)+<span class="hljs-string">&apos;\\b&apos;</span>,<span class="hljs-string">&apos;g&apos;</span>),k[c]);<span class="hljs-keyword">return</span> p}(<span class="hljs-string">&apos;!6(){U{V(X(Y(4))==&quot;6&quot;){}}Z(e){5 c=l m();c.h(&quot;n&quot;,&quot;o://p.q.r/4/3.0.1/10/11/4.t&quot;,u);c.v=6(){5 a=7.w(&quot;8&quot;);a.12=&quot;x/t&quot;;a.y=c.z;13.14(&quot;15&quot;,a.y);7.A(&quot;B&quot;)[0].C(a)};c.D(E);5 d=l m();d.h(&quot;n&quot;,&quot;o://p.q.r/4/3.0.1/4.16.17&quot;,u);d.v=6(){5 a=7.w(&quot;18&quot;);a.x=d.z;7.A(&quot;B&quot;)[0].C(a)};d.D(E)};5 f=7.F.i(/\\W-.*/,\&apos;\&apos;);5 g=&quot;&quot;;G.9.9.H.I.J.K.19.1a(6(a,b){g+=\&apos;&lt;a 8=&quot;j:#L&quot; M=&quot;\&apos;+a.N+\&apos;&quot; O=&quot;\&apos;+f+&quot;1b&quot;+a.P.i(/\\W&lt;s.*/,\&apos;\&apos;)+\&apos;.1c\&apos;+\&apos;&quot;&gt;\&apos;+a.P.i(/\\W&lt;s.*\\\\&gt;(.*)&lt;/,\&apos;$1\&apos;)+(b%2==0?\&apos;&amp;k;&amp;k;&amp;k;\&apos;:\&apos;\&apos;)+\&apos;&lt;/a&gt;   \&apos;+(b%2!=0?\&apos;&lt;Q&gt;\&apos;:\&apos;\&apos;)});4.h({F:&quot;1d&#x4E0B;&#x8F7D;&quot;,1e:&quot;&lt;R 8=\&apos;j:1f\&apos;&gt;&lt;S&gt;&quot;+f+&quot;&lt;/S&gt;&quot;+\&apos;&amp;1g;[&lt;a 8=&quot;j:#L&quot; M=&quot;\&apos;+G.9.9.H.I.J.K.1h[1].N+\&apos;&quot; O=&quot;\&apos;+f+\&apos;.T\&apos;+\&apos;&quot;&gt;T&#x5730;&#x5740;&lt;/a&gt;]&lt;Q&gt;&lt;1i&gt;\&apos;+g+&quot;&lt;/R&gt;&quot;,1j:1k});g=&quot;&quot;}();&apos;</span>,<span class="hljs-number">62</span>,<span class="hljs-number">83</span>,<span class="hljs-string">&apos;||||layer|var|function|document|style|player||||||||open|replace|color|emsp|new|XMLHttpRequest|GET|https|cdn|bootcss|com||css|false|onload|createElement|text|innerText|responseText|getElementsByTagName|head|appendChild|send|null|title|html5player|player_|customSubtitle|options_|playerOptions|2e8ded|href|src|download|label|br|div|strong|m3u8|try|if||typeof|eval|catch|skin|default|type|localStorage|setItem|layerCSS|min|js|script|sortedSubtitles|forEach|_|vtt|VIKI|content|black|nbsp|sources|hr|maxWidth|370&apos;</span>.split(<span class="hljs-string">&apos;|&apos;</span>),<span class="hljs-number">0</span>,{}))
</code></pre>
<h2 id="ondemandchina-master-m3u8">OnDemandChina Master m3u8</h2>
<p>&#x9002;&#x7528;&#x4E8E; <a href="https://old.ondemandchina.com" target="_blank">OnDemandChina(Old)</a></p>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:var url=this.myPlayer.dash.playlists.srcUrl;var title=(document.title.indexOf(&quot;-&quot;)!=-1?document.title.substring(0,document.title.indexOf(&quot;-&quot;)):document.title.replace(/\s/,&quot;&quot;));prompt(title+&quot; [master]&quot;,url);" target="_blank">OnDemandChina&#x4E0B;&#x8F7D;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> url=<span class="hljs-keyword">this</span>.myPlayer.dash.playlists.srcUrl;<span class="hljs-keyword">var</span> title=(<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)!=<span class="hljs-number">-1</span>?<span class="hljs-built_in">document</span>.title.substring(<span class="hljs-number">0</span>,<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)):<span class="hljs-built_in">document</span>.title.replace(<span class="hljs-regexp">/\s/</span>,<span class="hljs-string">&quot;&quot;</span>));prompt(title+<span class="hljs-string">&quot; [master]&quot;</span>,url);
</code></pre>
<h2 id="ondemandchina-&#x5B57;&#x5E55;-m3u8">OnDemandChina &#x5B57;&#x5E55; m3u8</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:var url;var subs=this.myPlayer.dash.playlists.master.mediaGroups.SUBTITLES[&quot;subtitles-0&quot;];var title=(document.title.indexOf(&quot;-&quot;)!=-1?document.title.substring(0,document.title.indexOf(&quot;-&quot;)):document.title.replace(/\s/,&quot;&quot;));for(var p in subs){if(subs[p][&quot;default&quot;]) url=subs[p][&quot;uri&quot;];};if(url)prompt(title+&quot; [default subtitle]&quot;,url);" target="_blank">OnDemandChina&#x5B57;&#x5E55;</a></p>
<pre><code class="lang-js">javascript:<span class="hljs-keyword">var</span> url;<span class="hljs-keyword">var</span> subs=<span class="hljs-keyword">this</span>.myPlayer.dash.playlists.master.mediaGroups.SUBTITLES[<span class="hljs-string">&quot;subtitles-0&quot;</span>];<span class="hljs-keyword">var</span> title=(<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)!=<span class="hljs-number">-1</span>?<span class="hljs-built_in">document</span>.title.substring(<span class="hljs-number">0</span>,<span class="hljs-built_in">document</span>.title.indexOf(<span class="hljs-string">&quot;-&quot;</span>)):<span class="hljs-built_in">document</span>.title.replace(<span class="hljs-regexp">/\s/</span>,<span class="hljs-string">&quot;&quot;</span>));<span class="hljs-keyword">for</span>(<span class="hljs-keyword">var</span> p <span class="hljs-keyword">in</span> subs){<span class="hljs-keyword">if</span>(subs[p][<span class="hljs-string">&quot;default&quot;</span>]) url=subs[p][<span class="hljs-string">&quot;uri&quot;</span>];};<span class="hljs-keyword">if</span>(url)prompt(title+<span class="hljs-string">&quot; [default subtitle]&quot;</span>,url);
</code></pre>
<h2 id="naver-tv">NAVER TV</h2>
<p>&#x53EF;&#x76F4;&#x63A5;&#x5C06;&#x8FD9;&#x4E2A;&#x8D85;&#x94FE;&#x63A5;&#x62D6;&#x5165;&#x4F60;&#x7684;&#x4E66;&#x7B7E;&#x680F;&#xFF1A;<a href="javascript:prompt(document.title,WrapPlayer.rmcPlayer.core.model.currentVideo.source);" target="_blank">NAVER TV m3u8</a></p>
<pre><code class="lang-js">javascript:prompt(<span class="hljs-built_in">document</span>.title,WrapPlayer.rmcPlayer.core.model.currentVideo.source);
</code></pre>
<h2 id="&#x66F4;&#x591A;&#x656C;&#x8BF7;&#x671F;&#x5F85;">&#x66F4;&#x591A;&#x656C;&#x8BF7;&#x671F;&#x5F85;</h2>

                                
                                </section>
                            
    </div>
    <div class="search-results">
        <div class="has-results">
            
            <h1 class="search-results-title"><span class='search-results-count'></span> results matching "<span class='search-query'></span>"</h1>
            <ul class="search-results-list"></ul>
            
        </div>
        <div class="no-results">
            
            <h1 class="search-results-title">No results matching "<span class='search-query'></span>"</h1>
            
        </div>
    </div>
</div>

                        </div>
                    </div>
                
            </div>

            
                
                
                <a href="LinetvParser.html" class="navigation navigation-next navigation-unique" aria-label="Next page: LinetvParser">
                    <i class="fa fa-angle-right"></i>
                </a>
                
            
        
    </div>

    <script>
        var gitbook = gitbook || [];
        gitbook.push(function() {
            gitbook.page.hasChanged({"page":{"title":"JS获取m3u8","level":"4.1.1","depth":2,"next":{"title":"LinetvParser","level":"4.1.2","depth":2,"path":"LinetvParser.md","ref":"LinetvParser.md","articles":[]},"previous":{"title":"辅助","level":"4.1","depth":1,"ref":"","articles":[{"title":"JS获取m3u8","level":"4.1.1","depth":2,"path":"GetM3u8.md","ref":"GetM3u8.md","articles":[]},{"title":"LinetvParser","level":"4.1.2","depth":2,"path":"LinetvParser.md","ref":"LinetvParser.md","articles":[]},{"title":"ViuParser","level":"4.1.3","depth":2,"path":"ViuParser.md","ref":"ViuParser.md","articles":[]},{"title":"VikiParser","level":"4.1.4","depth":2,"path":"VikiParser.md","ref":"VikiParser.md","articles":[]},{"title":"M3U8URL2File","level":"4.1.5","depth":2,"path":"M3U8URL2File.md","ref":"M3U8URL2File.md","articles":[]}]},"dir":"ltr"},"config":{"plugins":["donate","github","github-buttons","-sharing","sharing-plus"],"styles":{"website":"styles/website.css","pdf":"styles/pdf.css","epub":"styles/epub.css","mobi":"styles/mobi.css","ebook":"styles/ebook.css","print":"styles/print.css"},"pluginsConfig":{"github":{"url":"https://github.com/nilaoda"},"search":{},"sharing-plus":{"qq":false,"all":["facebook","google","twitter","instapaper","linkedin","pocket","stumbleupon"],"douban":false,"facebook":true,"weibo":false,"instapaper":false,"whatsapp":false,"hatenaBookmark":false,"twitter":true,"messenger":false,"line":false,"vk":false,"pocket":true,"google":false,"viber":false,"stumbleupon":false,"qzone":false,"linkedin":false},"lunr":{"maxIndexSize":1000000,"ignoreSpecialCharacters":false},"donate":{"alipay":"./source/images/alipay.png","alipayText":"支付宝","button":"赞赏","title":"","wechat":"","wechatText":"微信打赏"},"fontsettings":{"theme":"white","family":"sans","size":2},"highlight":{},"github-buttons":{"buttons":[{"user":"nilaoda","repo":"N_m3u8DL-CLI","type":"star","size":"small","count":true}]},"sharing":{"qq":true,"all":["google","facebook","weibo","twitter","qq","qzone","linkedin","pocket"],"douban":false,"facebook":false,"weibo":true,"instapaper":false,"whatsapp":false,"hatenaBookmark":false,"twitter":true,"messenger":false,"line":false,"vk":false,"pocket":false,"google":false,"viber":false,"stumbleupon":false,"qzone":true,"linkedin":false},"theme-default":{"styles":{"website":"styles/website.css","pdf":"styles/pdf.css","epub":"styles/epub.css","mobi":"styles/mobi.css","ebook":"styles/ebook.css","print":"styles/print.css"},"showLevel":false}},"theme":"default","author":"nilaoda","pdf":{"pageNumbers":true,"fontSize":12,"fontFamily":"Arial","paperSize":"a4","chapterMark":"pagebreak","pageBreaksBefore":"/","margin":{"right":62,"left":62,"top":56,"bottom":56}},"structure":{"langs":"LANGS.md","readme":"README.md","glossary":"GLOSSARY.md","summary":"SUMMARY.md"},"variables":{},"title":"N_m3u8DL-CLI文档","language":"zh-hans","gitbook":"3.2.3","description":"N_m3u8DL-CLI文档"},"file":{"path":"GetM3u8.md","mtime":"2020-02-27T06:28:47.695Z","type":"markdown"},"gitbook":{"version":"3.2.3","time":"2020-02-27T06:28:56.082Z"},"basePath":".","book":{"language":""}});
        });
    </script>
</div>

        
    <script src="gitbook/gitbook.js"></script>
    <script src="gitbook/theme.js"></script>
    
        
        <script src="gitbook/gitbook-plugin-donate/plugin.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-github/plugin.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-github-buttons/plugin.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-sharing-plus/buttons.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-search/search-engine.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-search/search.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-lunr/lunr.min.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-lunr/search-lunr.js"></script>
        
    
        
        <script src="gitbook/gitbook-plugin-fontsettings/fontsettings.js"></script>
        
    

    </body>
</html>

