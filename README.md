# 🌉 Ponte Móvel — Dashboard de Centro de Operações

Dashboard em tempo real para monitorização do estado da Ponte Móvel do Porto de Lisboa (APDL).

## Funcionalidades
- ✅ Semáforo em tempo real (verde / laranja / vermelho)
- ✅ Polling automático a cada 60 segundos
- ✅ Histórico de alterações de estado
- ✅ Exportação para CSV
- ✅ Totalmente offline-first (localStorage)
- ✅ Responsive e adaptado a mobile
- ✅ Zero dependências externas (excepto Google Fonts)

## Como correr localmente
```bash
# 1. Clone o repositório
git clone https://github.com/SEU_USER/ponte-movel.git
cd ponte-movel

# 2. Abrir com VS Code Live Server
# Install extensão "Live Server" no VS Code
# Clique direito em index.html → "Open with Live Server"

# OU com Python (sem instalar nada)
python3 -m http.server 8080
# Abrir http://localhost:8080