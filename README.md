# pylon-access

Política de acesso assinada do Pylon. O app baixa `access-policy.json` ao iniciar e só aceita o arquivo se a
assinatura Ed25519 conferir com a chave pública embutida nele. Editar este arquivo à mão invalida a assinatura.

Para mudar: gere uma nova política com `npm run license -- policy ...` no repositório do Pylon e substitua o arquivo aqui.
