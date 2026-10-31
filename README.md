# Beyond the Score — site de teste

**Beyond the Score: A Rehabilitation Nursing Approach to the Timed Up and Go**

Versão de teste de uma ferramenta pedagógica para estudantes e enfermeiros de reabilitação: do tempo do Timed Up and Go
ao movimento que o explica, e às áreas de intervenção, com o nível de evidência de cada ligação.

Site: https://hugoneves-tech.github.io/beyond-the-score-site/

Este repositório contém **apenas o site compilado**. O código-fonte é privado e, por agora, sem licença atribuída
(todos os direitos reservados).

## Estado

Versão em teste. Não dá diagnósticos, não substitui a avaliação clínica e não deve ser usada para decidir sobre
doentes. A análise por vídeo não está validada contra um sistema de referência.

## Privacidade

- O vídeo é processado no próprio dispositivo e não é enviado para nenhum servidor.
- Não há contas, análise de tráfego nem cookies.
- Na primeira utilização da análise, o navegador descarrega o modelo de pose (MediaPipe) de um CDN.
- O site pede `noindex`: não deve aparecer em motores de pesquisa enquanto estiver em teste.

## Dados

Os casos de Praticar usam pose de participantes do dataset MMU-FRiP (Kaggle, DOI 10.34740/KAGGLE/DSV/15068715), licença
CC BY-SA 4.0. Ver `LICENSE-DATA.md` para a atribuição e as alterações. O dataset não traz declaração de ética nem de
consentimento.

## Feedback

Hugo Neves, ESEUC.
