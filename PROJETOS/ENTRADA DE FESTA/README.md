# 🎉 Sistema de Verificação de Entrada em Evento 
✔ Projeto desenvolvido em Python
Este projeto tem como objetivo simular um sistema simples de controle de entrada em uma festa, verificando a idade dos convidados e determinando se eles podem ou não participar do evento.
O algoritmo foi desenvolvido aplicando princípios de lógica de programação, condicionais, organização de código e boas práticas de desenvolvimento em Python.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🧠 Objetivo do Projeto
Criar um programa que:

Solicita a idade do convidado

Avalia as regras de entrada

Exibe a condição permitida para o usuário


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 📝 Regras de Acesso
Idade	Condição de Entrada

Menor que 16	❌ Entrada proibida

16 ou 17	⚠ Entrada permitida somente com responsável

18 anos ou mais	✔ Entrada liberada

----------------------------------------------
# 🛠 Tecnologias Utilizadas
Python 3

Estruturas condicionais (if, elif, else)

Boas práticas de desenvolvimento de algoritmos

Comentários e organização de código

------------------------------------------------------------------------------------

# 📌 Código do Projeto
Sistema de verificação de idade para entrada em eventos

idade = int(input("Informe sua idade: "))

if idade < 16:
    print("Entrada não permitida.")
elif 16 <= idade <= 17:
    print("Entrada permitida somente com responsável.")
else:
    print("Entrada permitida. Aproveite a festa!")

------------------------------------------------------------------------------

# 📂 Como Executar
Certifique-se de ter o Python 3 instalado.

Execute o arquivo Python:

python entrada_festa.py

----------------------------------------------------------------------------
# 🚀 Aprendizados
Durante o desenvolvimento deste algoritmo, foram reforçados conceitos fundamentais:

Raciocínio lógico

Estruturas condicionais

Entrada e saída de dados

Tratamento simples de regras de decisão

Escrita clara e manutenção do código

------------------------------------------------------------------
# 👨‍💻 Autor

Projeto desenvolvido para estudo da disciplina Técnicas de Desenvolvimento de Algoritmos.
