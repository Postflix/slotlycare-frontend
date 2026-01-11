# 🚀 GUIA DE DEPLOY - SLOTLYMED FRONTEND

## 📋 O QUE VOCÊ VAI FAZER:

Subir 4 arquivos no Vercel para o SlotlyMed funcionar 100%

**Tempo:** 10 minutos  
**Custo:** $0

---

## 📁 ARQUIVOS NECESSÁRIOS:

Você vai baixar estes 4 arquivos:

1. ✅ `index.html` - Página inicial
2. ✅ `painel.html` - Painel do médico
3. ✅ `paciente.html` - Página de agendamento
4. ✅ `vercel.json` - Configuração de rotas

---

## 🔧 PASSO A PASSO:

### **PASSO 1: Baixar os arquivos**
Claude vai te dar os 4 arquivos. Salve todos numa pasta no seu computador.

### **PASSO 2: Criar novo projeto no Vercel**

1. Acesse: https://vercel.com
2. Faça login (mesma conta do backend)
3. Clique em **"Add New..."** → **"Project"**
4. Clique em **"Browse"** ou arraste a pasta com os 4 arquivos
5. Nome do projeto: `slotlymed-frontend`
6. Clique em **"Deploy"**

### **PASSO 3: Aguardar deploy**
- Vercel vai processar (~1 minuto)
- Quando terminar, você verá: ✅ **"Congratulations!"**

### **PASSO 4: Testar URLs**

Vercel vai te dar uma URL tipo: `slotlymed-frontend.vercel.app`

**Teste estas URLs:**
- `slotlymed-frontend.vercel.app` → Página inicial ✅
- `slotlymed-frontend.vercel.app/painel` → Painel médico ✅
- `slotlymed-frontend.vercel.app/dr-teste` → Página paciente (vai dar erro, normal!) ✅

---

## 🎯 COMO FUNCIONA:

### **Fluxo completo:**

1. Médico acessa: `slotlymed-frontend.vercel.app/painel`
2. Preenche dados, gera horários
3. Recebe link: `slotlymed-frontend.vercel.app/dr-joao-silva`
4. Paciente acessa esse link
5. Sistema busca dados do backend
6. Paciente agenda! ✅

---

## 🔗 DEPOIS (QUANDO COMPRAR DOMÍNIO):

Quando você comprar `slotlymed.com`:

1. No Vercel: Settings → Domains → Add `slotlymed.com`
2. Copia DNS do Vercel
3. Adiciona no registrador
4. Pronto! URLs ficam:
   - `slotlymed.com/painel`
   - `slotlymed.com/dr-joao-silva`

---

## ❓ PROBLEMAS COMUNS:

**Problema:** "Page not found" ao acessar `/dr-joao`  
**Solução:** Normal! Só vai funcionar quando o médico criar esse ID no painel

**Problema:** Painel não salva  
**Solução:** Verificar se backend está rodando (slotlymed-backend.vercel.app/api/test)

**Problema:** Página paciente não carrega dados  
**Solução:** Verificar console do navegador (F12)

---

## ✅ CHECKLIST FINAL:

- ☐ 4 arquivos baixados
- ☐ Projeto criado no Vercel
- ☐ Deploy concluído
- ☐ URL funcionando
- ☐ Painel abre corretamente
- ☐ Testado criar um médico de exemplo

---

**PRONTO! Sistema 100% funcional!** 🎉
