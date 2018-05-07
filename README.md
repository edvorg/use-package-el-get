# use-package-el-get
el-get support for use-package

## Usage:
Install `el-get` with `M-x package-install el-get`

```elisp
(require 'use-package-el-get)
(setq use-package-always-ensure nil)
(use-package-el-get-setup)

;;  then

(use-package cool-fancy-package
  :el-get t)

;; or

(use-package cool-fancy-package-file
  :el-get cool-fancy-package)
```
