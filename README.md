# CriandoVMAzure

Este repositório mostra os passos feitos para a criação de uma máquina virtual (VM) de teste no Azure, seguindo a trilha da DIO e a documentação da Microsoft.

## Etapas Realizadas

**Grupo de Recursos:** `VMTeste_group`  
Usado para organizar os recursos da VM.

**Máquina Virtual:** `VMTeste`  
- Região: East US  
- Zona: 1  
- Imagem: Windows Server 2022  
- Segurança: Trusted launch

**Tamanho:** Standard_B1s (1 vCPU, 1 GB RAM)  
Ideal para testes e elegível no plano gratuito.

**Administrador:**  
Usuário: `iorg`  
Senha: criada no momento da configuração

**Acesso RDP:**  
Porta 3389 liberada para conexão remota (restringir IPs depois dos testes).

