# orthoSync

> Tradução Preservativa e Refinamento Textual

## O que é?

O **orthoSync** é uma ferramenta de tradução que não apenas converte textos de um idioma para outro, mas também **preserva o estilo, a voz e o tom do autor original**. 

Diferente de tradutores comuns que "aplainam" o texto, o orthoSync mantém gírias, dialetos, jargões regionais e a época em que o texto foi escrito — como se o próprio autor tivesse escrito na língua de destino.

## Problema que resolve

Tradutores automáticos tradicionais (Google Translate, DeepL) perdem a essência do texto:
- Gírias viram linguagem formal
- Dialetos regionais desaparecem
- O tom pessoal do autor some
- Referências culturais são ignoradas

O orthoSync resolve isso com uma abordagem **preservativa**: traduz o conteúdo, mas mantém a alma do texto.

## Funcionalidades (MVP)

- [x] Upload de arquivos (.txt, .docx, .pdf)
- [x] Detecção automática de idioma
- [x] Tradução com ajuste fino de estilo
- [x] Preservação de gírias e época do autor
- [x] Mapeamento de dialetos e jargões regionais (Experimental)
- [x] Modo convidado com limites diários/mensais
- [x] Planos de assinatura para uso ilimitado

## Tecnologias

- HTML5, CSS3, JavaScript (Frontend)
- Interface responsiva e minimalista
- Simulação de motor de IA para processamento textual

## Como usar

### Modo Convidado (Gratuito / Limitado)

1. Acesse a aplicação no navegador
2. Clique em **[ Modo Convidado (Uso Local / Limitado) ]**
3. Arraste ou selecione um arquivo de texto
4. Configure as opções de tradução
5. Clique em **[ INICIAR TRADUÇÃO ORTHOSYNC ]**

> **Limites do modo convidado:** 6 arquivos/dia | 200 arquivos/mês

### Modo Completo (Assinatura)

| Plano | Preço | Volume | Recursos |
|-------|-------|--------|----------|
| **Mensal** | R$ 29,90/mês | Até 200 docs/mês | Acesso total à IA + Filtro de Dialetos profundo |
| **Anual** | R$ 239,90/ano | Até 200 docs/mês | Economia de 33% + Atualizações prioritárias |

## Instalação (Desenvolvimento Local)

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/orthosync.git

# Acesse a pasta
cd orthosync

# Abra o arquivo no navegador
open orthosyncv2.html
