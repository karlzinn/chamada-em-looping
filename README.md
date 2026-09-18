## Sobre o projeto

Programa em Java que calcula a situação escolar de múltiplos alunos com base na média de 3 notas.

### Funcionamento

- O usuário informa a quantidade de alunos a serem avaliados.
- Para cada aluno, são solicitadas 3 notas (aceitam casas decimais).
- É calculada a média aritmética das notas.
- A situação é definida conforme a média:
- **Média >= 7.0** → Aprovado
- **Média >= 5.0 e < 7.0** → Recuperação
- **Média < 5.0** → Reprovado
- O resultado (média e situação) é exibido para cada aluno.

### Tecnologias

- Java
- `Scanner` para entrada de dados via console

### Como executar

```bash
javac Main.java
java Main
```

### Exemplo de execução

```
Quantos alunos? 2

Aluno 1
n 1: 8
n 2: 7
n 3: 6
Aluno com media 7.0 está em situação de: Aprovado

Aluno 2
n 1: 4
n 2: 5
n 3: 3
Aluno com media 4.0 está em situação de: Reprovado
```
