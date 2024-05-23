# # Projeto de Programação Orientada a Objetos

## OBJETIVO
O objetivo deste trabalho é abordar a prática da programação orientada a objetos envolvendo os conceitos de
classe, objeto, associações de classes, encapsulamento, herança e polimorfismo.
Deve-se, portanto, criar um programa orientado a objetos, na linguagem Java, que apresente uma solução
para o problema especificado a seguir.

## DESCRIÇÃO DO PROBLEMA
Em uma clínica trabalham médicos e existem pacientes internados.
Cada médico é identificado pelo seu CRM, possui um CPF, um nome, um telefone e recebe um salário na
clínica. Um médico tem formação em diversas especialidades (ortopedia, traumatologia, infectologia, etc).
A clínica precisa ter conhecimento de todas as especialidades que um médico possui. Porém, o médico
exerce apenas uma especialidade na clínica.

Para todo paciente internado na clínica são cadastrados os seguintes dados pessoais: nome, RG, CPF,
endereço, telefone e data de nascimento.
Um paciente tem sempre um determinado médico como responsável.
Pacientes estão sempre internados em quartos individuais, que são identificados por um número e pelo andar
da clínica em que estão localizados.

Diariamente, um médico passa nos quartos para visitar os pacientes, e registra as observações realizadas
sobre o estado do paciente.
Essas observações são cadastradas no sistema para futuras consultas ao histórico médico do paciente.
Esse histórico deve registrar a data, o horário, a observação realizada e o nome do médico que a registrou.

## TAREFA
Desenvolver um programa orientado a objetos que atenda as especificações descritas acima.
- O programa deve especificar as classes, atributos e métodos necessários para a solução do problema.
- O programa deve ter, no mínimo, cinco classes, além da classe que contém o programa principal.
- O programa deve, obrigatoriamente, aplicar os conceitos de encapsulamento, herança e polimorfismo
  de inclusão.
- Deve ser desenvolvido um programa principal que demonstre o funcionamento do programa (por
  exemplo: cadastrar um paciente, associar um paciente a um quarto, inserir as anotações sobre o
  paciente em seu histórico, etc.)

## ESTRUTURA DO PROJETO
- `Medico.java`: Classe que representa os médicos da clínica.
- `Paciente.java`: Classe que representa os pacientes internados na clínica.
- `Quarto.java`: Classe que representa os quartos onde os pacientes estão internados.
- `HistoricoMedico.java`: Classe que representa o histórico de observações de um paciente.
- `Observacao.java`: Classe que representa uma observação registrada durante a visita de um médico.
- `Especialidade.java`: Classe que representa as especialidades médicas.
- `ClinicaMain.java`: Classe principal que demonstra o funcionamento do programa.

## Contribuições 

