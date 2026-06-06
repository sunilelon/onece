# onece

A compact public file hub for selected proxy rule artifacts, designed for direct Raw-file consumption instead of broad repository browsing.

<p>
  <a href="#english"><strong>English</strong></a>
  ·
  <a href="#中文"><strong>中文</strong></a>
</p>

<p>
  <img alt="Purpose" src="https://img.shields.io/badge/purpose-raw%20rule%20files-2f6f4e">
  <img alt="Primary Branch" src="https://img.shields.io/badge/rules%20branch-sing--box--rules-315f72">
  <img alt="Access" src="https://img.shields.io/badge/access-exact%20raw%20url-b36b24">
  <img alt="License" src="https://img.shields.io/badge/license-Apache--2.0-555555">
</p>

> Public repositories are not private storage. Only commit files that are safe to expose through exact Raw URLs.

## English

`onece` hosts a small set of publicly downloadable proxy rule artifacts. Files are intended to be consumed directly through `raw.githubusercontent.com` by exact file path, not as a general-purpose public file browser.

### At a Glance

| Item | Value |
| --- | --- |
| Main purpose | Host selected public proxy rule artifacts. |
| Preferred access | Direct Raw URL to a specific file. |
| Rules branch | `sing-box-rules` |
| Rule scope | IP rules and Site/domain rules. |
| Intended use | Learning, research, and personal reference only. |

### Branches

| Branch | Purpose | Scope | Notes |
| --- | --- | --- | --- |
| `master` | Project documentation and base configuration | `README.md`, `LICENSE`, `.gitignore` | Documents the repository purpose and ignore rules. |
| `sing-box-rules` | Maintains sing-box rule artifacts | IP rules and Site/domain rules, such as `.srs` files | For learning and reference only. Completeness, accuracy, and availability are not guaranteed. |

### Public Rule Files

| Type | File | Raw URL |
| --- | --- | --- |
| GeoIP | `rule-set-geoip/geoip-cn.srs` | `https://raw.githubusercontent.com/sunilelon/onece/sing-box-rules/rule-set-geoip/geoip-cn.srs` |
| Geosite | `rule-set-geosite/geosite-cn.srs` | `https://raw.githubusercontent.com/sunilelon/onece/sing-box-rules/rule-set-geosite/geosite-cn.srs` |

### Usage

Reference the exact Raw URL of the file you need in sing-box or any other tool that supports remote rule files:

```text
https://raw.githubusercontent.com/sunilelon/onece/sing-box-rules/rule-set-geosite/geosite-cn.srs
```

### Maintenance Rules

- Only commit rule files that are confirmed safe for public access.
- Do not commit `.env` files, keys, private configuration, passwords, temporary files, or local IDE state.
- Before adding a public file, verify that it does not contain accounts, tokens, subscription URLs, or other sensitive data.
- The `sing-box-rules` branch is only for rule artifact maintenance, not general file storage.

### Disclaimer

This project is for learning, research, and personal reference only. Rule files may be collected or converted from public materials or local sources. Timeliness, accuracy, completeness, and availability are not guaranteed.

<br>
<br>
<br>

---

<br>
<br>
<br>

## 中文

`onece` 用于托管少量可公开下载的代理规则文件。仓库内容主要通过 `raw.githubusercontent.com` 按文件路径访问，不建议也不承诺提供完整目录浏览用途。

> 注意：如果 GitHub 仓库或分支是公开的，已经提交的文件理论上都可以被访问。本项目通过 `.gitignore` 和分支隔离减少误提交风险，但不能替代私有仓库或访问控制。

### 快速概览

| 项目 | 内容 |
| --- | --- |
| 主要用途 | 托管少量确认可公开访问的代理规则文件。 |
| 推荐访问方式 | 使用具体文件的 Raw URL 直接下载。 |
| 规则分支 | `sing-box-rules` |
| 规则范围 | IP 规则、Site/域名规则。 |
| 使用场景 | 仅用于学习、研究和个人参考。 |

### 分支说明

| 分支 | 用途 | 内容范围 | 说明 |
| --- | --- | --- | --- |
| `master` | 项目说明与基础配置 | `README.md`、`LICENSE`、`.gitignore` | 用于说明项目用途和维护忽略规则。 |
| `sing-box-rules` | 维护 sing-box 规则文件 | IP 规则、Site/域名规则，例如 `.srs` 文件 | 仅用于学习参考，不保证完整性、准确性或可用性。 |

### 当前公开规则文件

| 类型 | 文件 | Raw 下载地址 |
| --- | --- | --- |
| GeoIP | `rule-set-geoip/geoip-cn.srs` | `https://raw.githubusercontent.com/sunilelon/onece/sing-box-rules/rule-set-geoip/geoip-cn.srs` |
| Geosite | `rule-set-geosite/geosite-cn.srs` | `https://raw.githubusercontent.com/sunilelon/onece/sing-box-rules/rule-set-geosite/geosite-cn.srs` |

### 使用方式

在 sing-box 或其他支持远程规则文件的工具中，直接引用需要的单个 Raw 文件地址：

```text
https://raw.githubusercontent.com/sunilelon/onece/sing-box-rules/rule-set-geosite/geosite-cn.srs
```

### 维护约定

- 只提交确认可以公开访问的规则文件。
- 不提交 `.env`、密钥、私有配置、密码、临时文件或本地 IDE 配置。
- 新增公开文件前，需要确认文件内容不包含账号、Token、订阅地址或其他敏感信息。
- `sing-box-rules` 分支只用于规则文件维护，不作为通用文件存储使用。

### 免责声明

本项目内容仅用于学习、研究和个人参考。规则文件可能来自公开资料整理或本地转换，不保证实时性、准确性、完整性，也不对使用结果承担责任。
