# Memos

20220718 wpf config
```
Configuration configuration = ConfigurationManager.OpenExeConfiguration(ConfigurationUserLevel.None);
configuration.AppSettings.Settings.Add("test2", "test success!");
configuration.Save(ConfigurationSaveMode.Modified);
ConfigurationManager.RefreshSection(configuration.AppSettings.SectionInformation.Name);
```
link: https://blog.kgoon.net/4 "ref"
[ref][link]

--------------
