# trabalho-engenharia-software-2026
Trabalho de clínica veterinária do Técnico em Informática, segundo semestre de 2026.

##Diagrama UML

```mermaid
flowchart TD
    %%Atores

    Cliente["Cliente🧔‍♂️​"]
    Garçom["Garçom​🧑‍💼"]

    %% ações
    Pedir["Pedir Comida🥖​"]
    Vinho["Pedir Vinho🍷​"]



    %%relacionamnetis
    Cliente --"Faz Pedido"---Comida
    Garçom --"Recebe Pedido" ---Comida

    Vinho-. "estende".->Comida



````
