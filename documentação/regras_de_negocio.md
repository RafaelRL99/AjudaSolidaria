# Regras de Negócio – AjudaSolidária

1. **RB-01** – Um *item* sempre pertence a **um único doador** (FK `id_doador`).
2. **RB-02** – Um *item* pode ter apenas **um status por vez**:  
   `Disponível` · `Reservado` · `Entregue`.
3. **RB-03** – Apenas *beneficiários cadastrados* podem registrar solicitações.
4. **RB-04** – Uma *solicitação* possui status `Pendente` ou `Atendida`.
5. **RB-05** – Itens *Reservados* ou *Entregues* não podem ser editados pelo doador.
6. **RB-06** – Exclusão de usuário só é permitida se **não houver itens/solicitações** vinculados.
7. **RB-07** – Cada usuário se autentica com **e-mail único**.
8. **RB-08** – Todas as operações de escrita exigem **usuário logado**.
