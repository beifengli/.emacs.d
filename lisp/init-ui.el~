;; 关闭文件滑动控件
(scroll-bar-mode -1)

;; 显示行号
(global-linum-mode 1)

;; 更改光标的样式（不能生效，解决方案见第二集）
(setq cursor-type 'bar)

;; 关闭启动帮助画面
(setq inhibit-splash-screen 1)

;;高亮当前行
(global-hl-line-mode 1)

;; 更改显示字体大小 120
;; http://stackoverflow.com/questions/294664/how-to-set-the-font-size-in-emacs
(set-face-attribute 'default nil :height 120)

;;---------------------------------------------------------------------------
;; 安装主题
;;---------------------------------------------------------------------------
(add-to-list 'my/packages 'monokai-theme)

;;加载主题
(load-theme 'monokai 1)

;; 文件末尾
(provide 'init-ui)
