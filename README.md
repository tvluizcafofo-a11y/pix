# Documentação do Aplicativo PIX Recebimentos

1. Resumo do Projeto

O PIX Recebimentos é um aplicativo web progressivo (PWA) desenvolvido para permitir que comerciantes e prestadores de serviços gerem QR Codes PIX de forma simples e rápida, diretamente de seus dispositivos móveis, sem necessidade de internet após a instalação.

O aplicativo foi desenvolvido inteiramente em HTML, CSS e JavaScript puro, utilizando a biblioteca QRCode.js para a geração dos códigos e armazenamento local (localStorage) para persistência dos dados.

---

2. Funcionalidades

Funcionalidade Descrição
Cadastro do recebedor Permite salvar nome, chave PIX, cidade, TXID (opcional), descrição padrão e título personalizado do cabeçalho.
Geração de QR Code PIX A partir dos dados cadastrados e de um valor informado, gera o payload PIX e o QR Code correspondente.
Copia e Cola Exibe o payload completo para ser copiado e colado em aplicativos de pagamento.
Compartilhamento Compartilha o payload via apps de mensagem (se o dispositivo suportar).
Relatórios Lista todos os recebimentos gerados, com status (pendente/pago). Permite filtrar por dia ou período.
Confirmação de pagamento O usuário pode marcar manualmente um recebimento como "pago", atualizando o relatório.
Segurança de edição O botão "Gerenciar recebedor" fica oculto e só é ativado com 7 cliques no canto superior direito (modo de edição).
Máscara de chave PIX Na página inicial, a chave é parcialmente ocultada (CPF, telefone, e-mail) para segurança.
Personalização do cabeçalho O título do aplicativo pode ser alterado no cadastro.
