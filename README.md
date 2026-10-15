# KRYVEXPT — OSINT Workspace

Painel local em HTML, CSS e JavaScript para organizar investigações responsáveis com fontes abertas.

## Iniciar no Android / Termux

1. Coloca a pasta `KRYVEXPT` em `~/KRYVEXPT`.
2. No Termux, instala Python se necessário: `pkg install python -y`
3. Inicia: `cd ~/KRYVEXPT && python -m http.server 8080`
4. Abre `http://127.0.0.1:8080` no navegador.
5. Mantém o Termux aberto. Para parar, usa `CTRL+C`.

## Inclui
- Pesquisa manual em motores de pesquisa e Wikipedia.
- Registo de URLs públicos e notas de verificação.
- Caderno de investigação local.
- Cálculo SHA-256 no navegador.
- Análise básica de URLs.
- Exportação JSON.
- Dados guardados no armazenamento local do navegador.

## Limites
Não rastreia pessoas, não revela localização em tempo real, não acede a contas privadas, não contorna autenticação e não recolhe dados ocultos. Confirma resultados e respeita a privacidade e a lei. Não guardes palavras-passe ou dados sensíveis.
