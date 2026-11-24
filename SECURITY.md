# Security Policy

[English](#english) | [中文](#中文)

## English

Cofacts (真的假的) is an open-source project run by volunteers. We appreciate everyone who helps keep Cofacts and its users safe. This policy applies to all repositories in the [Cofacts organization](https://github.com/cofacts) that do not have their own `SECURITY.md`.

### Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues, pull requests or discussions.**

Report them privately instead:

1. **GitHub private vulnerability reporting (preferred).** Go to the affected repository, open the **Security** tab and click **Report a vulnerability**. This creates a private security advisory that only you and the maintainers can see.
2. **Email.** If private vulnerability reporting is not available for that repository, or you cannot use GitHub, email **hi@cofacts.tw**.

To help us assess the report, please include:

- The affected repository, and the version, commit or branch
- A description of the vulnerability and its impact
- Steps to reproduce, or a proof of concept
- Any suggested fix or mitigation, if you have one

### Testing guidelines

- **Test only against a local setup** that you run yourself, using the source code and setup instructions in our repositories.
- **Do not test against Cofacts production or staging services**, including the website, API and chatbots. Do not run scanners or automated tools against them, and do not access, modify or delete other people's data.

### What to expect

- We will **acknowledge your report within 7 days**.
- We will **assess the report within 14 days** and let you know what we found and what happens next.
- We will keep you updated while we work on a fix, and coordinate the disclosure with you.
- With your permission, we will **credit you in the published security advisory**.

Cofacts is maintained by volunteers. **We do not run a bug bounty program** and cannot offer monetary rewards.

## 中文

Cofacts 真的假的是由志工維運的開源專案。感謝每一位協助守護 Cofacts 與使用者安全的人。本政策適用於 [Cofacts 組織](https://github.com/cofacts)中所有沒有自己 `SECURITY.md` 的 repository。

### 回報安全漏洞

**請勿透過公開的 GitHub issue、pull request 或 discussion 回報安全漏洞。**

請以私下的方式回報：

1. **GitHub 私密漏洞回報（建議）**：前往受影響的 repository，點選 **Security** 分頁中的 **Report a vulnerability**。這會建立一份只有你與維護者看得到的私密 security advisory。
2. **Email**：若該 repository 沒有開放私密漏洞回報，或你無法使用 GitHub，請寄信至 **hi@cofacts.tw**。

為了方便我們評估，請盡量提供：

- 受影響的 repository，以及版本、commit 或 branch
- 漏洞說明及其影響
- 重現步驟或 proof of concept
- 若有的話，建議的修正或緩解方式

### 測試原則

- **請只在你自己架設的本機環境測試**，可依各 repository 中的原始碼與安裝說明架設。
- **請勿對 Cofacts 正式站（production）或測試站（staging）進行測試**，包含網站、API 與聊天機器人。請勿對其執行掃描器或自動化工具，也請勿存取、修改或刪除他人的資料。

### 處理流程

- 我們會在 **7 天內確認收到**你的回報。
- 我們會在 **14 天內完成評估**，並告訴你評估結果與後續處理方式。
- 修正期間我們會持續與你聯繫，並與你協調揭露時程。
- 經你同意後，我們會在公開的 security advisory 中**列名感謝**你。

Cofacts 由志工維運，**我們沒有漏洞獎金（bug bounty）計畫**，無法提供金錢獎勵。
