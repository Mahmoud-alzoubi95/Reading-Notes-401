# Custom User Model
The authentication that comes with Django is good enough for most common cases, but you may have needs not met by the out-of-the-box defaults. Customizing authentication in your projects requires understanding what points of the provided system are extensible or replaceable. This document provides details about how the auth system can be customized.

Authentication backends provide an extensible system for when a username and password stored with the user model need to be authenticated against a different service than Django’s default.



### Setup 
- create and navigate into a dedicated directory called accounts for our code
- install Django
- make a new Django project called config
- make a new app accounts
- start the local web server


### Custom User Model
- update config/settings.py
- create a new CustomUser model
- create new UserCreation and UserChangeForm
- update the admin

![](https://learndjango.com/static/images/tutorials/custom_user_model/home_loggedout.png)
![](https://learndjango.com/static/images/tutorials/custom_user_model/login.png)
![](https://learndjango.com/static/images/tutorials/custom_user_model/signup.png)
![](https://learndjango.com/static/images/tutorials/custom_user_model/signup.png)


## Conclusion

Now that our custom user model is configured you can easily and at any time add additional fields to it. See the Django docs for further instructions.

You can also check out DjangoX, which is an open-source Django starter framework that includes a custom user model, email/password by default instead of username/email/password, social authentication, and more.




