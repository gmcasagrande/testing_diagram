# <p align="center">Centro Universitário Senac</p>


## <p align="center">Curso de Tecnologia em Análise e Desenvolvimento de Sistemas</p>

### <p align="center">PROJETO INTEGRADOR: DESENVOLVIMENTO DE SISTEMAS ORIENTADO A OBJETOS</p>

---

Este trabalho consiste no processo de modelagem de um sistema Orientado a Objetos, voltado a gestão de dados de uma grande universidade.

---
## <p align="center">Diagrama de caso de uso</p>

<p align="center">
  <img src="dcs/DiagramaCasoDeUso.svg" alt="Diagrama de Caso de Uso" width="600"/>
</p>

## <p align="center">Diagrama de classe</p>

```mermaid
classDiagram
    class PessoaFisica {
        -String cpf
        -String nome
        -String email
        -String telefone
        -Date dataNascimento
        -Int matricula
        +cadastrar() void
        +alterarDados() void
    }

    class Aluno {
        -String dataInicioCurso
        -String curso
        +cadastrarAluno() void
    }

    class Professor {
        -String formacao
        -String disciplina
        +cadastrarProfessor() void
    }

    class PessoaJuridica {
        -String cnpj
        -String razaoSocial
        -String email
        -String telefone
        -Date dataContrato
        +cadastrar() void
        +alterarDados() void
    }

    class Fornecedor {
        -String produto
        +solicitarProduto() void
    }

    Aluno --|> PessoaFisica
    Professor --|> PessoaFisica
    Fornecedor --|> PessoaJuridica
class PessoaFisica
  direction RL
```

---
## 👥 Colaboradores
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Pamelacimirro">
        <img src="https://avatars.githubusercontent.com/u/180059830?v=4?s=100" width="100px;" alt=""/>
        <br />
        <span style="font-size:16px;"><b>Pâmela</b></span>
      </a>
      <br />
    </td>
      <td align="center">
      <a href="https://github.com/aironvalentim">
        <img src="https://avatars.githubusercontent.com/u/146296538?v=4?s=100" width="100px;" alt=""/>
        <br />
        <span style="font-size:16px;"><b>Airon</b></span>
      </a>
      <br />
    </td>    <td align="center">
      <a href="https://github.com/AlexandreGarciaJr">
        <img src="https://avatars.githubusercontent.com/u/179349433?v=4?s=100" width="100px;" alt=""/>
        <br />
        <span style="font-size:16px;"><b>Alexandre</b></span>
      </a>
      <br />
      </td>    <td align="center">
      <a href="https://github.com/usuario2">
        <img src="https://avatars.githubusercontent.com/u/4430740?v=4?s=100" width="100px;" alt=""/>
        <br />
        <span style="font-size:16px;"><b>Anderson</b></span>
      </a>
      <br />
    </td>    <td align="center">
      <a href="https://github.com/gmcasagrande">
        <img src="https://avatars.githubusercontent.com/u/180349085?v=4?s=100" width="100px;" alt=""/>
        <br />
        <span style="font-size:16px;"><b>Guilherme</b></span>
      </a>
      <br />
    </td>    <td align="center">
      <a href="https://github.com/usuario1">
        <img src="https://avatars.githubusercontent.com/u/6946727?v=4?s=100" width="100px;" alt=""/>
        <br />
        <span style="font-size:16px;"><b>Gustavo</b></span>
      </a>
      <br />
    </td>    <td align="center">
      <a href="https://github.com/Maycon-on">
        <img src="https://avatars.githubusercontent.com/u/182829460?v=4?s=100" width="100px;" alt=""/>
        <br />
        <span style="font-size:16px;"><b>Maycon</b></span>
      </a>
      <br />
    </td>
  </tr>
  <tr>
</table>
