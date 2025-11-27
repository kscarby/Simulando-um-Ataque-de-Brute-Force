# 🔐 Simulação Educacional de Ataques de Força Bruta com Kali Linux e Medusa

Este projeto demonstra, de forma **100% educacional e controlada**, como ataques de força bruta funcionam em serviços vulneráveis utilizando **Kali Linux**, **Medusa**, **Metasploitable 2** e **DVWA**.

⚠️ Realizado apenas em ambiente isolado (VirtualBox). Não utilize em sistemas reais.

## 🖥️ Ambiente Utilizado

- Kali Linux: máquina de auditoria
- Metasploitable 2 / DVWA: ambientes vulneráveis
- Rede: Host-Only (isolada)

## 🎯 Objetivos

- Entender ataques de força bruta em FTP, Web e SMB  
- Testar autenticação com Medusa em ambiente seguro  
- Criar wordlists simples  
- Documentar o processo e propor medidas de mitigação  

## 🚀 Passos Principais

### 1️⃣ Reconhecimento  
Identificação de portas e serviços vulneráveis na Metasploitable (FTP, SMB, HTTP, DVWA).

### 2️⃣ Wordlists  
Criação de pequenas listas de senhas fictícias para testes.

### 3️⃣ Simulações Educacionais  
- FTP: análise de autenticação fraca  
- DVWA: estudo de brute force em login web  
- SMB: entendimento do conceito de password spraying  

### 4️⃣ Registro de Evidências  
Capturas de tela armazenadas em `/images`.

## 🛡️ Mitigações Recomendadas

- Senhas fortes e únicas  
- Limite de tentativas e bloqueio automático  
- Autenticação multifator  
- Captchas em formulários  
- Monitoramento de logs e uso de fail2ban  

## ✔️ Conclusão

O projeto permitiu entender como funcionam ataques de força bruta e como preveni-los.  
Foi essencial para desenvolver consciência sobre segurança, auditoria e boas práticas.

