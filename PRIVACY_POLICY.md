# Política de Privacidade do InvestView

Vigência: 13 de novembro de 2026

Última atualização: 16 de novembro de 2026

## 1. Responsável e finalidade

O InvestView — Painel Inteligente é uma extensão para Google Chrome
desenvolvida por **Iury Coimbra**. Sua finalidade é permitir que o usuário
acompanhe ativos financeiros e organize localmente informações de sua carteira
em um painel personalizável.

O InvestView não oferece consultoria, recomendação ou intermediação de
investimentos e não executa ordens financeiras.

## 2. Dados tratados

O usuário pode informar ou gerar no painel:

- ativos selecionados, categorias e ordem dos cartões;
- datas de compra, quantidades e preços unitários pagos;
- preferências de período, tabela, curvas e organização dos painéis.

Esses dados podem revelar informações financeiras do usuário. Eles são
tratados apenas para calcular e exibir a carteira solicitada.

## 3. Armazenamento local

Os dados da carteira e as preferências são salvos em `chrome.storage.local`, no
perfil local do Chrome. O InvestView não possui servidor próprio, banco de dados
remoto, telemetria, publicidade ou sistema de contas. O desenvolvedor não recebe
nem consegue consultar o conteúdo armazenado localmente pela extensão.

Os registros permanecem no dispositivo até serem excluídos pelo usuário no
painel, substituídos pela restauração das configurações ou removidos com a
desinstalação da extensão.

## 4. Comunicações com serviços externos

Para fornecer pesquisa, cotações, históricos e gráficos, o InvestView utiliza
conexões HTTPS com:

- **Yahoo Finance** (`query1.finance.yahoo.com` e
  `query2.finance.yahoo.com`): recebe o código do ativo, período e intervalo
  necessários para consultar históricos de fechamento;
- **TradingView** (`scanner.tradingview.com`): recebe códigos ou termos de
  busca para localizar ativos e consultar cotações;
- **widgets incorporados do TradingView**: recebem o código do ativo e as
  configurações visuais necessárias para exibir o gráfico.

Datas de compra, quantidades e preços pagos não são incluídos nas requisições
de cotações ou históricos. Os gráficos incorporados são executados em quadros
isolados de outro domínio; o InvestView não acessa cookies ou dados internos
desses quadros.

Como em qualquer acesso a um serviço na internet, Yahoo Finance e TradingView
podem receber informações técnicas da conexão, como endereço IP, agente do
navegador e horário, de acordo com suas próprias políticas.

## 5. Compartilhamento e uso

O InvestView não vende, aluga ou utiliza dados para publicidade, avaliação de
crédito ou criação de perfis. O compartilhamento limita-se aos códigos de ativos
e parâmetros técnicos necessários aos provedores descritos acima.

O uso das informações está limitado à finalidade declarada nesta política e
segue os requisitos de Uso Limitado da Política de Dados do Usuário da Chrome
Web Store.

## 6. Permissões do Chrome

- `storage`: preservar localmente ativos, compras e preferências;
- acesso aos hosts do Yahoo Finance: consultar históricos de fechamento;
- acesso ao scanner do TradingView: pesquisar ativos e consultar cotações;
- `frame-src` do TradingView: incorporar os gráficos financeiros.

A extensão não solicita acesso ao histórico de navegação, páginas visitadas,
senhas, e-mails, contatos, localização, câmera, microfone ou arquivos pessoais.

## 7. Segurança

As comunicações externas utilizam HTTPS. O código valida e normaliza dados
antes do armazenamento, limita os domínios acessíveis e não carrega scripts
executáveis remotos. Nenhum mecanismo digital, contudo, oferece segurança
absoluta; o usuário deve manter o Chrome e a extensão atualizados e proteger seu
perfil do navegador.

## 8. Direitos e controle do usuário

Nos termos aplicáveis da Lei Geral de Proteção de Dados (LGPD), o usuário pode
conhecer o tratamento descrito nesta política, corrigir dados editando as compras
e ativos, e excluir registros pelo painel ou pela desinstalação. Como os dados
da carteira não são enviados ao desenvolvedor, essas operações são realizadas
diretamente no dispositivo.

## 9. Crianças e adolescentes

O InvestView não é direcionado especificamente a crianças e não coleta
intencionalmente dados para identificar a idade do usuário.

## 10. Atualizações e contato

Esta política será atualizada quando houver mudança relevante na finalidade,
nas permissões ou no tratamento de dados. A data da última atualização será
indicada no início do documento.

Solicitações de suporte ou privacidade podem ser registradas no canal público
do projeto:

https://github.com/IuryCoimbra/investview-privacy/issues
