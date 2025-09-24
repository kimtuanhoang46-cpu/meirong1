# 美容院预约最小版

- 打开 index.html 即可操作：
  - 邮箱验证码登录（Supabase OTP）
  - 创建预约、查看我的预约、取消预约
- 管理员页面稍后添加（需要额外 RLS 策略或 Edge Function）。

## 本地预览
- 直接用浏览器打开 index.html（如果跨域缓存问题，请用本地静态服务器）。

## 环境
- Supabase URL: https://yxumytufdjardhwlrexr.supabase.co
- anon key 已内置于页面，仅用于公开前端。切勿在前端暴露 service_role。
