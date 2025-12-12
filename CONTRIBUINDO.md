# 📋 Guia de Contribuição

## Como Adicionar uma Nova Certificação

Este documento orienta como adicionar novas certificações ao repositório.

---

## Passos para Adicionar uma Certificação

### 1. **Edite o arquivo README.md**

- Navegue até o arquivo `README.md`
- Localize a seção apropriada (DIO, Google Cloud, AWS, etc.)
- Se a plataforma não existir, crie uma nova seção

### 2. **Siga o Template Padrão**

Use este template para manter consistência:

```markdown
#### ✅ Nome da Certificação

**Status**: [Concluído/Em Andamento/Não Iniciado]  
**Data**: [Mês Ano]  
**Carga Horária**: [X horas]  
**Nível**: [Básico/Intermediário/Avançado]  
**Link**: [URL do Certificado](https://link.com)  
**Temas Cobertos**:
- Tema 1
- Tema 2
- Tema 3
```

### 3. **Atualize as Estatísticas**

Na seção "Estatísticas", atualize:
- **Total de Certificações**: Incremente o número
- **Plataformas**: Adicione a nova plataforma se necessário
- **Óltima Atualização**: Atualize para a data atual

### 4. **Atualize os Próximos Passos (Opcional)**

Se uma certificação planejada foi concluída, marque-a como completa:
- [ ] Item concluído → se tornar (X) Item concluído

### 5. **Faça o Commit**

Exemplo de mensagem de commit:

```
feat: adicionar certificação [Nome da Certificação]

- Plataforma: [Nome da plataforma]
- Nível: [Básico/Intermediário/Avançado]
- Data: [Mês Ano]
```

---

## Estrutura do Repositório

```
certificacoes/
├─ README.md                 # Página principal (EDITE AQUI!)
├─ CONTRIBUINDO.md            # Este arquivo
├─ LICENSE                    # Licença do repositório
└─ certificates/              # (Futuro) Pasta para armazenar certificados
    ├─ 2025/
    └─ README.md
```

---

## Tipos de Status

| Status | Emoji | Descrição |
|--------|-------|-------------|
| Concluído | ✅ | Certificação já obtida |
| Em Andamento | 📑 | Certificação em progresso |
| Não Iniciado | ❌ | Planejado para o futuro |

---

## Níveis de Dificuldade

- **Básico**: Foco em conceitos fundamentais
- **Intermediário**: Conhecimento avançado de conceitos
- **Avançado**: Especialização profunda e prática avançada

---

## Exemplo Completo

#### ✅ Formação Python Intermediário

**Status**: Concluído  
**Data**: Novembro 2025  
**Carga Horária**: 20 horas  
**Nível**: Intermediário  
**Link**: [Ver Certificação](https://exemplo.com/certificado)  
**Temas Cobertos**:
- Orientação a Objetos
- Tratamento de Exceções
- Trabalho com Bibliotecas

---

## Perguntas Frequentes

**P: Posso adicionar certificações de outras plataformas?**  
R: Sim! Siga o padrão e crie uma nova seção com o nome da plataforma.

**P: Como formatar o link do certificado?**  
R: Use `[Texto](URL)` - exemplo: `[Ver Certificação](https://link.com)`

**P: Preciso adicionar uma imagem do certificado?**  
R: Não é obrigatório, mas links são muito úteis!

---

**Obrigado por contribuir ao seu desenvolvimento profissional! 🚀**
