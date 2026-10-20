# 💡 Backlog de Ideias - Próxima Versão do Laboratório

> **Pausa temporária iniciada em:** 15/out/2026  
> **Motivo:** Foco em estudos com prazo determinado (Bootcamp Santander e curso do CCNA).  
> *Nota: Ideias registradas aqui serão avaliadas e executadas na retomada do projeto.*

## 📌 Ideias pendentes por categoria:

### 🔒 Segurança e Hardening (Conexão com o Bootcamp/Cibersegurança)
- [ ] Implementar regras de firewall mais restritivas.

### 🌐 Redes e Infra (Conexão com o CCNA)

> Inicialmente, o projeto V2 utilizará apenas a rede local, sem conexão com a internet.

Rede local implementada através de interfaces lógicas e SSIDs separados no OpenWrt:

- [X] Plano de endereçamento: bloco 172.16.1.0/24 (planejamento inicial das sub-redes realizado no dia 18/10/2026)

Sub-redes:    
Gestão    	    172.16.1.0/26    
Empresa         172.16.1.64/26    
Visitante 	    172.16.1.128/26    
Reserva 	      172.16.1.192/26    

- [ ] Revisar a segmentação de VLANs.
- [ ] Testar melhorias no roteamento ou topologia.

###  Desenho da Topologia Planejada V2
- [X] Desenho inicial da topologia V2 com base no plano de endereçamento: 172.16.1.0/24 (Desenhado realizado no dia 18/10/2026)

### ⚙️ Automação e Ferramentas
- [ ] Automatizar o deploy de alguma rotina do laboratório.

## Para testar quando retomar
- Viabilidade da VPN (verificar CGNAT / duplo NAT)
- Regras de firewall do AD entre VLANs
- DHCP: no Windows (com relay) ou no OpenWrt

## 📂 Documentação
- Criação da Estrutura (docs, Topologia, Readme, Incidentes) Inicial do Projeto V2 (Status: Em construção desde 18/10/2026)    
- Criação do repositório Aprendizado para registrar os conceitos que serão estudados no Projeto V2 (Status: Em construção desde 18/10/2026)    
- Documentar a criação das VLANs: método LuCI e método CLI/UCI

## Dúvidas em aberto
- ...
