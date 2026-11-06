<a href="https://gvpoliveira.github.io">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
    <img alt="Gabriel Vinicius, desenvolvedor backend Java em formação, aberto a estágio" src="./assets/header-light.svg" width="100%">
  </picture>
</a>

<p>
  <a href="https://gvpoliveira.github.io"><img alt="Portfólio" src="https://img.shields.io/badge/Portfólio-gvpoliveira.github.io-F2B33D?style=for-the-badge&labelColor=13202B"></a>
  <a href="https://gvpoliveira.github.io/curriculo-gabriel-oliveira.pdf"><img alt="Currículo em PDF" src="https://img.shields.io/badge/Currículo-PDF-F2B33D?style=for-the-badge&labelColor=13202B"></a>
  <a href="https://www.linkedin.com/in/gvpoliveira"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-gvpoliveira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=13202B"></a>
  <a href="mailto:gabriel.vpoliveira@hotmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-gabriel.vpoliveira@hotmail.com-56687A?style=for-the-badge&labelColor=13202B"></a>
</p>

### Sobre mim

```java
public class GabrielVinicius {

    private final String formacao = "Análise e Desenvolvimento de Sistemas · SENAC SP (2025–2028)";
    private final String objetivo = "Estágio em desenvolvimento backend com Java";
    private final String local    = "São Paulo – SP";

    private final List<String> stack = List.of(
        "Java", "Spring Boot", "Spring Data JPA", "MySQL", "JUnit 5", "MockMvc"
    );

    public String historia() {
        return "Trabalho no almoxarifado e transformo essa rotina em sistema: "
             + "o mesmo projeto reconstruído em POO, JDBC e Spring Boot.";
    }
}
```

### Stack

<p>
  <img alt="Java, Spring, Hibernate, MySQL, Maven, Git, GitHub, IntelliJ, HTML, CSS e JavaScript" src="https://skillicons.dev/icons?i=java,spring,hibernate,mysql,maven,git,github,idea,html,css,js&perline=11">
</p>

### Projetos

<table>
  <tr>
    <td width="50%">
      <a href="https://github.com/GvPOliveira/almoxarifado-v3">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./assets/card-almoxarifado-v3-dark.svg">
          <img alt="Almoxarifado v3 com Spring Boot: API REST com Spring Data JPA, 38 testes com JUnit 5 e MockMvc" src="./assets/card-almoxarifado-v3-light.svg" width="100%">
        </picture>
      </a>
    </td>
    <td width="50%">
      <a href="https://github.com/GvPOliveira/almoxarifado-system">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./assets/card-almoxarifado-v1-v2-dark.svg">
          <img alt="Almoxarifado v1 e v2 com POO e JDBC: 68 testes na v1 e transações na v2" src="./assets/card-almoxarifado-v1-v2-light.svg" width="100%">
        </picture>
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <a href="https://github.com/GvPOliveira/gerenciador-de-jogadores">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./assets/card-gerenciador-dark.svg">
          <img alt="Gerenciador de Jogadores: CRUD com Spring Boot, JPA, H2 e front-end em JavaScript" src="./assets/card-gerenciador-light.svg" width="100%">
        </picture>
      </a>
    </td>
    <td width="50%">
      <a href="https://gvpoliveira.github.io/#jogo">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./assets/card-portfolio-dark.svg">
          <img alt="Portfólio com retrato em pixel art e minijogo de almoxarifado" src="./assets/card-portfolio-light.svg" width="100%">
        </picture>
      </a>
    </td>
  </tr>
</table>

<details>
<summary><b>Por que reconstruir o mesmo sistema três vezes?</b></summary>
<br>

Escolhi um domínio que conheço por dentro, o do meu trabalho no almoxarifado, e refiz o sistema a cada nova etapa de estudo. Assim, cada versão mostra na prática o que a tecnologia nova resolve.

```
v1 · POO  ─────▶  v2 · JDBC  ─────▶  v3 · Spring Boot
Java puro         MySQL + SQL         JPA + API REST
68 testes         transações          38 testes · em andamento
```

| Versão | O que aprendi |
| :-- | :-- |
| **v1 · POO** | Modelar regras de negócio com classes, Collections e exceções próprias, e garantir o comportamento com testes unitários |
| **v2 · JDBC** | Escrever SQL à mão, montar objetos a partir do `ResultSet` e controlar transações com commit e rollback |
| **v3 · Spring Boot** | Comparar todo esse trabalho manual com Spring Data JPA, expor uma API REST com DTOs e testar os endpoints com MockMvc |

</details>

<details>
<summary><b>O que estou estudando agora</b></summary>
<br>

- [ ] Regras de negócio da v3 com Spring: notas fiscais, requisições e estornos
- [ ] Testes automatizados no Spring
- [ ] Boas práticas de APIs REST

</details>

---

<sub>Sempre aberto a feedback sobre os meus projetos. Se quiser conversar, me chame no LinkedIn.</sub>
