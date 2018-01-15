# use-package-el-get
el-get support for use-package

## Usage:

```elisp
(require 'use-package-el-get)
(use-package-el-get-setup)

(use-package req-package
  :el-get t)

;; or

(use-package req-package
  :el-get req-package)
```
