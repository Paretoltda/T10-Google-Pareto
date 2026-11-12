# Pizza-Em-Casa-Pareto

Página de VSL do **Pizza em Casa** (HTML estático, sem build).

- Domínio: `essencialpramim.com.br`, o site precisa ficar na **raiz** do domínio.
- `/` é a página da VSL (Vturb), `/termos` e `/privacidade` são as páginas legais.
- Empresa: Pareto Treinamentos Digitais LTDA — CNPJ 58.176.225/0001-83.
- E-mail de contato usado nas páginas: `contato@essencialpramim.com.br` (troque se for outro; está em `index.html`, `termos/` e `privacidade/`).
- Rastreamento em todas as páginas: Meta Pixel, Utmify e Google (GTM-MC86FPMM).
- Hospedagem em S3 + CloudFront: se `/termos` e `/privacidade` derem erro, aplique a CloudFront Function que acrescenta `index.html` em URLs de pasta.
