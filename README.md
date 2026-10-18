# F1 Career Mobile — versão para navegador

Build WebGL do jogo em desenvolvimento. O código-fonte fica em um repositório privado.
Para jogar no iPhone, abra no Safari: https://vitorvolpe14-arch.github.io/f1-career-play/

- **Modos:** treino livre; corrida rápida contra 9 ou 19 adversários da IA (3, 5 ou 10 voltas, 4 níveis de dificuldade);
  **temporada** (uma etapa por circuito, classificação, grid de 20 carros, pontos 25-18-15-12-10-8-6-4-2-1 e
  classificação de pilotos e equipes, salva no aparelho); **carreira** (crie seu piloto, comece numa equipe pequena
  da Fórmula Base e suba para a Fórmula Acesso e a Fórmula Elite com bons resultados; reputação, propostas de
  contrato, desenvolvimento do carro e notícias de cada etapa; salva no aparelho).
- **Circuitos:** Monza, Interlagos, Spa-Francorchamps, Silverstone e Red Bull Ring. Traçados e pit lanes derivados do
  OpenStreetMap — © OpenStreetMap contributors, licença ODbL (https://www.openstreetmap.org/copyright). Os nomes dos
  circuitos e das curvas aparecem só como referência, sem autorização verificada e para uso pessoal ("Red Bull Ring"
  contém marca registrada).
- **Pilotos, equipes e categorias:** todos fictícios (placeholder) — equipes com nomes de cores e pilotos com sobrenomes
  inventados, conferidos contra uma lista de pilotos reais. As categorias Fórmula Base, Acesso e Elite seguem o molde
  da escada F3 → F2 → F1, mas não são os campeonatos oficiais. Não há logotipos nem patrocinadores reais.
- **Gráficos:** texturas reais CC0 de asfalto, grama, brita, zebras, muros e pit lane (Poly Haven e ambientCG, licença
  CC0 — https://polyhaven.com/license e https://docs.ambientcg.com/license/) e céu HDRI fotográfico CC0 (Poly Haven).
  Carro, cenário e HUD são arte própria gerada em código. Fonte Titillium Web (SIL Open Font License 1.1).
  Auto/Alto/Médio/Baixo no menu de ajustes (engrenagem).
- **Clima:** seco, chuva ou variável (a chuva chega no meio da sessão), com pista molhada, spray e pneus intermediários
  e de chuva. Simulação provisória do jogo.
- **Pneus e estratégia:** 5 compostos, desgaste proporcional à distância de um GP, regra dos 2 compostos, botão BOX
  e estratégia própria de cada IA. DRS e ERS seguem regras provisórias no estilo 2011–2025 (o regulamento de 2026 não
  tem DRS). No teclado: Q = DRS, E = ERS.
- **Diagnóstico:** acrescente `?debug` ao endereço para ver a posição do carro e da câmera; `?laps=1` para corridas de
  1 volta; `?track=interlagos` (ou `spa`, `silverstone`, `redbullring`) para abrir num circuito.
