1. api.go#8
``` Info() *User ```
2. bot.go#138
```go

func (b *Bot) Info() *User {
	return b.Me
}
```
3. go.mod
```module github.com/xnumb/tele```
4. 包名: ```package tele```