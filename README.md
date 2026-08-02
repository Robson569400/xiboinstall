# 🖥️ Instalador Automático do Xibo CMS com Docker + SSL

Este script automatiza a instalação completa do [Xibo CMS](https://xibosignage.com/) com Docker, Apache, proxy reverso, certificado SSL via Certbot e renovação automática. Também é possivel instalar sem proxy reverso ou SSL.

Aceita a instalação de diversos cms Xibo no mesmo servidor.

## 📦 Requisitos

- Servidor Ubuntu 20.04 ou superior
- Acesso root ou sudo
- Um domínio válido (ex: `painel.suaempresa.com.br`)

---

## 🚀 Instalação

Clone o repositório e execute o script:

```bash
git clone https://github.com/Robson569400/xiboinstall
cd xibodockerinstall
chmod +x xibo.sh
sudo ./xibo.sh
