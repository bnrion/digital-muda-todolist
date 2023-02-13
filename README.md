# digital-muda-todolist

Digital Muda Todolist menggunakan Spring Boot dan Thymeleaf
![todo](https://user-images.githubusercontent.com/75271856/218431605-ba1ee310-d2f3-4f5a-95e5-cf851d662bf6.png)

Aplikasi ini dibuat menggunakan

- Spring Boot 3.0.2
- Spring Data JPA
- H2 Database
- Thymeleaf
- Intellij

# instruksi untuk deployment

```git clone https://github.com/bnrion/digital-muda-todolist.git```

download bootstrap jar dari
1. bootstrap versi 5.2.3 dari https://mvnrepository.com/artifact/org.webjars/bootstrap
2. boostrap icon versi 1.10.3 dari https://mvnrepository.com/artifact/org.webjars.npm/bootstrap-icons

install jar bootstrap di lokal
```console
mvn install:install-file -Dfile=<path-to-jar> -DgroupId=<group-id> -DartifactId=<artifact-id> -Dversion=<version> -Dpackaging=jar
```
```console
mvn clean install
```

jika sudah update ke maven terbaru (jika menggunakan intellij, akan muncul notifikasi secara otomatis)
