# company-yankpad
Company mode autocompletion and expansion for yankpad snippets using keyword
expansion feature of yankpad.

 Add something similar to your init file

    (add-hook 'dart-mode-hook (lambda ()
     (set (make-local-variable 'company-backends)
      '(company-dart (company-dabbrev company-yankpad)))))
