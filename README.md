# 广州澜特产品原型

广州澜特蓝领招聘、入职、用工及薪酬结算一体化平台原型仓库。

## 原型入口

- [Web 后台管理原型](./web/index.html)
- [移动端小程序原型](./mobile/index.html)
- [原型变更日志](./CHANGELOG.html)

## 目录结构

```text
.
├── index.html          # 统一入口
├── web/
│   └── index.html      # Web 后台原型
└── mobile/
    └── index.html      # 移动端原型
```

## 主要业务链路

岗位发布 → 求职报名/渠道报备 → 面试审核 → 入职登记与审核 → 电子合同 → 员工花名册 → 工时工资结算 → 工资条

## 维护约定

- Web 原型修改后更新 `web/index.html`
- 移动端原型修改后更新 `mobile/index.html`
- 每次原型调整同步追加 `CHANGELOG.html`，记录日期、影响端和主要变更
- 提交信息建议使用 `feat:`、`fix:`、`docs:` 等前缀
