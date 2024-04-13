# dj-multiple-settings-config
Django configuration, focusing specifically on the management of multiple settings for projects that demand scalability.

#### 📍Remenber set env varible `DJANGO_SETTINGS_MODULE` 

🟢 **Linux**

In this case is for **dev** enviroment

`export DJANGO_SETTINGS_MODULE=core.settings.dev`

🟢  **Windows**

In this other example the configuration is for **prod** enviroment

`
setx DJANGO_SETTINGS_MODULE "core.settings.prod"
`

📍 Error: **"A server error occurred. Please contact the administrator."**

If you face the error mentioned above, ensure that the `DEBUG` setting is set to `False` in the `dev.py` file. Additionally, verify that the environment variable is correctly configured with export `DJANGO_SETTINGS_MODULE=core.settings.dev`

<a href="https://mefardales.medium.com/django-configuration-managing-multiple-settings-for-scalable-projects-0afd46cb6a6b">🎖️Link</a> for full explanation.