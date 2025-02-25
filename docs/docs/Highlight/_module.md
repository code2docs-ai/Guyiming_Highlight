# 基础信息

|      |      |
|------|------|
| 编码语言 | .java |
| 代码路径 | Highlight |
| 概述说明 | None |

# 说明

None


### 包内部结构视图

graph TD;
Highlight --> HighlightBlazor;
Highlight --> .git;
HighlightBlazor --> wwwroot;
.git --> hooks;
.git --> branches;
.git --> refs;
.git --> logs;
.git --> objects;
.git --> info;
.git --> remotes;
.logs --> refs;
.objects --> info;
.objects --> pack;
.Demo --> Demo1;
Demo1 --> Client;
Demo1 --> Server;
Client --> wwwroot;
Client --> Pages;
Client --> Properties;
Client --> Shared;
Server --> Pages;
Server --> Controllers;
Server --> Properties;
Demo1/Client/wwwroot --> css;
css --> bootstrap;
css --> open-iconic;
open-iconic --> font;
font --> css;
font --> fonts;
Demo1/Client/wwwroot/css/open-iconic --> font;
Demo1/Client/wwwroot/css/open-iconic/font --> css;
Demo1/Client/wwwroot/css/open-iconic/font --> fonts;
Pages --> Shared;

文件和文件夹的层级关系：
根目录为Highlight，下级包含HighlightBlazor, .git, .logs, .objects, Demo1；
其中.Demo1包含子文件夹Client和Server；
而Client下又包含子文件夹wwwroot, Pages, Properties, Shared；
Server下又包含文件夹Pages, Controllers, Properties；
wwwroot下还有子文件夹css，其中css文件夹包含子文件夹bootstrap和open-iconic；
open-iconic文件夹包含子文件夹font，font文件夹下包括子文件夹css和fonts。

