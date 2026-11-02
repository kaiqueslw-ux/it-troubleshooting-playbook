# it-troubleshooting-playbook

# 🛠️ IT Troubleshooting Playbook

Guia prático de documentação de incidentes, diagnósticos e resoluções de N1/N2 em infraestrutura, sistemas operacionais e hardware.

## 📂 Categorias de Casos
- [Sistemas Operacionais & Particionamento](#sistemas-operacionais--particionamento)
- [Diagnóstico de Hardware](#diagnóstico-de-hardware)
- [Suporte a Usuários & Redes](#suporte-a-usuários--redes)

---

## 📌 Casos Documentados

### 1. Recuperação e Reestruturação de Partições em Linux Mint
* **Sintoma:** Falha crítica de boot após corrupção de tabela de partições ou instabilidade no sistema de arquivos.
* **Diagnóstico:** Utilização de ferramentas de ambiente live-USB para análise de pontos de montagem (`fdisk`, `lsblk`) e verificação de integridade dos discos.
* **Resolução:** Reconfiguração da tabela de partições, realocação segura de dados e reinstalação limpa do gerenciador de boot (GRUB) sem perda de arquivos de usuário.

### 2. Diagnóstico de Bancada e Teste de Componentes
* **Sintoma:** Sistema sem sinal de vídeo ou falhas intermitentes de inicialização.
* **Diagnóstico:** Isolamento de componentes em placa-mãe (testes cruzados de memória RAM, verificação de pinagem de CPU e integridade de conexões de energia da fonte).
* **Resolução:** Substituição/respiros de conectores oxidados e testes de estresse para validação de estabilidade térmica e elétrica.
