# layui-treeGrid
layui的treeGrid树形菜单的最新版layui-v2.4.5版本的图标丢失解决方法
来源地址:https://www.layui.com/doc/modules/tree.html


现在文档里面缺失了两个图标没办法,只能去Iconfont-阿里巴巴矢量图标库找到文件夹跟展开文件库的字体图标下载下来
新建一个文件夹命名:iconfont,放进去刚下载的文件就好,然后在样式中写入:

body .layui-tree-skin-shihuang .layui-tree-branch {
    font-family: "iconfont" !important;
    font-size: 16px;
    font-style: normal;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

再引入刚下载的文件:
<link rel="stylesheet" href="iconfont/iconfont.css">

就可以了,还是不会用的可以下载我的压缩包查看!
