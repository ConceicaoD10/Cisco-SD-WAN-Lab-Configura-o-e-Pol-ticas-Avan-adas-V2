# Cisco-SD-WAN-Lab-Configura-o-e-Pol-ticas-Avan-adas-V2



# 🛠️ Cisco SD-WAN Lab – Configuração e Políticas Avançadas

Este repositório documenta o progresso do meu laboratório prático com **Cisco SD-WAN**, incluindo topologia, prints de configurações reais, templates, políticas OMP e de controle, bem como soluções para cenários avançados envolvendo Traffic Engineering, Inbound/Outbound Control Policy, Service Chaining e VPN Membership.

## 🎯 Objetivo

Explorar de forma prática os principais recursos e desafios da solução Cisco SD-WAN, utilizando a plataforma vManage, vSmart e os edge routers, com foco em:

 Roteamento dinâmico com OSPF e propagação de rotas com OMP
 Implementação de políticas Active/Standby entre datacenters
 Manipulação de preferências de caminhos com Traffic Engineering (TE)
 Controle de propagação de rotas com políticas Inbound vs Outbound
Isolamento de VPNs para ambientes convidados
Encadeamento de serviços (Service Chaining) para segurança de tráfego

 📂 Conteúdo do Repositório

 `/prints/` – Capturas de tela com as configurações reais no vManage
 `/topologia/` – Imagens da topologia utilizada no laboratório
`/templates/` – Estrutura de configuração dos routers e controladores
`/policies/` – Exemplos e explicações das políticas aplicadas
`README.md` – Descrição completa do projeto

📌 Destaques Técnicos

 Utilização de políticas OMP para alterar a preferência de caminhos com base em prefixos específicos
 Redistribuição de prefixos entre sites para garantir redundância total de acesso
Organização das regras de política com base em ordem sequencial, condições de match e ações
 Aplicação prática da segmentação de VPNs para ambientes de convidados
 Planeamento de Service Chaining com Firewalls

 🔗 Publicação e Discussão

Este laboratório também foi divulgado e comentado na minha [publicação no LinkedIn](https://www.linkedin.com/in/danilo-conceição), onde partilho insights sobre a experiência de implementar estas políticas num ambiente prático de simulação.



> 💬 Para dúvidas, colaborações ou troca de experiências, sinta-se à vontade para abrir um issue ou entrar em contato.


Danilo Conceição

🌐 [LinkedIn](https://www.linkedin.com/in/danilo-conceição

