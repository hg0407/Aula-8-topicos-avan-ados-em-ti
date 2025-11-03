# Secure Pipeline CI/CD - HTML/CSS Project

## 🛡️ Pipeline de Segurança DevSecOps

Este projeto implementa uma pipeline completa de CI/CD com foco em segurança, incluindo:

### 🔍 Análises de Segurança Implementadas:

- **SAST** (Static Application Security Testing)
- **DAST** (Dynamic Application Security Testing)  
- **SCA** (Software Composition Analysis)
- **IaC Scan** (Infrastructure as Code Security)
- **Secrets Detection**
- **Vulnerability Management**

### 🚀 Fluxo da Pipeline:

1. **Git App Code** → Checkout do código
2. **Secrets Scan** → Detecção de credenciais
3. **SAST** → Análise estática de segurança
4. **SCA** → Análise de dependências
5. **IaC Scan** → Validação de infraestrutura
6. **DAST** → Testes dinâmicos de segurança
7. **Deploy** → Deploy seguro
8. **Vulnerability Management** → Gestão de vulnerabilidades

### 📊 Ferramentas Utilizadas:

- GitLeaks & Semgrep (Secrets & SAST)
- Trivy (IaC & Vulnerability Scanning)
- OWASP ZAP (DAST)
- DefectDojo (Vulnerability Management)

Para mais detalhes, consulte o arquivo [SECURITY-PIPELINE.md](SECURITY-PIPELINE.md)