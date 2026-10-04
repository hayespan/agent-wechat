---
"@agent-wechat/agent-wechat": minor
"@agent-wechat/cli": minor
"@agent-wechat/shared": minor
"@agent-wechat/agent-server": minor
---

Expose everyone @-mentioned in a group message as `Message.mentions` (wxid plus contact display name when resolvable), parsed from the `<atuserlist>` in the message source XML with the existing content-XML fallback for type-49 appmsg. `isMentioned` keeps its "is the logged-in user among them" meaning.
