# golang-basic

## Шаг 1: Установить Go SDK

1. Перейдите на официальный сайт Go: [https://go.dev/dl](https://go.dev/dl)
2. Скачайте версию, соответствующую вашей ОС.
3. Установите Go, следуя инструкциям.
4. Проверьте установку:

```bash
go version
```

---

## Шаг 2: Установить и настроить IDE

Рекомендуемые варианты:

- [GoLand](https://www.jetbrains.com/go/) (платно с пробным периодом)
- [Visual Studio Code](https://code.visualstudio.com/) + плагин "Go" от Google

После установки IDE:

- Настройте путь к Go SDK, если требуется.
- Убедитесь, что IntelliSense/автодополнение работают.

---

## Шаг 3: Создать учётную запись на GitHub

1. Перейдите на [https://github.com](https://github.com)
2. Зарегистрируйтесь и подтвердите почту.
3. Настройте двухфакторную аутентификацию (рекомендуется).

---

## Шаг 4: Установить Git и GitHub Desktop

- Установите Git: [https://git-scm.com](https://git-scm.com)
- Установите GitHub Desktop: [https://desktop.github.com](https://desktop.github.com)

Проверьте установку Git:

```bash
git --version
```

---

## Шаг 5: Создать публичный репозиторий

1. Зайдите в GitHub → `New repository`
2. Назовите его, например, `golang-basic`
3. Сделайте его **публичным**
4. Не добавляйте `.gitignore` или `README` (создадим локально)

---

## Шаг 6: Клонировать репозиторий на своё устройство

Через GitHub Desktop:

1. `File → Clone repository`
2. Выберите `golang-basic`
3. Выберите путь для сохранения

Или через терминал:

```bash
git clone https://github.com/ВАШ_ЮЗЕРНЕЙМ/go-homework.git
cd go-homework
```

---

## Шаг 7: Написать первые строчки кода

1. Внутри проекта создайте файл `main.go`:
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

2. Запустите:

```bash
go run main.go
```
