影响一个或多个仓库的{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.21" %}{% data variables.product.prodname_dependabot_alerts %}{% else %}安全警报{% endif %}电子邮件通知包含 `X-GitHub-Severity` 标头字段。 您可以使用 `X-GitHub-Severity` 标头字段的值过滤{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.21" %}{% data variables.product.prodname_dependabot_alerts %}{% else %}安全警报{% endif %}的电子邮件通知。