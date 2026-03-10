--------------------------------------------

# NVIDIA-AMD-Tecnology-and-hardware-

--------------------------------------------

PTBR:
Notebooklm, projeto prático. Bootcamp Bradesco Gen AI e Dados

--------------------------------------------

Projeto: Assistente Especialista em Hardware para IA (AMD vs NVIDIA 2026)

Objetivo do Projeto
O objetivo deste projeto foi utilizar o NotebookLM como uma ferramenta de apoio à decisão e "segundo cérebro" para navegar no complexo ecossistema de hardware voltado para Inteligência Artificial em 2026
. O foco principal foi analisar e comparar as ofertas da AMD e NVIDIA para diferentes perfis de uso, desde o consumidor doméstico (notebooks e GPUs de entrada) até infraestruturas de grande escala (datacenters e parcerias globais)

--------------------------------------------

Como o NotebookLM foi utilizado
O NotebookLM serviu como o hub central de processamento de informações multimodais. Ele permitiu:
Sintetizar transcrições de entrevistas extensas com executivos e análises técnicas de vídeo

--------------------------------------------

Cruzamento de dados entre relatórios financeiros de mercado e especificações técnicas brutas de lançamentos

Tradução de linguagem técnica (como TOPS e TFLOPS) em insights práticos para o consumidor final

--------------------------------------------

Fontes e Documentos Utilizados
A base de conhecimento foi composta por:
Vídeos e Transcrições: Entrevistas da AMD Brasil (Priscila Bianchi), análises técnicas do canal Adrenaline sobre FSR 4 e guias de uso de ROCm no Linux

Relatórios de Pesquisa (2026): Análises profundas da Finterra sobre a NVIDIA ("Sovereign of the Silicon Age") e a AMD ("Catching up with NVIDIA")

Benchmarks de IA: Dados do MLPerf Inference v5.1 e comparativos de "CUDA Gap" entre MI300X e H100

Documentação Técnica: Blogs oficiais da AMD sobre as séries Instinct MI350/400 e arquiteturas Ryzen AI

--------------------------------------------

O Processo de Análise/Aprendizado
O projeto seguiu três fases distintas:
Fase de Coleta: Upload de fontes variadas para cobrir tanto a perspectiva comercial (promoções) quanto a técnica (performance de inferência)

Fase de Consulta: Realização de prompts específicos para identificar o melhor custo-benefício em diferentes faixas de preço no mercado brasileiro

Fase de Comparação: Avaliação crítica entre a maturidade do software (CUDA da NVIDIA) e a abertura do ecossistema (ROCm da AMD)

--------------------------------------------

Principais Resultados e Insights
Liderança em IA Local: A AMD tomou a dianteira em notebooks com a série Ryzen AI 400, oferecendo até 60 TOPS, o que a posiciona como líder em eficiência para PCs Copilot+

Importância da VRAM: Para desenvolvedores de IA, a capacidade de memória (VRAM) tornou-se a métrica principal, superando o FPS de jogos. GPUs como a RTX 5090 (32GB) e RTX 4090 (24GB) são os padrões recomendados para LLMs locais

Avanço em Datacenters: A AMD emergiu como a principal alternativa para inferência em larga escala, com a série Instinct MI350 oferecendo até 50% de economia de custo em relação à NVIDIA em cenários específicos

Democratização do Preço: Identificou-se que em 2026, notebooks com IA robusta (NPU de 50 TOPS) já podem ser encontrados abaixo de R$ 5.000 no Brasil

--------------------------------------------------------------------------------

Evidências do uso do NotebookLM

Exemplos de Prompts Utilizados
"Quais processadores AMD são recomendados para IA em notebooks?"
"Quais as gpus mais custo benefício para IA?"
"Quais são as melhores promoções da AMD na Semana do Consumidor?"
Respostas Geradas pela IA
(As respostas detalhadas foram integradas no corpo do README e estão arquivadas nas sessões anteriores deste chat, fornecendo dados sobre o modelo Ryzen 7 7735HS para orçamentos de R$ 3.000 e as NPUs da linha Ryzen AI 300
.)

--------------------------------------------------------------------------------

Arquivos Adicionais

# Estratégia de Prompts para Hardware e IA

Para este projeto, utilizei uma abordagem de "Refinamento Contextual":

1. **Atribuição de Persona:** "Aja como um segundo cérebro especializado em tecnologias AMD e NVIDIA".
2. **Delimitação Temporal:** Foco em dados de 2026 para garantir que a IA não usasse informações obsoletas de 2023-2024.
3. **Métricas Objetivas:** Exigência de respostas baseadas em TOPS, TFLOPS e capacidade de VRAM em vez de adjetivos vagos.
4. **Foco Geográfico:** Solicitação de dados específicos para o varejo brasileiro (preços em Reais e lojas locais como KaBuM!).

Documentos de Base

transcricao_entrevista_amd_brasil.txt
relatorio_finterra_nvidia_2026.pdf
comparativo_cuda_vs_rocm_aimultiple.pdf
amd_road_map_datacenter_tbr.txt

--------------------------------------------
