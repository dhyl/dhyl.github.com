---
title: rails_g_model
date: 2017-03-15 10:09:30
tags:
---
## rails 创建数据表
------

> * ![](/2017-03-15.png)
> * 上图创建了一张表，表名为：`see_elders`
> * `see_content,see_image`为俩字符串类型的字段
> * `t.references :company_doctor, foreign_key: true`该代码将生成company_doctor这张表的外键及索引字段`company_doctor_id`
> * `comment: "看望老人图片记录"`该代码为字段描述
> * `t.timestamps`该代码讲生成 created_at,updated两个字段
------