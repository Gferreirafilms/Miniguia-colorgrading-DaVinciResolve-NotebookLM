# 📚 Miniguia de Estudos: Color Grading de Alta Performance com NotebookLM

## 🎯 1. Contexto e Objetivos
Este projeto faz parte do Bootcamp da DIO em parceria com o Bradesco. O objetivo de estudo escolhido foi o **Color Grading no DaVinci Resolve**, com um foco muito específico e moderno: o tratamento de imagens gravadas em formato **Apple Log no iPhone 15 Pro Max**. Meu propósito é aplicar os "Primeiros Princípios" para parar de corrigir cores "no olho" (o que destrói a imagem) e começar a usar as ferramentas matemáticas corretas para extrair uma estética de cinema.

## 🗂️ 2. Curadoria de Fontes
Para construir uma base sólida e não depender de "achismos", o NotebookLM foi alimentado com 15 fontes de alto nível, incluindo:
- Aulas e materiais do "CG Lab 2.0" e "Coloristas Profissionais" (Marcelo Sant'Anna).
- Guias práticos de Color Grading para iniciantes no DaVinci Resolve.
- Estudos sobre a Psicologia das Cores (ex: Análise do filme Pobres Criaturas).
- Masterclasses sobre técnicas para agilizar o fluxo de trabalho (Workflow).

## 🛠️ 3. Engenharia de Prompts e "Cicatrizes"
Para extrair o melhor conhecimento, fui direto ao ponto com a IA.

**O Prompt Estratégico:**
- "iphone 15 pro max" (Buscando o fluxo de trabalho exato para este equipamento dentro do vasto material enviado).

**Minhas Cicatrizes (Troubleshooting):**
A grande virada de chave do projeto foi entender o erro clássico dos videomakers. No início, a intuição manda pegar o vídeo "lavado" (sem cor) e ir adicionando contraste e saturação manualmente. A IA me mostrou que isso é um erro fatal que destrói as informações do arquivo. A solução foi aprender a aplicar uma transformação matemática antes de qualquer processo criativo.

## 📖 4. Miniguia de Estudo (O Resultado)

### 📝 Resumo Estruturado: O Segredo do Apple Log
Imagine que o vídeo gravado no iPhone 15 Pro Max em formato Apple Log é um texto escrito em um idioma alienígena. Se você tentar adivinhar o que está escrito (fazer a cor "no olho"), você vai errar. Você precisa de um tradutor oficial.

No DaVinci Resolve, esse tradutor se chama **Color Space Transform (CST)**. Antes de brincar com o visual, você aplica o CST com esta receita técnica exata:
1. **Input Color Space:** `Rec.2020` (O idioma de entrada).
2. **Input Gamma:** `Apple Log` (O formato nativo do iPhone).
3. **Output Gamma:** `Rec.709 Gamma 2.4` (O idioma de saída, que é o padrão da internet e das telas).

Apenas com essa tradução matemática, o vídeo "lavado" ganha vida de forma perfeita. Só depois disso é seguro aplicar os 4 pilares criativos: Exposição, Balanço, Saturação e Look.

### 📚 Glossário Simplificado
- **Apple Log:** Um formato de gravação de vídeo do iPhone que deixa a imagem cinza ("lavada"). Ele faz isso de propósito para capturar o máximo de detalhes possível de luz e sombra, guardando essas informações para a edição.
- **CST (Color Space Transform):** A ferramenta matemática do DaVinci Resolve que funciona como um tradutor universal, convertendo perfeitamente as cores da câmera para o padrão das nossas telas.
- **Rec.709:** É a "caixa de lápis de cor" padrão da televisão e da internet. É o formato de saída ideal para garantir que todos vejam as cores corretas.

### 🔄 Prompts Reutilizáveis para Revisão Futura
Para aprofundar os estudos futuramente, deixei estes comandos prontos para a IA:
- "Como ajustar o balanço de branco do Apple Log?"
- "Quais as vantagens de usar o Color Space Transform?"
- "Como aplicar a saturação subtrativa no iPhone 15 Pro?"
