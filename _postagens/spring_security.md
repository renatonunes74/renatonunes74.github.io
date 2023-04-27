---
title: spring security
layout: post
---
# etapas
- Adicione as Dependências no arquivo pom.xml
    - spring security
    - jjwt api
    - jjwt impl
    - jjwt jackson
- criea a classe Usuario na Camada Model
    - crie o relacionamento da classe Usuario com a classe Postagem
    - crie o relacionamento da classe Postagem com a classe Usuario
- crie a classe UsuarioLogin na camada Model
- crie a classe UsuarioRepository na camada Repository
    - crie o metodo findByUsuario(String Usuario)
- crie o pacote com.generation.security
    - crie a classe UserDetailsImpl na camada security
    - crie a classe UserDetailsServiceImpl na camada security
    - crie a classe JwtService na camada security
    - crie a classe JwtAuthFilter na camada security
    - crie a classe BasicSecurityConfig na camada security
- crie o pacote com.generation.service
    - crie a classe UsuarioService na camada service
- crie a classe UsuarioController na camada controller
- execute os testes http
    - testes no recurso Usuario
    - atualizar os testes post e put postagem
    - inserir token em todos os testes

# referencias
- [Documentação Spring Security](https://spring.io/projects/spring-security)
- [Dependência JJWT](https://github.com/jwtk/jjwt)
- [Dependência JJWT-API Maven](https://mvnrepository.com/artifact/io.jsonwebtoken/jjwt-api/0.11.5)
- [Dependência JJWT-IMPL Maven](https://mvnrepository.com/artifact/io.jsonwebtoken/jjwt-impl/0.11.5)
- [Dependência JJWT-JACKSON Maven](https://mvnrepository.com/artifact/io.jsonwebtoken/jjwt-jackson/0.11.5)
