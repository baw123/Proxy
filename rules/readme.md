
Stash使用
```
rule-providers:
  zuoyebang-adblock:
    type: http
    behavior: classical
    format: yaml
    url: "https://raw.githubusercontent.com/baw123/Proxy/refs/heads/main/rules/stash/zuoyebang-adblock.yaml"
    path: ./ruleset/zuoyebang-adblock.yaml
    interval: 86400

rules:
  - RULE-SET,zuoyebang-adblock,REJECT   # 放在规则列表靠前的位置
  # ... 其他规则
  ```

  Surge使用
  ```
[Rule]
RULE-SET,https://raw.githubusercontent.com/baw123/Proxy/refs/heads/main/rules/surge/zuoyebang-adblock.list,REJECT
  ```
