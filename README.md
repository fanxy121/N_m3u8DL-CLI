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



                   
    
 JS获取m3u8
使用Javascript获取m3u8
本页将提供一些JS代码，在您的浏览器运行这些代码有助于更快的获取到m3u8链接用以下载。
为了方便使用，最好将下面的JS代码存为书签。

注意：

所有代码仅供学习，请勿用于任何违法途径
本页Javascript代码更新于2020年2月27日，测试于360极速浏览器，其他浏览器不保证正常使用
腾讯视频
可直接将这个超链接拖入你的书签栏：腾讯视频

javascript:var a=prompt(PLAYER._DownloadMonitor.context.dataset.title,PLAYER._DownloadMonitor.context.dataset.ckc?PLAYER._DownloadMonitor.context.dataset.currentVideoUrl:PLAYER._DownloadMonitor.context.dataset.currentVideoUrl.replace(/:.*qq.com/g,"://defaultts.tc.qq.com/defaultts.tc.qq.com"));
腾讯视频(DRM内容)
可直接将这个超链接拖入你的书签栏：腾讯视频(DRM内容)

javascript:var m3u8Content=PLAYER._DownloadMonitor.context.dataset.playList[0].m3u8;var blob=new Blob([m3u8Content],{type:"text/plain"});var url=URL.createObjectURL(blob);var title=PLAYER._DownloadMonitor.context.dataset.title+"[v+a].m3u8";var aLink=document.createElement("a");aLink.href=url;aLink.download=title;aLink.style.display="none";var event;if(window.MouseEvent){event=new MouseEvent("click")}else{event=document.createEvent("MouseEvents");event.initMouseEvent("click",true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event);
优酷视频
可直接将这个超链接拖入你的书签栏：优酷视频

javascript:var url;var size=0;Array.from(videoPlayer.getData()._playlistData.stream).forEach(function(element,index,array){if(element.audio_lang==videoPlayer.getConfig().language&&element.size>size){url=element.m3u8_url;size=element.size}});/*nilaoda*/var a=prompt(videoPlayer.getData()._videoData.title+"_"+videoPlayer.getConfig().language+"_"+(size/1024/1024).toFixed(2)+"MB",url);
补充说明 (20200223)：

目前部分优酷视频使用了其自有Copyright DRM加密，使用本软件2.5.0及以上版本可以解密。使用以下JS获取专用解密KEY

javascript:var a=prompt(videoPlayer.getData()._videoData.title + "key", btoa(String.fromCharCode.apply(null, ____hexA)));
部分视频为cmaf加密，参考：https://github.com/nilaoda/Blog/issues/19

爱奇艺/愛奇藝视频
可直接将这个超链接拖入你的书签栏：爱奇艺视频

javascript:try{var info=playerObject._player._core._movieinfo.originalData.data.program.video;info.forEach(function(item,index){if(item._selected){var m3u8Content="";if(item.m3u8==undefined){try{if(typeof(eval(cmd5x))=="function"){}}catch(e){var req1=new XMLHttpRequest();req1.open("GET","https://static.iqiyi.com/js/common/f6a3054843de4645b34d205a9f377d25.js",false);req1.onload=function(){var script=document.createElement("script");script.text=req1.responseText;document.getElementsByTagName("head")[0].appendChild(script)};req1.send(null)}var fs=item.fs;var content="#EXTM3U\n";fs.forEach(function(fs_i,fs_index){var url=fs_i.l;var prefix="https://data.video.iqiyi.com/videos";var api=prefix+url;try{var t=playerObject._player._core._movieinfo.originalData.data.boss.data.t;api=prefix+url+"&cross-domain=1&t="+t+"&QY00001="+/qd_uid=(\d+)/g.exec(url)[1]+"&ib=4&ptime=0&ibt="+cmd5x(t+/\/(\w{10,})/g.exec(url)[1])}catch(err){}var req=new XMLHttpRequest();req.overrideMimeType("application/json");req.open("GET",api,false);req.onload=function(){var jsonResponse=JSON.parse(req.responseText);content+="#EXTINF:0\n"+jsonResponse["l"]+"\n"};req.send(null)});content+="#EXT-X-ENDLIST";m3u8Content=content}else{m3u8Content=item.m3u8}var blob=new Blob([m3u8Content],{type:"text/plain"});var url=URL.createObjectURL(blob);var title=(document.title.indexOf("-")!=-1?document.title.substring(0,document.title.indexOf("-")):document.title.replace(/\s/,""))+"_"+item.scrsz+"_"+(item.code==2?"H264":"H265")+"_"+document.getElementsByClassName("iqp-time-dur")[0].innerText.replace(/:/,".")+"_"+(item.vsize/1024/1024).toFixed(2)+"MB.m3u8";var aLink=document.createElement("a");aLink.href=url;aLink.download=title;aLink.style.display="none";var event;if(window.MouseEvent){event=new MouseEvent("click")}else{event=document.createEvent("MouseEvents");event.initMouseEvent("click",true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)}})}catch(err){var info1=playerObject._player.package.engine.adproxy.engine.movieinfo.vidl;info1.forEach(function(item1,index1){if(item1.responseData!=undefined){var info=item1.responseData.data.program.video;info.forEach(function(item,index){if(item._selected){var m3u8Content="";if(item.m3u8==undefined){try{if(typeof(eval(cmd5x))=="function"){}}catch(e){var req1=new XMLHttpRequest();req1.open("GET","https://static.iqiyi.com/js/common/f6a3054843de4645b34d205a9f377d25.js",false);req1.onload=function(){var script=document.createElement("script");script.text=req1.responseText;document.getElementsByTagName("head")[0].appendChild(script)};req1.send(null)}var fs=item.fs;var content="#EXTM3U\n";fs.forEach(function(fs_i,fs_index){var url=fs_i.l;var prefix="https://data.video.iqiyi.com/videos";var api=prefix+url;try{var t=playerObject._player.package.engine.adproxy.engine.movieinfo.current.boss.data.t;api=prefix+url+"&cross-domain=1&t="+t+"&QY00001="+/qd_uid=(\d+)/g.exec(url)[1]+"&ib=4&ptime=0&ibt="+cmd5x(t+/\/(\w{10,})/g.exec(url)[1])}catch(err){console.error(err)}var req=new XMLHttpRequest();req.overrideMimeType("application/json");req.open("GET",api,false);req.onload=function(){var jsonResponse=JSON.parse(req.responseText);content+="#EXTINF:0\n"+jsonResponse["l"]+"\n"};req.send(null)});content+="#EXT-X-ENDLIST";m3u8Content=content}else{m3u8Content=item.m3u8}var blob=new Blob([m3u8Content],{type:"text/plain"});var url=URL.createObjectURL(blob);var title=(document.title.indexOf("-")!=-1?document.title.substring(0,document.title.indexOf("-")):document.title.replace(/\s/,""))+"_"+item.scrsz+"_"+(item.code==2?"H264":"H265")+"_"+document.getElementsByClassName("iqp-time-dur")[0].innerText.replace(/:/,".")+"_"+(item.vsize/1024/1024).toFixed(2)+"MB.m3u8";/*nilaoda*/var aLink=document.createElement("a");aLink.href=url;aLink.download=title;aLink.style.display="none";var event;if(window.MouseEvent){event=new MouseEvent("click")}else{event=document.createEvent("MouseEvents");event.initMouseEvent("click",true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)}})}})}
爱奇艺/愛奇藝 杜比音轨
可直接将这个超链接拖入你的书签栏：爱奇艺杜比音轨

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 B=A 1k();B.1j("1h","R://2I.M.C/1c/1Q/2b.1c",9);B.1b=7(){3 a=6.Q("19");a.1m=B.Z;6.V("U")[0].S(a)};B.18(z);7 G(a){3 b=6.2S.14("; ");1K(3 i=0;i<b.1Y;i++){3 c=b[i].14("=");J(a==c[0])K 1d(c[1])}K z}7 N(a,b){3 c=A 1U(\'(^|&)\'+a+\'=([^&]*)(&|$)\',\'i\');3 r=b.22(c);J(r!=z){K 1d(r[2])}K z}3 L=8.2T.15.O("1L.M.C")!=-1?"1M":"1O";3 F=1R.1S.1T.1a.1X.1a.F;3 P="/1Z/20?1e="+F.1e+"&24=26&27=28&D="+F.D+"&L="+L+"&2d=0&2e=1&2h="+G("2i")+"&2x=2y&2E=0&T="+G("2M")+"&2R=0&d=0&s=&1n=&1o=&1p=&1q=1&1r=0&1s=0&1t="+G("1u")+"&1v=1w&1x=0&1y=2&1z="+(A 2Z()).1B()+"&1C=a&1D=0&1E=1F&1G=1H&1I=1&1J=W&Y=1&Y=5";8.I="R://1N.11.M.C"+P+"&1P="+12(P);13(8.I);7 13(a){3 b=6.V("U")[0];3 c=6.Q("19");c.L=a;b.S(c)}7 W(e){3 x=e.H.1V.1W;3 y=0;x.17(7(m,n){J(m.21){3 o=m.23;3 p="#25\\n";o.17(7(b,c){3 f=b.l;y+=b.b;3 h="R://H.11.M.C/29";3 i=h+f;2a{3 t=e.H.2c.H.t;3 j=N("D",8.I);3 k=N("T",8.I);i=h+f+"&t="+t+"&D="+j+"&2f="+/2g=(\\d+)/g.1f(f)[1]+"&2j="+k+"&2k=4&2l="+12(t+/\\/(\\w{10,})/g.1f(f)[1])+"&2m=0"}2n(2o){}3 l=A 1k();l.2p("2q/2r");l.1j("1h",i,9);l.1b=7(){3 a=2s.2t(l.Z);p+="#2u:0\\n"+a["l"]+"\\n"};l.18(z)});p+="#2v-X-2w";1g=p;3 q=A 2z([1g],{2A:"1m/2B"});3 r=2C.2D(q);3 s=(6.E.O("-")!=-1?6.E.2F(0,6.E.O("-")):6.E.2G(/\\s/,""))+"2H"+(y/1i/1i).2J(2)+"2K.2L";3 u=6.Q("a");u.15=r;u.2N=s;u.2O.2P="2Q";3 v;J(8.1l){v=A 1l("16")}2U{v=6.2V("2W");v.2X("16",2Y,9,8,0,0,0,0,0,9,9,9,9,0,z)}u.1A(v)}})}',62,186,'|||var|||document|function|window|false||||||||||||||||||||||||||null|new|req1|com|vid|title|movieinfo|getCookie|data|dashUrl|if|return|src|iqiyi|getQueryString|indexOf|params|createElement|https|appendChild|k_uid|head|getElementsByTagName|NILAODA||ut|responseText||video|cmd5x|loadScript|split|href|click|forEach|send|script|engine|onload|js|unescape|tvid|exec|m3u8Content|GET|1024|open|XMLHttpRequest|MouseEvent|text|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|dispatchEvent|getTime|qdy|qds|k_ft1|1354994433|k_ft4|8196|k_ft5|callback|for|tw|01010031010010000000|cache|01010031010000000000|vf|common|playerObject|_player|package|RegExp|program|audio|adproxy|length|jp|dash|_selected|match|fs|bid|EXTM3U|300|abid|500|videos|try|f6a3054843de4645b34d205a9f377d25|boss_ts|vt|rs|QY00001|qd_uid|uid|P00003|su|ib|ibt|ptime|catch|err|overrideMimeType|application|json|JSON|parse|EXTINF|EXT|ENDLIST|ori|pcw|Blob|type|plain|URL|createObjectURL|ps|substring|replace|_dolby_|static|toFixed|MB|m3u8|QC005|download|style|display|none|pt|cookie|location|else|createEvent|MouseEvents|initMouseEvent|true|Date'.split('|'),0,{}))
爱奇艺/愛奇藝 4K H264
可直接将这个超链接拖入你的书签栏：爱奇艺4K_H264

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 j=k 1e();j.1E("1J","S://14.y.x/N/1K/1W.N",7);j.11=6(){3 a=5.w("E");a.z=j.2i;5.L("F")[0].B(a)};j.1f(9);6 m(a){3 b=5.1P.G("; ");1Y(3 i=0;i<b.W;i++){3 c=b[i].G("=");q(a==c[0])t R(c[1])}t 9}6 1g(a,b){3 c=k 1C(\'(^|&)\'+a+\'=([^&]*)(&|$)\',\'i\');3 r=b.1G(c);q(r!=9){t R(r[2])}t 9}3 p=8.1V.P.u("1Z.y.x")!=-1?"2a":"2d";3 n=2j.2k.V.A.X.A.n;3 v="/Z/10?C="+n.C+"&12=13&D="+n.D+"&p="+p+"&15=0&16=1&17="+m("18")+"&19=1a&1b=0&1c="+m("1d")+"&2q=0&d=0&s=&1h=&1i=&1j=&1k=1&1l=0&1m=0&1n="+m("1o")+"&1p=1q&1r=0&1s=2&1t="+(k 1u()).1v()+"&1w=a&1x=0&1y=1z&1A=4&1B=H&1D=1";8.I="S://1F.J.y.x"+v+"&1H="+1I(v);K(8.I);6 K(a){3 b=5.L("F")[0];3 c=5.w("E");c.p=a;b.B(c)}6 H(e){3 i=e.1L.1M.J;i.1N(6(a,b){q(a.1O){3 c=a.M;3 d=k 1Q([c],{1R:"z/1S"});3 e=1T.1U(d);3 f=(5.o.u("-")!=-1?5.o.1X(0,5.o.u("-")):5.o.O(/\\s/,""))+"l"+a.20+"l"+(a.21==2?"22":"23")+"l"+5.24("25-26-27")[0].28.O(/:/,".")+"l"+(a.29/Q/Q).2b(2)+"2c.M";3 g=5.w("a");g.P=e;g.2e=f;g.2f.2g="2h";3 h;q(8.T){h=k T("U")}2l{h=5.2m("2n");h.2o("U",2p,7,8,0,0,0,0,0,7,7,7,7,0,9)}g.Y(h)}})}',62,151,'|||var||document|function|false|window|null||||||||||req1|new|_|getCookie|movieinfo|title|src|if|||return|indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|800|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|QC005|XMLHttpRequest|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8196|k_ft4|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|pt'.split('|'),0,{}))
爱奇艺/愛奇藝 4K H265
可直接将这个超链接拖入你的书签栏：爱奇艺4K_H265

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 9=j 1c();9.1C("1H","R://13.x.w/M/1I/1U.M",6);9.10=5(){3 a=4.v("D");a.y=9.2g;4.K("E")[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F("; ");1W(3 i=0;i<b.V;i++){3 c=b[i].F("=");p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\'(^|&)\'+a+\'=([^&]*)(&|$)\',\'i\');3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t("1X.x.w")!=-1?"28":"2b";3 m=2h.2i.U.z.W.z.m;3 u="/Y/Z?B="+m.B+"&11=12&C="+m.C+"&o="+o+"&14=0&15=1&16="+l("17")+"&18=19&1a=0&1b="+l("2o")+"&1d=0&d=0&s=&1g=&1h=&1i=&1j=1&1k=0&1l=0&1m="+l("1n")+"&1o=1p&1q=0&1r=2&1s="+(j 1t()).1u()+"&1v=a&1w=0&1x=1y&1z=G&1B=1";7.H="R://1D.I.x.w"+u+"&1F="+1G(u);J(7.H);5 J(a){3 b=4.K("E")[0];3 c=4.v("D");c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:"y/1Q"});3 e=1R.1S(d);3 f=(4.n.t("-")!=-1?4.n.1V(0,4.n.t("-")):4.n.N(/\\s/,""))+"k"+a.1Y+"k"+(a.1Z==2?"20":"21")+"k"+4.22("23-24-25")[0].26.N(/:/,".")+"k"+(a.27/P/P).29(2)+"2a.L";3 g=4.v("a");g.O=e;g.2c=f;g.2d.2e="2f";3 h;p(7.S){h=j S("T")}2j{h=4.2k("2l");h.2m("T",2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}',62,149,'|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|800|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005'.split('|'),0,{}))
爱奇艺/愛奇藝 1080P H265 (低码)
可直接将这个超链接拖入你的书签栏：爱奇艺1080P_H265(低码)

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 9=j 1c();9.1C("1H","R://13.x.w/M/1I/1U.M",6);9.10=5(){3 a=4.v("D");a.y=9.2g;4.K("E")[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F("; ");1W(3 i=0;i<b.V;i++){3 c=b[i].F("=");p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\'(^|&)\'+a+\'=([^&]*)(&|$)\',\'i\');3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t("1X.x.w")!=-1?"28":"2b";3 m=2h.2i.U.z.W.z.m;3 u="/Y/Z?B="+m.B+"&11=12&C="+m.C+"&o="+o+"&14=0&15=1&16="+l("17")+"&18=19&1a=0&1b="+l("2o")+"&1d=0&d=0&s=&1g=&1h=&1i=&1j=1&1k=0&1l=0&1m="+l("1n")+"&1o=1p&1q=0&1r=2&1s="+(j 1t()).1u()+"&1v=a&1w=0&1x=1y&1z=G&1B=1";7.H="R://1D.I.x.w"+u+"&1F="+1G(u);J(7.H);5 J(a){3 b=4.K("E")[0];3 c=4.v("D");c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:"y/1Q"});3 e=1R.1S(d);3 f=(4.n.t("-")!=-1?4.n.1V(0,4.n.t("-")):4.n.N(/\\s/,""))+"k"+a.1Y+"k"+(a.1Z==2?"20":"21")+"k"+4.22("23-24-25")[0].26.N(/:/,".")+"k"+(a.27/P/P).29(2)+"2a.L";3 g=4.v("a");g.O=e;g.2c=f;g.2d.2e="2f";3 h;p(7.S){h=j S("T")}2j{h=4.2k("2l");h.2m("T",2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}',62,149,'|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|600|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005'.split('|'),0,{}))
爱奇艺/愛奇藝 1080P H265 (中码)
可直接将这个超链接拖入你的书签栏：爱奇艺1080P_H265(中码)

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 9=j 1c();9.1C("1H","R://13.x.w/M/1I/1U.M",6);9.10=5(){3 a=4.v("D");a.y=9.2g;4.K("E")[0].A(a)};9.1e(8);5 l(a){3 b=4.1N.F("; ");1W(3 i=0;i<b.V;i++){3 c=b[i].F("=");p(a==c[0])q Q(c[1])}q 8}5 1f(a,b){3 c=j 1A(\'(^|&)\'+a+\'=([^&]*)(&|$)\',\'i\');3 r=b.1E(c);p(r!=8){q Q(r[2])}q 8}3 o=7.1T.O.t("1X.x.w")!=-1?"28":"2b";3 m=2h.2i.U.z.W.z.m;3 u="/Y/Z?B="+m.B+"&11=12&C="+m.C+"&o="+o+"&14=0&15=1&16="+l("17")+"&18=19&1a=0&1b="+l("2o")+"&1d=0&d=0&s=&1g=&1h=&1i=&1j=1&1k=0&1l=0&1m="+l("1n")+"&1o=1p&1q=0&1r=2&1s="+(j 1t()).1u()+"&1v=a&1w=0&1x=1y&1z=G&1B=1";7.H="R://1D.I.x.w"+u+"&1F="+1G(u);J(7.H);5 J(a){3 b=4.K("E")[0];3 c=4.v("D");c.o=a;b.A(c)}5 G(e){3 i=e.1J.1K.I;i.1L(5(a,b){p(a.1M){3 c=a.L;3 d=j 1O([c],{1P:"y/1Q"});3 e=1R.1S(d);3 f=(4.n.t("-")!=-1?4.n.1V(0,4.n.t("-")):4.n.N(/\\s/,""))+"k"+a.1Y+"k"+(a.1Z==2?"20":"21")+"k"+4.22("23-24-25")[0].26.N(/:/,".")+"k"+(a.27/P/P).29(2)+"2a.L";3 g=4.v("a");g.O=e;g.2c=f;g.2d.2e="2f";3 h;p(7.S){h=j S("T")}2j{h=4.2k("2l");h.2m("T",2n,6,7,0,0,0,0,0,6,6,6,6,0,8)}g.X(h)}})}',62,149,'|||var|document|function|false|window|null|req1||||||||||new|_|getCookie|movieinfo|title|src|if|return|||indexOf|params|createElement|com|iqiyi|text|engine|appendChild|tvid|vid|script|head|split|NILAODA|dashUrl|video|loadScript|getElementsByTagName|m3u8|js|replace|href|1024|unescape|https|MouseEvent|click|package|length|adproxy|dispatchEvent|jp|dash|onload|bid|620|static|vt|rs|uid|P00003|ori|pcw|ps|k_uid|XMLHttpRequest|pt|send|getQueryString|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft2|8191|callback|RegExp|ut|open|cache|match|vf|cmd5x|GET|common|data|program|forEach|_selected|cookie|Blob|type|plain|URL|createObjectURL|location|f6a3054843de4645b34d205a9f377d25|substring|for|tw|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|03020031010010000000|toFixed|MB|03020031010000000000|download|style|display|none|responseText|playerObject|_player|else|createEvent|MouseEvents|initMouseEvent|true|QC005'.split('|'),0,{}))
爱奇艺/愛奇藝 1080P_高帧率
可直接将这个超链接拖入你的书签栏：爱奇艺1080P_高帧率

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('3 7=8 U();7.V("W","y://X.t.u/z/Y/Z.z",5);7.10=6(){3 a=4.v("A");a.B=7.11;4.C("D")[0].E(a)};7.12(9);6 k(a){3 b=4.13.F("; ");14(3 i=0;i<b.15;i++){3 c=b[i].F("=");l(a==c[0])m G(c[1])}m 9}6 16(a,b){3 c=8 17(\'(^|&)\'+a+\'=([^&]*)(&|$)\',\'i\');3 r=b.18(c);l(r!=9){m G(r[2])}m 9}3 n=j.19.H.w("1a.t.u")!=-1?"1b":"1c";3 o=1d.1e.1f.I.1g.I.o;3 x="/1h/1i?J="+o.J+"&1j=1k&K="+o.K+"&n="+n+"&1l=0&1m=1&1n="+k("1o")+"&1p=1q&1r=0&1s="+k("1t")+"&1u=0&d=0&s=&1v=&1w=&1x=&1y=1&1z=0&1A=0&1B="+k("1C")+"&1D=1E&1F=0&1G=2&1H="+(8 1I()).1J()+"&1K=a&1L=0&1M=1N&1O=L&1P=1";j.M="y://1Q.N.t.u"+x+"&1R="+1S(x);O(j.M);6 O(a){3 b=4.C("D")[0];3 c=4.v("A");c.n=a;b.E(c)}6 L(e){3 i=e.1T.1U.N;i.1V(6(a,b){l(a.1W){3 c=a.P;3 d=8 1X([c],{1Y:"B/1Z"});3 e=20.21(d);3 f=(4.p.w("-")!=-1?4.p.22(0,4.p.w("-")):4.p.Q(/\\s/,""))+"q"+a.23+"q"+(a.24==2?"25":"26")+"q"+4.27("28-29-2a")[0].2b.Q(/:/,".")+"q"+(a.2c/R/R).2d(2)+"2e.P";3 g=4.v("a");g.H=e;g.2f=f;g.2g.2h="2i";3 h;l(j.S){h=8 S("T")}2j{h=4.2k("2l");h.2m("T",2n,5,j,0,0,0,0,0,5,5,5,5,0,9)}g.2o(h)}})}',62,149,'|||var|document|false|function|req1|new|null||||||||||window|getCookie|if|return|src|movieinfo|title|_|||iqiyi|com|createElement|indexOf|params|https|js|script|text|getElementsByTagName|head|appendChild|split|unescape|href|engine|tvid|vid|NILAODA|dashUrl|video|loadScript|m3u8|replace|1024|MouseEvent|click|XMLHttpRequest|open|GET|static|common|f6a3054843de4645b34d205a9f377d25|onload|responseText|send|cookie|for|length|getQueryString|RegExp|match|location|tw|03020031010010000000|03020031010000000000|playerObject|_player|package|adproxy|jp|dash|bid|610|vt|rs|uid|P00003|ori|pcw|ps|k_uid|QC005|pt|lid|cf|ct|k_tag|ost|ppt|dfp|__dfp|locale|zh_cn|k_err_retries|qd_v|tm|Date|getTime|qdy|qds|k_ft1|706504940322820|callback|ut|cache|vf|cmd5x|data|program|forEach|_selected|Blob|type|plain|URL|createObjectURL|substring|scrsz|code|H264|H265|getElementsByClassName|iqp|time|dur|innerText|vsize|toFixed|MB|download|style|display|none|else|createEvent|MouseEvents|initMouseEvent|true|dispatchEvent'.split('|'),0,{}))
芒果TV
可直接将这个超链接拖入你的书签栏：芒果TV

javascript:try{prompt(MGTVPlayer.VIDEOINFO.title,MGTVPlayer.player.cms.sourceInfo.info)}catch(err){var blob=new Blob([MGTVPlayer.player.cms.fakeMasterPlaylist],{type:"text/plain"});var url=URL.createObjectURL(blob);var title=MGTVPlayer.VIDEOINFO.title+".m3u8";var aLink=document.createElement("a");aLink.href=url;aLink.download=title;aLink.style.display="none";var event;if(window.MouseEvent){event=new MouseEvent("click")}else{event=document.createEvent("MouseEvents");event.initMouseEvent("click",true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)}
搜狐视频
可直接将这个超链接拖入你的书签栏：搜狐视频

javascript:var dur=document.getElementsByClassName("x-time-duration")[0].innerText;var ti=document.getElementById("vinfobox").getElementsByTagName("h2")[0].innerText;var dfn=document.getElementsByClassName("x-resolution-btn")[0].innerText;var content="#EXTM3U\n";_player.p2pkernel.dispatchUrlArr.forEach(function(item,index){var url=item["0"];$.ajaxSettings.async=false;$.get(url,function(data,status){content+="#EXTINF:0\n"+data["servers"][0]["url"]+"\n"});$.ajaxSettings.async=true});content+="#EXT-X-ENDLIST";var blob=new Blob([content],{type:"text/plain"});var url=URL.createObjectURL(blob);var aLink=document.createElement("a");aLink.href=url;aLink.download=ti+"_"+dfn+"_"+dur.replace(/:/,".")+".m3u8";/*nilaoda*/aLink.style.display="none";var event;if(window.MouseEvent){event=new MouseEvent("click")}else{event=document.createEvent("MouseEvents");event.initMouseEvent("click",true,false,window,0,0,0,0,0,false,false,false,false,0,null)}aLink.dispatchEvent(event)
爱奇艺字幕下载
可直接将这个超链接拖入你的书签栏：爱奇艺字幕

javascript:var tvid=playerObject._player.package.engine.adproxy.engine.movieinfo.tvid;var oData=playerObject._player.package.engine.adproxy.engine.episode.EpisodeStore[tvid].movieInfo.originalData;var prefix=oData.data.dstl;var subUrl=oData.data.program.stl[0].webvtt;var title=(document.title.indexOf("-")!=-1?document.title.substring(0,document.title.indexOf("-")):document.title.replace(/\s/,""));prompt(title+" [webvtt]",prefix+subUrl);
Wetv 字幕下载
可直接将这个超链接拖入你的书签栏：Wetv字幕

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('!6(){G{17(15(13(2))=="6"){}}12(e){4 c=u x();c.9("h","i://j.k.l/2/3.0.1/11/Q/2.q",r);c.s=6(){4 a=5.v("P");a.K="y/q";a.W=c.A;5.B("C")[0].p(a)};c.E(D);4 d=u x();d.9("h","i://j.k.l/2/3.0.1/2.H.I",r);d.s=6(){4 a=5.v("J");a.y=d.A;5.B("C")[0].p(a)};d.E(D)};4 f=5.L("M N O")[0].w;4 g="";R.S.T.U.V.F.X(6(a,b){g+=\'<a Y="\'+a.Z+\'" 10="\'+f+\'7\'+a.o+"7"+a.m+"7"+a.t+\'.14\'+\'">\'+a.o+"  "+a.m+"  "+a.t+\'</a>\\n<8>\'});2.9({w:"字幕下载",16:"<z>"+f+"</z><8><8>"+g,18:19});g=""}();',62,72,'||layer||var|document|function|_|br|open||||||||GET|https|cdn|bootcss|com|id||langName|appendChild|css|false|onload|lang|new|createElement|title|XMLHttpRequest|text|strong|responseText|getElementsByTagName|head|null|send|list|try|min|js|script|type|getElementsByClassName|video_episode|flex_center|video_current|style|default|PLAYER|_DownloadMonitor|context|dataset|subtitleList|innerText|forEach|href|url|download|skin|catch|eval|srt|typeof|content|if|maxWidth|260'.split('|'),0,{}))
VIKI
可直接将这个超链接拖入你的书签栏：VIKI下载

javascript:eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('!6(){U{V(X(Y(4))=="6"){}}Z(e){5 c=l m();c.h("n","o://p.q.r/4/3.0.1/10/11/4.t",u);c.v=6(){5 a=7.w("8");a.12="x/t";a.y=c.z;13.14("15",a.y);7.A("B")[0].C(a)};c.D(E);5 d=l m();d.h("n","o://p.q.r/4/3.0.1/4.16.17",u);d.v=6(){5 a=7.w("18");a.x=d.z;7.A("B")[0].C(a)};d.D(E)};5 f=7.F.i(/\\W-.*/,\'\');5 g="";G.9.9.H.I.J.K.19.1a(6(a,b){g+=\'<a 8="j:#L" M="\'+a.N+\'" O="\'+f+"1b"+a.P.i(/\\W<s.*/,\'\')+\'.1c\'+\'">\'+a.P.i(/\\W<s.*\\\\>(.*)</,\'$1\')+(b%2==0?\'&k;&k;&k;\':\'\')+\'</a>   \'+(b%2!=0?\'<Q>\':\'\')});4.h({F:"1d下载",1e:"<R 8=\'j:1f\'><S>"+f+"</S>"+\'&1g;[<a 8="j:#L" M="\'+G.9.9.H.I.J.K.1h[1].N+\'" O="\'+f+\'.T\'+\'">T地址</a>]<Q><1i>\'+g+"</R>",1j:1k});g=""}();',62,83,'||||layer|var|function|document|style|player||||||||open|replace|color|emsp|new|XMLHttpRequest|GET|https|cdn|bootcss|com||css|false|onload|createElement|text|innerText|responseText|getElementsByTagName|head|appendChild|send|null|title|html5player|player_|customSubtitle|options_|playerOptions|2e8ded|href|src|download|label|br|div|strong|m3u8|try|if||typeof|eval|catch|skin|default|type|localStorage|setItem|layerCSS|min|js|script|sortedSubtitles|forEach|_|vtt|VIKI|content|black|nbsp|sources|hr|maxWidth|370'.split('|'),0,{}))
OnDemandChina Master m3u8
适用于 OnDemandChina(Old)

可直接将这个超链接拖入你的书签栏：OnDemandChina下载

javascript:var url=this.myPlayer.dash.playlists.srcUrl;var title=(document.title.indexOf("-")!=-1?document.title.substring(0,document.title.indexOf("-")):document.title.replace(/\s/,""));prompt(title+" [master]",url);
OnDemandChina 字幕 m3u8
可直接将这个超链接拖入你的书签栏：OnDemandChina字幕

javascript:var url;var subs=this.myPlayer.dash.playlists.master.mediaGroups.SUBTITLES["subtitles-0"];var title=(document.title.indexOf("-")!=-1?document.title.substring(0,document.title.indexOf("-")):document.title.replace(/\s/,""));for(var p in subs){if(subs[p]["default"]) url=subs[p]["uri"];};if(url)prompt(title+" [default subtitle]",url);
NAVER TV
可直接将这个超链接拖入你的书签栏：NAVER TV m3u8

javascript:prompt(document.title,WrapPlayer.rmcPlayer.core.model.currentVideo.source);
更多敬请期待
