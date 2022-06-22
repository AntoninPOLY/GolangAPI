<p align="center">
  # GolangAPI
  This a simple Golang API created with fiber 👋
  <br>
  <b>Fiber</b> is an <a href="https://github.com/expressjs/express">Express</a> inspired <b>web framework</b> built on top of <a href="https://github.com/valyala/fasthttp">Fasthttp</a>, the <b>fastest</b> HTTP engine for <a href="https://go.dev/doc/">Go</a>. Designed to <b>ease</b> things up for <b>fast</b> development with <b>zero memory allocation</b> and <b>performance</b> in mind.
</p>

## ⚡️ Quickstart

```go
package main

import "github.com/gofiber/fiber/v2"

func main() {
    app := fiber.New()

    app.Get("/", func(c *fiber.Ctx) error {
        return c.SendString("Hello, World 👋!")
    })

    app.Listen(":3000")
}
```

## 🤖 Benchmarks



## ⚙️ Installation

Make sure you have Go installed ([download](https://go.dev/dl/)). Version `1.14` or higher is required.

Initialize your project by creating a folder and then running `go mod init github.com/your/repo` ([learn more](https://go.dev/blog/using-go-modules)) inside the folder. Then install Fiber with the [`go get`](https://pkg.go.dev/cmd/go/#hdr-Add_dependencies_to_current_module_and_install_them) command:

```bash
go get -u github.com/gofiber/fiber/v2
```

## 🎯 Features


## 💡 Philosophy


## ⚠️ Limitations

## 👀 Examples

## 🕶️ Awesome List

## 👍 Contribute


## ☕ Supporters

## ‎‍💻 Code Contributors

## ⭐️ Stargazers

## ⚠️ License
