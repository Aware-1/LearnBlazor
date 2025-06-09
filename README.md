ssr->render in server & send JS
Intractive->Runs entirely on the server
assembly -> C# convert to WASM & in client device download and Run 
hubrid
---------------
app->   <Routes />
توی این مشخص میکنیم با کدوم ادرس کدوم کامپوننت اجرا شود
-----
خوده Roites Component
کارش اینه html بسازه
DefaultLayout -> main layout -> @body (renderBode همون)

page -> routable component  =>  HAVE @page(همون ادرس)
iner component -> noun Routable component
---------------

render mode??????????????
--------------
Directivr
------------
event
------
parameter in URL=> if u wanna use parameter first "server/{is:int?}" next write prop With same name and [parameter][supplyParemeterFromQuery]
? means allow null


[parameter] حتی بخوای تو در تو کامپوننت بسازی باید از این طریق صداش بزنی
override onParameterSet()

<EditForm   Medel=""    FormName=""  onsubmit=""> 
        StateHasChanged(); // اجباری برای به‌روزرسانی UI
