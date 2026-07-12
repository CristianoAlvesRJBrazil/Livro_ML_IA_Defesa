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
| [cap3_redes_neurais_deep_learning_defesa.ipynb](cap3_redes_neurais_deep_learning_defesa.ipynb) | 3 | Redes neurais e deep learning: do perceptron ao MLP, retropropagação, CNNs, RNNs/LSTM, regularização, TensorFlow/Keras e PyTorch, e uma CNN de triagem de imagens de sensor contra baseline clássica |
| [cap4_visao_computacional_defesa.ipynb](cap4_visao_computacional_defesa.ipynb) | 4 | Visão computacional para defesa: IoU, NMS e mAP implementados do zero, detectores de duas etapas (Faster R-CNN) e de uma etapa (YOLO), rastreamento multiobjetivo com Kalman + algoritmo húngaro, sensores SAR/satélite/VANT e pipeline de triagem para vigilância de área |
| [cap5_processamento_linguagem_natural_defesa.ipynb](cap5_processamento_linguagem_natural_defesa.ipynb) | 5 | PLN para inteligência: pré-processamento, TF-IDF calculado à mão, embeddings distribucionais, classificação temática e de sentimento, detecção de campanhas coordenadas, mecanismo de atenção, tradução neural e pipeline de triagem OSINT |
| [cap6_llm_inteligencia_osint_defesa.ipynb](cap6_llm_inteligencia_osint_defesa.ipynb) | 6 | LLMs em inteligência e OSINT: auto-atenção implementada em numpy, codificação posicional, embeddings contextuais com BERT (a ambiguidade de "manga" resolvida), BERT vs. GPT, fine-tuning/prompt/RAG, sumarização, riscos (alucinação, vazamento, dependência) e assistente OSINT com RAG |
| [cap7_aprendizado_por_reforco_defesa.ipynb](cap7_aprendizado_por_reforco_defesa.ipynb) | 7 | Aprendizado por reforço profundo: MDP e Bellman num mundo em grade com dilema de desconto, Q-learning tabular vs. iteração de valor, REINFORCE em PyTorch num ambiente de controle 1D, PPO no LunarLander com avaliação orientada à cauda, e reward hacking demonstrado ao vivo |
| [cap8_robustez_adversarial_defesa.ipynb](cap8_robustez_adversarial_defesa.ipynb) | 8 | Robustez adversarial: ataque de backdoor que passa na validação, exemplos adversariais FGSM e PGD implementados em PyTorch, treinamento adversarial (defesa min-max), curva de robustez comparando modelo comum vs. defendido, e a disciplina de verificação e validação (V&V) |
| [cap9_ia_embarcada_tempo_real_defesa.ipynb](cap9_ia_embarcada_tempo_real_defesa.ipynb) | 9 | IA embarcada e tempo real: restrições da borda e ambientes negados (DDIL), quantização int8 com TensorFlow Lite, pruning até o colapso, destilação de conhecimento professor→aluno, exportação ONNX e medição de latência no alvo (mediana vs. p95) |
| [cap10_etica_regulacao_governanca_defesa.ipynb](cap10_etica_regulacao_governanca_defesa.ipynb) | 10 | Ética, regulação e governança: marcos internacionais (CCW, OTAN, AI Act), controle humano significativo (in/on/out of the loop), princípios do DIH mapeados a propriedades técnicas, trilha de auditoria e ficha de modelo (model card) executáveis — o fecho da obra |

**Os dez capítulos estão disponíveis** — a coleção completa de notebooks acompanha a obra do primeiro modelo clássico à governança da IA de defesa, percorrendo os quatro módulos: Fundamentos e Modelos Clássicos (caps. 1–3), Percepção (caps. 4–6), Decisão Autônoma e Robustez (caps. 7–8) e Operação e Governança (caps. 9–10).

## 📽️ Slides das aulas

Slides de apoio para uso em sala, um conjunto por capítulo:

| Arquivo | Capítulo | Aula |
|---|---|---|
| [capitulo1_fundamentos_IA_ML.pptx](capitulo1_fundamentos_IA_ML.pptx) | 1 | Fundamentos de Inteligência Artificial e Machine Learning — Módulo I |
| [capitulo2_modelos_classicos_ML.pptx](capitulo2_modelos_classicos_ML.pptx) | 2 | Modelos Clássicos de Machine Learning para Defesa — Módulo I |
| [capitulo3_redes_neurais_deep_learning.pptx](capitulo3_redes_neurais_deep_learning.pptx) | 3 | Redes Neurais Artificiais e Deep Learning — Módulo I |
| [capitulo4_visao_computacional.pptx](capitulo4_visao_computacional.pptx) | 4 | Visão Computacional para Defesa — Módulo II |
| [capitulo5_processamento_linguagem_natural.pptx](capitulo5_processamento_linguagem_natural.pptx) | 5 | Processamento de Linguagem Natural para Inteligência — Módulo II |
| [capitulo6_llm_inteligencia_osint.pptx](capitulo6_llm_inteligencia_osint.pptx) | 6 | Modelos de Linguagem de Grande Escala em Inteligência e OSINT — Módulo II |

### Como usar

1. Abra o notebook desejado no [Google Colab](https://colab.research.google.com/) (menu *File → Open notebook → GitHub* e cole a URL deste repositório).
2. Execute as células em ordem (`Runtime → Run all`). Os notebooks usam bibliotecas já presentes no Colab (`numpy`, `matplotlib`, `scikit-learn` e, a partir do Capítulo 3, `tensorflow` e `torch`); o Capítulo 4 instala adicionalmente a `ultralytics` (YOLO) em uma célula própria. Nos Capítulos 3 e 4, uma GPU gratuita (*Ambiente de execução → Alterar o tipo de ambiente de execução → GPU T4*) acelera os treinos e a inferência, mas tudo executa também em CPU.
3. As células dos exercícios trazem marcações `# <--- ALTERE AQUI` indicando o que modificar.

### Reprodutibilidade

Todos os notebooks fixam a semente aleatória (`SEMENTE = 0`) — dados os mesmos dados, os mesmos resultados. Em sistemas de defesa, reprodutibilidade não é opcional.

## Ambiente e versões de referência

`scikit-learn` 1.5 · `TensorFlow` 2.18 · `PyTorch` 2.4 — ambiente principal: Google Colab; alternativa local: Anaconda/venv com aceleração CUDA quando disponível.

## Licença e contato

O código-fonte, os notebooks e os conjuntos de dados sintéticos de apoio são distribuídos sob **licença MIT**. Os exemplos operacionais não contêm dados classificados; quando inspirados em sistemas reais, foram reconstruídos a partir de fontes abertas e adaptados para fins didáticos.

Esta é uma edição em desenvolvimento (versão de trabalho). Erros, sugestões e propostas de novos estudos de caso podem ser comunicados ao autor para incorporação em edições futuras: **cristiano.alves.professor@gmail.com**
