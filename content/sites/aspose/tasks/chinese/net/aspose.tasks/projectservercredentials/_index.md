---
title: ProjectServerCredentials
second_title: Aspose.Tasks for .NET API 参考
description: 用于连接到 Project Online 或 Project Server 的本地实例的凭据
type: docs
weight: 1230
url: /zh/net/aspose.tasks/projectservercredentials/
---
## ProjectServerCredentials class

用于连接到 Project Online 或 Project Server 的本地实例的凭据。

```csharp
public sealed class ProjectServerCredentials
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ProjectServerCredentials](projectservercredentials#constructor)(string, NetworkCredential) | 初始化[`ProjectServerCredentials`](../projectservercredentials)使用 Project Web Access 端点的 URL 和网络凭据的类。 |
| [ProjectServerCredentials](projectservercredentials#constructor_1)(string, string) | 初始化[`ProjectServerCredentials`](../projectservercredentials)类使用 SharePoint 网站的 URL 和 SharePoint 的 PWA（项目 Web 访问）网站的有效 SPOIDCRL 授权令牌。 |
| [ProjectServerCredentials](projectservercredentials#constructor_2)(string, string, string) | 初始化[`ProjectServerCredentials`](../projectservercredentials)使用 SharePoint 网站的 URL、用户名和密码的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AuthToken](../../aspose.tasks/projectservercredentials/authtoken) { get; } | 获取 SharePoint 实例的授权令牌。 |
| [SiteUrl](../../aspose.tasks/projectservercredentials/siteurl) { get; } | 获取 PWA 在 SharePoint 站点的 URL 或本地 Project Server 的 URL。 例如，https://your_company_name.sharepoint.com/sites/pwa"; |
| [UserName](../../aspose.tasks/projectservercredentials/username) { get; } | 获取 SharePoint 网站的用户名。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [ToString](../../aspose.tasks/projectservercredentials/tostring)() | 返回此实例的字符串表示形式。 |

### 也可以看看

* 命名空间 [Aspose.Tasks](../../aspose.tasks)
* 部件 [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
