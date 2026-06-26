# 💪 Projeto Fitness: Aline Karoliny

Um aplicativo web moderno para treinos personalizados, cálculo de IMC e acompanhamento de metas fitness.

## 🎯 Funcionalidades

- **Calculadora de IMC** - Calcula IMC, TMB (Taxa Metabólica Basal), TDEE (Gasto Energético Diário) e meta calórica
- **Três Treinos Personalizados** - Rotinas de exercícios para inferiores e superiores
- **Vídeos Tutoriais** - Links para vídeos do YouTube de cada exercício
- **Interface Moderna** - Design responsivo com tema escuro e glassmorphismo
- **Modal de Vídeos** - Visualize os vídeos em um modal integrado

## 🚀 Como Usar

1. Abra o arquivo `index.html` no navegador
2. Preencha seus dados (altura, peso, idade, sexo, nível de atividade e objetivo)
3. Clique em "Calcular IMC" para ver seus resultados
4. Clique em "Ver treinos" para acessar os treinos personalizados
5. Clique nos links "Ver vídeo" para visualizar os exercícios

## 📐 Cálculos Realizados

### IMC (Índice de Massa Corporal)
```
IMC = Peso (kg) / (Altura (m))²
```

### TMB (Taxa Metabólica Basal)
**Feminino:**
```
TMB = 655 + (9.6 × Peso) + (1.8 × Altura em cm) - (4.7 × Idade)
```

**Masculino:**
```
TMB = 66 + (13.7 × Peso) + (5 × Altura em cm) - (6.8 × Idade)
```

### TDEE (Gasto Energético Diário Total)
```
TDEE = TMB × Fator de Atividade
```

### Meta Calórica
```
Meta = TDEE - Déficit (dependendo do objetivo)
```

## 🏋️ Treinos Inclusos

### Treino A – Inferiores
- Agachamento Smith – 4x12
- Avanço com Halteres – 3x10
- Cadeira Flexora – 3x12

### Treino B – Superiores
- Puxada na Frente – 4x10
- Remada Unilateral – 3x10
- Tríceps Corda – 3x12

### Treino C – Inferiores
- Agachamento Livre – 4x10
- Leg Press 45° – 4x12
- Panturrilha em Pé – 4x20

## 🎨 Design

- **Tema:** Escuro com acentos verde e azul
- **Responsivo:** Mobile-first, otimizado para todos os tamanhos de tela
- **Animações:** Transições suaves e efeitos de hover
- **Glassmorphismo:** Cards com efeito de vidro fosco

## 📦 Tecnologias

- HTML5
- CSS3 (com variables e media queries)
- JavaScript Vanilla

## 📝 Notas

- A funcionalidade de envio por e-mail é apenas uma simulação (UI-only)
- Os vídeos são incorporados do YouTube
- Todos os cálculos são realizados no lado do cliente

## 👤 Desenvolvido para

Aline Karoliny • Projeto Fitness © 2025

---

**Mantenha o foco. O progresso vem com consistência! 💪**