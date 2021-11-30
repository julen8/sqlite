# GORM Sqlite Driver

![CI](https://github.com/hello-xnew/sqlite/workflows/CI/badge.svg)

## 使用 modernc.org/sqlite 驱动纯go实现,不需要cgo支持

## USAGE

```go
import (
  "github.com/newQian/sqlite"
  "gorm.io/gorm"
)

// modernc.org/sqlite
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.

