## Proje 1
- Dotnet SDK 6'yı base image alarak, içinde sadece fortify yüklü, bu pronin dosyaları içinde olmayacak şekilde bir imaj yaratın.
- Yaratılan imajı <dockerhub kullanıcı ismi>/fortify:dotnet ismiyle dockerhub'a yükleyip, private'a çekin.
- Bu imaj aşağıdaki gibi çağırıldığında, abuna benzer bir sonuç vermeli. 

```
docker run --rm -it <dockerhub kullanıcı ismi>/fortify:dotnet /opt/Fortify/Fortify_SCA_and_Apps_22.1.1/bin/sourceanalyzer

Fortify Static Code Analyzer 22.1.1.0017
Copyright (c) 2003-2022 Micro Focus or one of its affiliates

For command-line help, type 'sourceanalyzer -h'
```


## Proje 2


