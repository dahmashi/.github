## Welcome to GitHub for Dahmashi Group 👋

### 🙋‍♀️ A short introduction - what is your organization all about?

Dahmashi Group of companies owns and operates various proprietary custom software for internal use, and also for public consumption. Our core Technology stack currently includes the following web-based products:

| Name      | Description                           | Type    | Maintainer                                 | Location                                                                                                        | ✔️ Pros                                                                  | ❌ Cons                                                                                                                               |
| --------- | ------------------------------------- | ------- | ------------------------------------------ | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| BongoBaba | B2B e-Commerce Application            | Public  | [Large IT Solution](https://large-it.com/) | [url](https://bongobaba.com/)                                                                                   |                                                                          | undocumented                                                                                                                          |
| One-ERP   | Finance / Accounts ERP Software       | Private | [One ICT Limited](https://one-ict.com/)    | [private ip](http://192.168.2.107:4200)                                                                         |                                                                          | undocumented / incomplete / WIP                                                                                                       |
| MMS       | Manpower Management System            | Public  | [3DEVs IT Ltd](https://3-devs.com/)        | [private ip](http://192.168.2.107:85) / [public ip](http://103.17.37.98:8002) / [url](https://mms.dahmashi.com) | clean UI / easy hosting on custom domain with some configuration updates | undocumented / buggy / poor login security / ongoing license fees?                                                                    |
| [Jute-ERP](https://github.com/dahmashi/jute-erp)  | Internal Jute Industries ERP Software | Public  | [@zaman6g](mailto:zaman6g@gmail.com)       | [private ip](http://192.168.2.120:1213) / [public ip](http://103.17.37.98) / [url](https://jute.dahmashi.com)   |                                                                          | undocumented / features being added / unpolished & outdated UI / no easy hosting to custom domain without IIS / ongoing license fees? |


## **Policies / Guidelines**

### 🌈 Contribution guidelines - how can the Dahmashi community get involved?

- **Repository type**: Generally, create **private** repositories for `dahmashi` org, unless authorised by org owners / admins
- **Gitignore**: Initially, commmit appropriate `.gitignore` file for GitHub repositories, either using Github built-in templates during GitHub repository creation or via online tools like [gitignore.io](https://gitignore.io) for your project stack
- **Secrets**: Runtime, build, and development environments must be replicable across devices and teams; store environment variables in portable `.env` files for local development, then request GitHub repository / org admins to configure environments via [Github Secrets](https://docs.github.com/en/actions/security-for-github-actions/security-guides/using-secrets-in-github-actions#creating-secrets-for-a-repository)

> [!WARNING]
> **Never** commit sensitive secrets / credentials to GitHub in plaintext (e.g. authenticated database connection strings). **Always** `.gitignore` all relevant `.env*` files used for local development environments to ignore them from version control.
>
> Best practice is to manage sensitive information in your GitHub organization, repository, or environments level as these are stored encrypted and have built-in access control for sensitive information

### 👩‍💻 Useful resources - where can the Dahmashi community find your docs? Is there anything else the community should know?

Dahmashi Group of companies are [ISO9001:2015](https://www.iso.org/standard/62085.html) certified. As such, being both a vendor and producer of custom software solutions in our companies, our policies and guidelines are aligned with this certification. Any Dahmashi employee contributing to software design / development must follow our internal IT Policies to support ISO 9001.

> [!NOTE]
> It is our intention to bring all custom Dahmashi software under our GitHub org [@dahmashi](https://github.com/dahmashi). This gives our group of companies increased visibility to changes in our custom software codebases as we request new features, report bugs to be fixed to maintainers, etc. during the software development lifecycle of our various software products, whether internal or public-facing. It also ensures all our digital products align with ISO 9001:2015 standards and specifications and guidelines which our group is committed to maintain.

**These internal policies help align software development with ISO 9001:**

1. [Git Version Control Policy](https://docs.google.com/document/d/1hIgS53W1F4jwTb99LNsM3UZjBXuY7jqtTxBttPj6_sg/edit?usp=sharing)

### 🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
