Для скачивания можно открыть справа [Releases](https://github.com/Jipok/MoySklad-Kassa-AppImage/releases) и скачать последний appimage. После сделать его исполняемым либо через ваш файловый менджер либо через:

```bash
chmod +x ./moysklad-kassa_4.267.0-7745.AppImage
```

Но я рекомендую поставить zap: https://github.com/srevinsaju/zap

С ним установка проста:
```bash
zap install --github --from=Jipok/MoySklad-Kassa-AppImage
```

И обновления тоже: `zap upgrade`

Не поддерживает ubuntu 20 из-за протухшего там glibc
