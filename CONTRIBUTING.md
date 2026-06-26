---

## CONTRIBUTING.md

```markdown
# CONTRIBUTING.md — Como Contribuir com o orthoSync

Obrigado pelo seu interesse em ajudar o **orthoSync** a crescer! Este documento explica como você pode contribuir de forma organizada e respeitosa.

---

## 1. Antes de começar

- Leia o [README.md](README.md) para entender o que o projeto faz
- Verifique se a sua ideia já não foi sugerida em uma [Issue](https://github.com/seu-usuario/orthosync/issues)
- Se for sua primeira contribuição, comece com algo simples (correção de texto, ajuste de CSS, etc.)

---

## 2. Como reportar um problema (Bug)

Se você encontrou algo errado, abra uma **Issue** com estas informações:

1. **Título claro**: ex: "Botão de tradução não responde no Safari"
2. **Descrição do problema**: o que aconteceu?
3. **Passos para reproduzir**: liste o que você fez, passo a passo
4. **Comportamento esperado**: o que deveria acontecer?
5. **Screenshots**: se possível, anexe imagens
6. **Navegador/Sistema**: ex: "Chrome 120 no Windows 11"

> Dica: Verifique se o bug já foi reportado antes de abrir uma nova Issue.

---

## 3. Como sugerir uma nova funcionalidade

1. Abra uma **Issue** com o rótulo `enhancement`
2. Explique **por que** essa funcionalidade é útil
3. Descreva **como** você imagina que ela funcionaria
4. Se possível, faça um desenho ou mockup simples

---

## 4. Como enviar código (Pull Request)

### Passo a passo:

```bash
# 1. Faça um fork do repositório (botão "Fork" no GitHub)

# 2. Clone o seu fork
git clone https://github.com/seu-usuario/orthosync.git

# 3. Crie uma branch para a sua alteração
git checkout -b minha-nova-funcionalidade

# 4. Faça as suas mudanças no código

# 5. Teste no navegador antes de enviar
#    - Abra o orthosyncv2.html
#    - Verifique se não quebrou nada

# 6. Commit com uma mensagem clara
git add .
git commit -m "feat: adiciona suporte a arquivos .epub"

# 7. Envie para o seu fork
git push origin minha-nova-funcionalidade

# 8. Abra um Pull Request no GitHub original
