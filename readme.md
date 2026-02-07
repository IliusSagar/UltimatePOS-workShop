## About Ultimate POS

Ultimate POS is a POS application by [Ultimate Fosters](http://ultimatefosters.com), a brand of [The Web Fosters](http://thewebfosters.com).

## Installation & Documentation
You will find installation guide and documentation in the downloaded zip file.
Also, For complete updated documentation of the ultimate pos please visit online [documentation guide](http://ultimatefosters.com/ultimate-pos/).

## Security Vulnerabilities

If you discover a security vulnerability within ultimate POS, please send an e-mail to support at thewebfosters@gmail.com. All security vulnerabilities will be promptly addressed.

## License

The Ultimate POS software is licensed under the [Codecanyon license](https://codecanyon.net/licenses/standard).

## Server Deployment File & Code
==> Http/Controllers/TransactionPaymentController.php
==> resources/views/cash_register/payment_details.blade.php
==> App/Utils/CashRegisterUtil.php
==> app/http/controllers/ExpenseController.php

## POS & Admin Expense File Find Out
    => resources/views/expense/add_expense_modal.blade.php
    => resources/views/expense/create.blade.php
    => app/Http/Controllers/ExpenseController.php [361 = store]
    => app/Utils/TransactionUtil.php [5898 = createExpense]

## Register Customs Developement File

==> Http/Coontrollers/CashRegisterController.php
    ==> getRegisterDetails [135]
==> Http/Utils/CashRegisterUtil.php
    ==> getRegisterDetails [268]
==> resources/views/cash_egister/payment_details.blade.php
==> Database : cash_register_transactions
