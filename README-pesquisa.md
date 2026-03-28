# Pesquisa de Mercado — Frete Parnaíba

Formulário de pesquisa de campo para coleta de dados sobre o mercado de frete em Parnaíba — PI.

Dois públicos: **motoristas** e **clientes** (quem contrata frete).

---

## Como usar

### 1. Configurar o Formspree (receber respostas por email)

1. Acessa [formspree.io](https://formspree.io) e cria uma conta gratuita
2. Cria dois formulários:
   - `Pesquisa Motoristas`
   - `Pesquisa Clientes`
3. Cada formulário gera um ID (ex: `xknkpqrz`)
4. Abre o arquivo `index.html` e substitui:
   - `SEU_ID_MOTORISTA` → ID do form de motoristas
   - `SEU_ID_CLIENTE` → ID do form de clientes
5. Salva o arquivo e faz commit no GitHub

### 2. Ativar o GitHub Pages

1. No repositório: **Settings → Pages**
2. Em **Branch**: seleciona `main` → pasta `/root`
3. Clica **Save**
4. Aguarda ~1 minuto
5. Link disponível em: `https://seuusuario.github.io/muvv-pesquisa`

### 3. Compartilhar

Manda o link direto no WhatsApp para motoristas e clientes.

---

## O que é coletado

### Motoristas
- Nome e WhatsApp
- Tipo de veículo e capacidade
- Fretes por dia (dentro e fora de Parnaíba)
- Tabela de valores por rota:
  - Mínimo dentro de Parnaíba
  - Parnaíba → Buriti dos Lopes
  - Parnaíba → Camocim
  - Parnaíba → Piripiri
  - Parnaíba → Teresina
  - Parnaíba → Picos
  - Parnaíba → São Luís
  - Parnaíba → Fortaleza
- Forma de pagamento atual
- Maiores dores no trabalho
- Comissão aceitável por frete

### Clientes
- Nome e WhatsApp
- Perfil (pessoa física, comércio, construtora...)
- Frequência de uso
- Tipo de veículo contratado
- Valor médio pago hoje
- Como encontra motoristas atualmente
- Maiores problemas
- Interesse em usar um app

---

## Ver as respostas

Todas as respostas chegam no **email cadastrado no Formspree** e ficam salvas no dashboard em [formspree.io](https://formspree.io).

Para exportar: **Dashboard → seu formulário → Export CSV** → abre no Excel.

---

## Estrutura do repositório

```
index.html   → formulário completo (motoristas + clientes)
README.md    → este arquivo
```
