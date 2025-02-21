# Análise de Sentimentos com Language Studio no Azure AI

Este projeto utiliza a ferramenta Language Studio do Azure AI para realizar a análise de sentimentos de algumas sentenças.

## Etapas
1. Criação de um documento de entrada com sentenças para análise.
2. Uso do Azure Language Studio para analisar o sentimento das sentenças.
3. Exibição dos resultados, incluindo insights sobre o polaridade (positiva, negativa ou neutra).

## Resultados
Durante a análise, as sentenças foram classificadas da seguinte maneira:
- "O filme foi um desperdício de tempo, muito chato e previsível." -> Negativo
- "A qualidade do produto não é boa, me arrependi de comprar." -> Negativo
- "O atendimento no hotel foi péssimo, o serviço deixou a desejar." -> Negativo
- "A internet está super lenta hoje, estou muito frustrado." -> Negativo
- "A experiência foi horrível, não voltarei nunca mais." -> Negativo
- "Hoje o tempo está parcialmente nublado." -> Neutro
- "Comprei um livro novo ontem." -> Neutro
- "A reunião foi marcada para as 15h." -> Neutro
- "O produto chegou na data prevista." -> Neutro
- "O restaurante fica na Rua das Flores, 23." -> Neutro
- "Estou muito feliz com o meu novo trabalho, está sendo uma experiência incrível!" -> Positivo
- "A comida estava deliciosa, adorei cada prato!" -> Positivo
- "Esse é o melhor aplicativo que já usei, super intuitivo e útil." -> Positivo
- "O atendimento ao cliente foi excepcional, todos foram muito atenciosos." -> Positivo
- "A experiência foi maravilhosa, definitivamente voltarei em breve." -> Positivo

## Insights
A análise revelou que a polaridade pode ser muito útil para avaliar feedbacks de clientes em tempo real. Com a análise de sentimentos, é possível identificar rapidamente quando há um feedback negativo e agir para resolver o problema.

## Possibilidades de Aprimoramento
- Analisar grandes volumes de feedbacks de clientes automaticamente.
- Implementar um sistema de alerta para detectar sentimentos negativos.
