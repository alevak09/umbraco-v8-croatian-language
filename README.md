# umbraco-v8-croatian-language
Umbraco v8 backoffice language translation to croatian (hrvatski). File **hr.xml** is not fully translated to croatian so any contributions are welcome.

<img src="https://github.com/alevak09/umbraco-v8-croatian-language/blob/main/assets/lanuage.PNG?raw=true">

## Setup umbraco backoffice language:

- Copy **hr.xml** file from this repository to **Umbraco -> Config -> Lang** folder
- Run your umbraco project on localhost
- **For newer umbraco v8 versions** go to User section, select Admin user and under Language choose Croatian(Hrvatski) language to be displayed in backoffice
- Save changes
- Referesh F5 umbraco backoffice
- Now your backoffice should be displayed in croatian language for Admin user

- **For older umbraco v8 versions** before runing your umbraco project in Visual Studio, open web.config file and change **Umbraco.Core.DefaultUILanguag** key in **<appSettings>** section: 
```
<add key="Umbraco.Core.DefaultUILanguage" value="hr-HR" />
```

- Save changes
- Run your umbraco project on localhost
- Login to umbraco backoffice
- Now your backoffice should be displayed in croatian language for Admin user

<br><br>
**Any contributions are appreciated** 
