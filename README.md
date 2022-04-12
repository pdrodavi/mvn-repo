# Repo Maven Public
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

### Contato: developer@pedrodavi.com.br
#### https://pedrodavi.com.br

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

### Docval - Validador de documentos
```sh
<dependency>
    <groupId>docval</groupId>
    <artifactId>docval</artifactId>
    <version>1.0.0</version>
</dependency>
```
### Uso
```sh
boolean cpf = Docval.checkCPF("796.850.250-02");
boolean cnpj = Docval.checkCNPJ("28.535.777/0001-70");
boolean ie = Docval.checkIE("44516185-0", "PB");
```

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

### Tratamento de imagem
```sh
<dependency>
    <groupId>tratimg</groupId>
    <artifactId>tratimg</artifactId>
    <version>1.0.0</version>
</dependency>
```
### Uso
```sh
// Instância
Tratimg tratimg = new Tratimg();

// Exemplo de métodos
tratimg.binarizacao();
tratimg.CalcMediana();
tratimg.brilho();
tratimg.contraste();
tratimg.tonsDeCinza();
tratimg.calculaHistograma();
tratimg.calculaHistogramaAcumulado();
tratimg.equalizacao();
tratimg.LeJanela3x3();
tratimg.negativo();
tratimg.paleta();
tratimg.passaAlta();
tratimg.suavizacao();
```
