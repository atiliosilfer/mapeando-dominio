# mapeando-dominio

Atividade de fundamentos de DDD do curso de Node - rockeseat
[link da atividade](https://efficient-sloth-d85.notion.site/Atividade-Mapeando-o-dom-nio-38963358ffd74289b824ff73b187165d)https://efficient-sloth-d85.notion.site/Atividade-Mapeando-o-dom-nio-38963358ffd74289b824ff73b187165d

- Quais as entidades de domínio?
  - Produto
  - Hístorico de vendas
  - Estoque

- Quais as ações (casos de uso) que essa aplicação deve ter?
  - Deve ser possível rastrear cada produto individualmente
  - Deve ser possível vincular ao produto um id único, tamanho e cor
    
  - Deve ser possível definir um limite mínimo de um produto no estoque
  - Ao chegar nesse valor mínimo de estoque deve disparar um alerta no sistema de gerenciamento de estoque e por e-mail

  - Deve ser possível visualizar o histórico de vendas e estoque
  - Deve ser possível visualizar
    - quantos produtos foram vendidos em um determinado período
    - o lucro gerado por produto 
    - quais produtos estão vendendo melhor em cada produto
  - Deve ser possível observar as tendências de estoque ao longo do tempo

  - Deve ser possível criar e gerenciar ordens de compra automaticamente baseado nas quantidades mínimas de estoque e nas tendências de vendas
  - Deve haver uma integração do sistema com os fornecedores, recebendo atualizações automáticas sobre prazos de entregas de novas remessas
