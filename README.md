# Inteligência Artificial e Machine Learning Avançado para Defesa

*Dos algoritmos clássicos à IA embarcada em aplicações operacionais*

**Cristiano Alves** · Quantum Strategic AI · Rio de Janeiro, 2026

## Sobre o livro

Livro-texto dedicado à aplicação avançada de Inteligência Artificial (IA) e Machine Learning (ML) na engenharia de defesa, com carga compatível com um curso intensivo de **40 horas**, organizado em **quatro módulos** e **dez capítulos**. É a continuação natural do volume *Programação com Python Aplicada à Engenharia de Defesa* (Quantum Strategic AI, 2026).

A obra percorre um caminho que parte dos modelos clássicos de aprendizado de máquina, atravessa as arquiteturas profundas de percepção (visão computacional e linguagem natural, incluindo modelos de grande escala em OSINT), entra na decisão autônoma e no aprendizado por reforço aplicado a problemas táticos, e termina em três temas que respondem à pergunta mais difícil do setor: *quando* é seguro implantar um modelo, *como* é possível garantir robustez e *sob que* quadro normativo — robustez adversarial, IA embarcada em plataformas com restrições de campo e governança de sistemas autônomos, em alinhamento com a Estratégia Nacional de Defesa.

Cada capítulo combina exposição teórica formalizada, implementação executável em `scikit-learn`, `TensorFlow` ou `PyTorch`, estudo de caso operacional extraído de aplicações reais — do *Project Maven* aos sistemas brasileiros de monitoramento de fontes abertas — e exercícios em três níveis: **essencial** · **tático** · **estratégico**.

**Público-alvo:** oficiais e analistas das Forças Armadas em cursos de altos estudos, engenheiros e pesquisadores da Base Industrial de Defesa, analistas de inteligência, alunos e docentes de pós-graduação em Engenharia, Ciência da Computação, Defesa e Estudos Estratégicos, e profissionais de consultoria de risco e segurança cibernética.

## 📖 Amostra do livro

Uma amostra em PDF, com a apresentação da obra e os três primeiros capítulos, está disponível neste repositório: **[livro_IA_ML_defesa_3.pdf](livro_IA_ML_defesa_3.pdf)**

## 📓 Notebooks das aulas práticas

Cada capítulo é acompanhado de uma aula prática em formato Google Colab, com teoria, código executável, visualizações e exercícios:

| Notebook | Capítulo | Tema |
|---|---|---|
| [cap1_fundamentos_IA_ML_defesa.ipynb](cap1_fundamentos_IA_ML_defesa.ipynb) | 1 | Fundamentos de IA e ML: as três tradições, os três regimes de aprendizado e o pipeline de cinco etapas |
| [cap2_modelos_classicos_ML_defesa.ipynb](cap2_modelos_classicos_ML_defesa.ipynb) | 2 | Modelos clássicos de ML supervisionado: regressão linear e logística, árvores e florestas aleatórias, SVM, métricas para classes desbalanceadas e pipeline comparativo |

Novos notebooks serão adicionados à medida que os capítulos forem concluídos.

### Como usar

1. Abra o notebook desejado no [Google Colab](https://colab.research.google.com/) (menu *File → Open notebook → GitHub* e cole a URL deste repositório).
2. Execute as células em ordem (`Runtime → Run all`). Não é necessária nenhuma instalação: os notebooks dos capítulos iniciais usam apenas `numpy`, `matplotlib` e `scikit-learn`, já presentes no Colab.
3. As células dos exercícios trazem marcações `# <--- ALTERE AQUI` indicando o que modificar.

### Reprodutibilidade

Todos os notebooks fixam a semente aleatória (`SEMENTE = 0`) — dados os mesmos dados, os mesmos resultados. Em sistemas de defesa, reprodutibilidade não é opcional.

## Ambiente e versões de referência

`scikit-learn` 1.5 · `TensorFlow` 2.18 · `PyTorch` 2.4 — ambiente principal: Google Colab; alternativa local: Anaconda/venv com aceleração CUDA quando disponível.

## Licença e contato

O código-fonte, os notebooks e os conjuntos de dados sintéticos de apoio são distribuídos sob **licença MIT**. Os exemplos operacionais não contêm dados classificados; quando inspirados em sistemas reais, foram reconstruídos a partir de fontes abertas e adaptados para fins didáticos.

Esta é uma edição em desenvolvimento (versão de trabalho). Erros, sugestões e propostas de novos estudos de caso podem ser comunicados ao autor para incorporação em edições futuras: **cristiano.alves.professor@gmail.com**
