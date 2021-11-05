# Repo Maven Public
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

### Adicione o repositório ao seu pom.xml

```sh
<repositories>
    <repository>
        <id>central</id>
        <url>https://mvn.pedrodavi.com.br/</url>
    </repository>
</repositories>
```

### Dependências disponíveis

### ValidateXmlByXsd
```sh
<dependency>
    <groupId>ValidateXmlByXsd</groupId>
    <artifactId>ValidateXmlByXsd</artifactId>
    <version>1.0.0</version>
</dependency>
```
### Uso
```sh
File xml = new File("arquivo.xml");
File xsd = new File("arquivo.xsd");
ValidateXmlByXsd.validate(xml, xsd);
```
