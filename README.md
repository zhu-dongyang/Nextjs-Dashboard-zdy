## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

# 记录
主要文件下载app文件夹中
app-
    dashboard-一级路由
    layout.tsx-页面布局，为页面视图页面，里面的children为page.tsx组件，主要用于为整个页面设置样式、布局
                  根布局必须存在，用于定义页面html和body标签
    page.tsx-页面组件，为各个组件的集合
    lib-数据相关
       -data.ts-具体的查询sql编写
       -placeholder-data.js-数据库预存数据
    ui-单个组件
public-静态资源图片等
scripts-脚本文件
       -seed.js-连接数据库并创建表

# 注意
http://localhost:3000/ 为app目录layout.tsx展示页面
后续路由层级与代码文件夹层级相同，必须要有page.jsx
服务器组件的props为  props======> { params: {}, searchParams: { query: '12' } }
                        params为路由参数 searchParams为url传参