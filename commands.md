لمعرفة تعليمات الاطار

    rails -h
انشاء تطبيق

    rails new app_name

للدخول لمجلد التطبيق

    cd app_name

ثم داخل المجلد

    rails --tasks

أو

    rails -h

للوصول للتعليمات لكل أمر

    rails g -h

انشاء كنترولر

    rails g controller homepage index about

## مثال آخر

للوصول للتعليمات

    rails g scaffold -h

عمل تطبيق منشورات

    rails generate scaffold post title:string body:text published:boolean

عمل تطبيق مؤلفين وربطه بالمنشورات

    rails generate scaffold author name:string post:references

تمرين على اضافة نظام تسجيل دخول
الجيم المستخدم

[https://github.com/heartcombo/devise](https://github.com/heartcombo/devise)

بعض القوالب للاطار
[https://github.com/excid3/jumpstart](https://github.com/excid3/jumpstart)

[https://bullettrain.co/](https://bullettrain.co/)











